# Dnkvw Raylib Minimal Example

A minimal example that demonstrates the usage of Dnkvw with Raylib.

## Building

This project uses CMake. Make sure you have at least version 3.15.
To build it, use the following commands:
```console
dani@khan:~$ mkdir build
dani@khan:~$ cd build
dani@khan:~$ cmake ..
<CMAKE CONFIGURE OUTPUT HERE>
```

The cmake configuration may take longer because it will automatically download raylib if you don't already have it installed.
It also may fail if you don't have dnkvw installed. In that case look [here](https://github.com/DaNiKhan-GbR/DaNiKhan-V-Window#readme) for instructions.
If you installed dnkvw in a local directory you can specify the path in the dnkvw_DIR CMake variable.

## Running

If you run it and you don't have dnkvw installed systemwide you may get an error because the shared library (on Window the DLL) of dnkvw is missing.
In that case copy the library (dnvw.\[dll|dylib|so\]) from your dnkvw install directory into the same directory as the executable.
