# Dactyl CC Mini

Work in Progress.

A smaller version of the [Dactly CC keyboard](https://github.com/mjohns/dactyl-cc) with the following changes (besides key removal):

* Thumb end key removed and alt and home key moved down.
* Thumb is moved in closer in the x direction.
* Entire height is shifted down to keep it as low profile as possible.

![image](https://imgur.com/IP2UYYA.jpg)

```
// Build. Requires g++.
./build.sh.

// If changing files under util you must run a clean build.
./build.sh --clean

// To generate STL from command line:
openscad -o things/left.stl out/left.scad
```
