# abmesh-carve
To be used with arnholm/xcsg. 

This fork of carve contains fixes to allow static compilation for
* Windows MSVC2013 Express compiler with boost 1.59, x64
* Linux Ubuntu GNU g++ with boost 1.62, x64

## Basic build instructions

* Use CMake Gui on both platforms, disable dev warning (Options menu)
* Enable only CARVE_BOOST_COLLECTIONS, CARVE_SYSTEM_BOOST, CARVE_USE_EXACT_PREDICATES
* Set "Where to build" ../abmesh-carve/cmake_build
* Windows MSVC2013: Build carve project in cmake_build/carve.sln
   * Static libs under cmake_build/lib/Release and cmake_build/lib/Debug
* Linux: Build with makefile under abmesh-carve/cmake_build/src
   * Static lib under cmake_build/lib


