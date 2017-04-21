# template-cpp
a cpp project template for Visual Studio and CMake

## how to use
* clone
```
git clone https://github.com/cfwen/template-cpp.git new-project-name
```
* run init
```
python init.py new-project-name
```
* if later you want to rename project
```
python init.py old-project-name new-project-name
```

## build
* Visual Studio project is ready, just open *.sln
* for cmake
```
mkdir build
cd build
cmake ..
```