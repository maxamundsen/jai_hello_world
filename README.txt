Simple project starter for Jai projects.

Contains a build.jai file, does a little bit of setup before compiling the `main.jai` file in `/src/`.

Build options:

-- debug   :
Sets `DEBUG` variable in build program to `true`.
No optimizations, outputs to `build_debug` directory, sets `DEBUG` constant in main program to `true`.

-- release :
Sets `DEBUG` variable in build program to `false`.
Turns on all optimizations within LLVM, sets output to the `build_release` directory, and sets the `DEBUG` constant in the main program to `false`.

--no_output:
Compiles program as fast as possible, omitting any output. Useful for checking compile errors quickly without wasting time building the executable.
