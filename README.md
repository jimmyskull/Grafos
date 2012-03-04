Algorithms and Graphs
=====================

Academic discipline exercises.

Building
--------

In order to build, you should have installed `cmake`.

This project should be build out-of-source:

```
	$ mkdir build; cd build
	$ cmake ..
	$ make
```

The default build target is "Debug".  You may set the target
to "Release", which will strip debugging information and
enable all optimizations (on "Debug" no optimization is enabld),
running this command:

	cmake -D CMAKE_BUILD_TYPE=Release ../


Additionally, yf you want to get the `make` output (command-line execution),
run `make VERBOSE=1`.

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


