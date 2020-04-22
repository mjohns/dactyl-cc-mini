# Dactyl CC Mini

A smaller version of the [Dactly CC keyboard](https://github.com/mjohns/dactyl-cc) with the following changes (besides key removal):

* Pinky column moved down in the y direction.
* Thumb end key removed and alt and home key moved down.
* 3 and 4 key are shifted up in the z direction.
* Thumb is moved in closer in the x direction.

![image](https://imgur.com/IP2UYYA.jpg)

```
// Build. Requires g++.
./build.sh.

// If changing files under util you must run a clean build.
./build.sh --clean

// To generate STL from command line:
openscad -o things/left.stl out/left.scad
```
