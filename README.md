# SDLNGL
![alt tag](http://nccastaff.bournemouth.ac.uk/jmacey/GraphicsLib/Demos/BlankNGL.png)

This is the simplest SDL / NGL demo using a basic SDL2.0 window and core profile OpenGL context


This demo has been modified to work with glsl 330 and OpenGL 3.1 as default. If you need a higher OpenGL version modify main.cpp and change the following lines
```C++
  SDL_GL_SetAttribute(SDL_GL_CONTEXT_MAJOR_VERSION, 3);
  SDL_GL_SetAttribute(SDL_GL_CONTEXT_MINOR_VERSION, 2);

```
changing the major and minor version numbers.