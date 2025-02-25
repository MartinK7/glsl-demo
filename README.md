GLSL Demo
=========

Real Time 3D Demo made in 2008

Port for linux & How to compile
-----
This repo is forked from original repo at
https://github.com/yagero/glsl-demo
But here is added support (port) for linux.

Dependencies:

OpenGL, GLU, GLUT, GLEW

Steps:

* `mkdir build`
* `cd build`
* `cmake ..`
* `make`
* `cd ../exec/`
* `./glsl_demo`


Video
-----

https://www.youtube.com/watch?v=9N-kgCqy2xs


Keys
----

* SPACE:  switch camera mode (auto/free)
* MOUSE:  control the camera view in free camera mode
* ARROWS: move the camera in free camera mode
* NUMPAD NUMBERS: teleport to a scene in free camera mode
	* 1 - island scene
	* 2 - shadow mapping scene
	* 3 - reflection/refraction scene
	* 4 - toon mapping scene
	* 5 - relief mapping and fur scene

* +/-:   speed up/down the moving speed of the camera (and of the world)

* ZQSD:  change sun position (in the island scene)

* A:     enable/disable anaglyph view
* B:     enable/disable bloom post effect
* V:     enable/disable vignette post effect
* N:     enable/disable noise post effect
* C:     enable/disable depth of field post effect
* T:     show/hide camera splines

* F2:    reload and recompile the shaders (lets you iterate faster if you want to play with the shader source code)

Have fun!
