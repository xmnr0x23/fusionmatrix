# FusionMatrix

FusionMatrix is a node based matrix library for Blackmagic Design Fusion.

## Acknowledgements

- Kristof Indeherberge
- Cédric Duriau

## Requirements

- [lua-matrix](https://github.com/davidm/lua-matrix)

## Installation

**FusionMatrix**

1. Clone or download the repository.
2. Set the absolute path of the **./fusion** directory into the Fusion
   **UserPaths:** path mapping.

**lua-matrix**

1. Clone or download the repository.
2. Set the absolute path of the **./lua** directory into the Fusion
   **LuaModules:** path mapping.

## Contents

**Fuses**

- `creatematrix.fuse`: Fuse to create a 4x4 matrix.
- `matrixcolortransform.fuse`: Fuse that applies a color matrix on a color vector.
- `matrixconcatenatehorizontal.fuse`: Fuse to concatenate two matrices horizontally.
- `matrixconcatenatevertical.fuse`: Fuse to concatenate two matrices vertically.
- `matrixfromarray.fuse`: Fuse to create a matrix from an array stored as JSON string.
- `matrixinvert.fuse`: Fuse to invert a matrix.
- `matrixmultiply.fuse`: Fuse to multiply two matrices.
- `matrixtranspose.fuse`: Fuse to transpose a matrix.
- `readmatrix.fuse`: Fuse to read a matrix from metadata of an image.
- `writematrix.fuse`: Fuse to write a matrix to metadata of an image.

**Modules/Lua**

- `matrixutils.lua`: Core module using lua-matrix.
