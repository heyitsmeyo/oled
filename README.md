This is a pico sdk project to test an oled display ssd1306 on a raspberry pi pico 


![469050796_8766733976767992_6333603364607256048_n-ezgif com-video-to-gif-converter (1)](https://github.com/user-attachments/assets/4c896042-1a5e-454c-ad64-9e5c5d804ca0)



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
