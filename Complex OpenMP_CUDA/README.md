RayTracing Parallel
-----------------

This is a Ray Tracing implementation in C++ using OpenMP and Cuda.

This code implements rays' intersection with spheres and plane.
There is also reflection.

Start of this project was completed in the comp 137 (parallel computing) class

Run
-----------------
The executables will be created in the folder "build". To run
the program, just type ./RayTracing_<version>, passing as argument the
width, height and the fov (field of view) desired -- this last
argumnet is optional (default value is 60º).

Example
-----------------
The following image was generated typing the
following command after build the source:

./RayTracing_openmp 800 600 60

