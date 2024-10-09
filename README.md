# Local Build Instructions #

Download [Binaries](https://github.com/glfw/glfw/releases/download/3.4/glfw-3.4.bin.WIN64.zip)

Unzip to a temporary directory

copy `include\GLFW` to `C:/glwf/GLFW`
copy `lib-{your visual studio version}\` to `C:/glfw/`

then build as normal

you will need to link the opengl binary that comes with visual studio

on the class machines it is: 
`C:\Program Files (x86)\Windows Kits\10\Lib\10.0.22621.0\um\x64\OpenGL32.lib` you may have to go spelunking on your machine