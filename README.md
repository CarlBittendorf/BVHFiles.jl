# BVH

[![Build Status](https://travis-ci.com/CarlBittendorf/BVH.jl.svg?branch=master)](https://travis-ci.com/CarlBittendorf/BVH.jl)
[![Build Status](https://ci.appveyor.com/api/projects/status/github/CarlBittendorf/BVH.jl?svg=true)](https://ci.appveyor.com/project/CarlBittendorf/BVH-jl)
[![Coverage](https://codecov.io/gh/CarlBittendorf/BVH.jl/branch/master/graph/badge.svg)](https://codecov.io/gh/CarlBittendorf/BVH.jl)
[![Coverage](https://coveralls.io/repos/github/CarlBittendorf/BVH.jl/badge.svg?branch=master)](https://coveralls.io/github/CarlBittendorf/BVH.jl?branch=master)

BVH.jl is a package for working with BioVisionHierarchy files, a file format which stores motion capture 
data in a hierarchical structure. 

BVH.jl uses [graphs](https://github.com/JuliaGraphs/LightGraphs.jl) to represent and manipulate the data.

## Examples

![Original new](https://user-images.githubusercontent.com/85636219/121555428-4b36bd00-ca13-11eb-9ef7-8341cf912ba0.png)
![Icon new](https://user-images.githubusercontent.com/85636219/121555373-3eb26480-ca13-11eb-89e2-074c1e0da9ae.png)
![Transformed new](https://user-images.githubusercontent.com/85636219/121555473-5558bb80-ca13-11eb-9ad7-f23339926045.png)
![Icon new](https://user-images.githubusercontent.com/85636219/121555373-3eb26480-ca13-11eb-89e2-074c1e0da9ae.png)
![Result new](https://user-images.githubusercontent.com/85636219/121555540-630e4100-ca13-11eb-83a6-a258653f5b4b.png)



https://user-images.githubusercontent.com/85636219/121430877-f6deff00-c978-11eb-944a-ec36bfbfc072.mp4


## Features

- Load BVH files
- Calculate global positions
- Removal of joints 
- Adding joints
- Adding frames
- Loss functions
- Optimizing offsets
- Changing rotation sequences
- Scaling
- Transfer movements to different hierarchies
- Save BVH files
