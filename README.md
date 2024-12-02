This is a pico sdk project to test an oled display ssd1306 on a raspberry pi pico 

You need to configure pico-sdk by cloning it first : 

    https://github.com/raspberrypi/pico-sdk

Add folder with a name of project you choose

Copy c file , CMakelists.txt file into that folder 

in that folder , add another folder named build : 

    Mkdir build 

Go to that folder :

    cd build 

Configure the sdk path : 

    export PICO_SDK_PATH=/pico-sdk path 

Run :

    cmake .. 

then : 

      make 

      


# if you like the project , you can donate us for more : 

    https://ko-fi.com/heyitsmeyo
