Algorithms and Graphs
=====================

Academic discipline exercises.

Building
--------

In order to build, you should have installed `cmake` program.

This project is designed to be build out-of-source, in a separated folder 
from the source:

```
	$ mkdir build; cd build
	$ cmake ..
	$ make
```

Target Options
--------------

The default build target is "Debug".  You may set the target
to "Release", which will strip debugging information and
enable all optimizations (on "Debug" no optimization is enabled),
running this command:

	$ cmake -D CMAKE_BUILD_TYPE=Release ../


Additionally, to get all `make` output, run `make VERBOSE=1`.

Cleaning
--------

On `build` directory type `make clean` to remove all
files generated by compiler and linker.  To remove all files generated
just delete the folder `build`.

Testing
-------

To run the test suite, on `build` directory type:

```
	$ ctest
```


