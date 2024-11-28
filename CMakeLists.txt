cmake_minimum_required(VERSION 3.13...3.27)

# initialize the SDK based on PICO_SDK_PATH
# note: this must happen before project()
include(pico_sdk_import.cmake)

project(oled)

# initialize the Raspberry Pi Pico SDK
pico_sdk_init()



add_executable(ssd1306_i2c
        ssd1306_i2c.c
        )

# pull in common dependencies and additional i2c hardware support
target_link_libraries(ssd1306_i2c pico_stdlib hardware_i2c)

# create map/bin/hex file etc.
pico_add_extra_outputs(ssd1306_i2c)

pico_enable_stdio_usb(ssd1306_i2c 1)


# add url via pico_set_program_url
#example_auto_set_url(ssd1306_i2c)
