## WebGL!

Notes related to learning about WebGL, with focus on GLSL shaders.

*files:*

* `cos_color.html`: Dynamically change background Color
* `varying_test.html`:  Determine color with a 'Varying' Variable
* `speed_test_mil.html`:  Update 1,000,000 Points animation
* `gpu_row_reduce.html`: Reduce Matrix with `gpu.js`
* `uniform_test.html`: Animation with Uniforms
* `webgl_min.html`: Minimum Setup
* `color_vertex_min`: Vertex Colors
* `turbo_test.html`: Setting/Getting with `turbo.js`
* `mouse_sand.html`: Texture Mouse Input
* `texture.html`: Minimum Texture
* `texture_anim.html`: Texture Animation
* `shader_2d.html`: Mat3 Uniform test
* `shader_3d_test.html:` Mat4 Uniform test
* `min_surface.html`: Float Texture with Interleaved uv's
* `min_read_fb.html`: Read pixel from frame buffer
* `tex_mat.html`: Display uv coords for texture
* `webgl2tex.html`: Texture with webgl **2**
* `tex_read_write_0.html`: Read / Write to textures
* `tex_read_write_1.html`: ... add ( functions + if/else ) in fragment shader

*to do:*

* Write a shader to clear under a pivot
* Write get/set functions in the fragment shader
* Write a 1-channel matrix-texture interface

*about:*

The goal of this project is to learn about GPGPU with WebGL.  Ideally, this project would culminate in writing a WebGL-Accelerated ping-pong solver for large linear systems.  This would be really useful for engineering stuff.  

However, it appears to be a long road from making triangles to doing efficient GPU computation.  The current mini-goal is to just put in hours doing stuff with WebGL.  Writing short scripts is a way to maintain interest in the subject.  

Two resources that have been really helpful are the `turbo.js` source code and notes from:  http://www.vizitsolutions.com/portfolio/webgl/gpgpu/.

*links:*

Talk by creators of gpu.js:
https://www.youtube.com/watch?v=nUAZxpE9s9w

