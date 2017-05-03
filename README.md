# abmesh-carve
To be used with arnholm/xcsg. 

This fork of carve contains fixes to allow static compilation for
* Windows MSVC2013 Express compiler with boost 1.59, x64
* Linux Ubuntu GNU g++ with boost 1.62

## Basic build instructions

* Use CMake Gui on both plaforms 
* Disable all options except CARVE_BOOST_COLLECTIONS and CARVE_SYSTEM_BOOST
* Windows: Build Carve project in generated Visual Studio 2013 solution
* Linux: Use generated makefile under src

Compilation generates a number of warnings, but succeeds.
