# Journey-Through-OpenGL

## Session 1
Just created a window. Simple so far

## Session 2
Completed Hello Triangle! Questions I have so far:
    1) Why do we bind the vertex array and buffer to 0 after we create them?

## Session 3
I will now start to learn about Element Buffer Objects. It allows you to draw by index. Updated: I was able to draw a rotated cube!

## Session 4
This is all about shaders. So far, I wonder how using uniforms using others things such as an EBO (turns out you don't need to do anything special, I just made the green value too high.
Note to self: check if color values are in the correct range)

## Session 5
I will now learn about different configurations of the VBO, filling the VBO with both vertices and colors. I don't know how practical it is mixing the two, but I will see in the future (I gotta say, now that I really understand how the vertex buffer works, this is so much easier to understand)

## Session 6
Now I'm working on using textures. For now, the texture is not loading... (fixed!). I need to look up texture units in the future. For some reason, the face texture isn't loading right (My god. The problem was that I was using GL_RGB instead of GL_RGBA. THE IMAGE HAD TRANSPARENCY)

## Session 7
Time to use glm. Having trouble input a matrix into a uniform right now. (It was because I was using the vertex shader as the input shader instead of the shader program). I find it weird that you need to create a new matrix to send to the uniform each frame of the program

## Session 8
This will be all about coordinate systems. There are 5 coordinate systems:
    1) Local: Coordinates relative to an object
    2) World: Relative to the world's origin
    3) View Space: Coordinates relative to the camera's view?
    4) Clip Space: In -1.0 to 1.0 range, determines which vertices are on screen
    5) Screen Space: -1.0 to 1.0 range defined by `glViewport`, these coordinates will be       rasterized
    I did the rotating cube and my question is how are the textures orientened on the cube? I also learned how to draw multiple things at once

## Session 9
The final section in the "Getting Started" tab. Now I will make a camera. (So far, the camera stuff has been pretty simple. Honestly, OpenGL is more simple than I thought it would be.)

