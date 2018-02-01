# ga2018-homework2
Second homework for Game Architecture.

In this homework you will implement parts of vector and matrix math library. 
See src/engine/math/ga_vec3f.h and src/engine/math/ga_mat4f.cpp.

To determine if your implementation is functionally correct, the engine runs
some simple unit tests. See src/engine/math/ga_vec3f.tests.cpp and
src/engine/math/ga_mat4f.tests.cpp.

For this homework you must correctly implement the stubbed out methods
in ga_vec3f and ga_mat4f (search for "TODO: Homework 2") and all unit tests
must pass.

This repo is meant to be built stand-alone, with just the math code. If you wish
to incorporate the rest of the engine, you'll need to update CMakeLists.txt

Run build\setup_win64.bat, then in the newly-created folder, open gamearch2.sln
in Visual Studio. Build the project, and set "ga" to be your startup project,
as before. 