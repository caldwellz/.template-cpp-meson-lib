# template-cpp-meson-lib
This is a template for MPL2-licensed C/C++ library projects using the Meson build system. It provides the structure to build a central library plus optional test executables. It can also automatically generate pkgconfig info and install things into relevant subdirectories based on the project name.  
At a bare minimum, you should change or fill in:
* The project name (the empty string at the top of the main meson.build).
* The list of additional source code files (lib_srcs in src/meson.build).
* Any library dependencies (lib_deps in src/meson.build).
  * SDL2 is configured as a dependency there and in subprojects/sdl2.wrap (currently set to 2.24.0) as an example.
* This ReadMe file (README.md).
