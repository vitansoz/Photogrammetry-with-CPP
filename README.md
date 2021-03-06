# Photogrammetry-with-CPP
Photogrammetry using C++

For a long time I have been wanting to write a technical book.  After doing some 
technical reviewing, I think I have enough appreciation and knowledge to start
this effort.  In particular, I have a strong passion for cartography and 
photogrammetry.  I want to write a book which shares my passion for photogrammetry
using common C++ libraries.  My goal is to enable intermediate to advanced
C++ developers the ability to write applications which take advantage of
all the power that modern cartography enables. 


Please contact me with any questions, comments, or advice.  I am not the worlds
greatest writer, so please feel free to help me along.  If there is any specific
information you would like to see, please let me know. 

## Project Organization

The base directory is divided into sections. 

1.  book : Contains all book-related material, including the build scripts, source, images, and other artifacts.

2.  cmake : Contains all required CMake materials include CMake scripts and modules.

3.  code : Contains all sample code used in the book.

## Project Dependencies

### Documentation

- texlive or other LaTeX Compiler
- CMake

### Software

- GDAL   : Geospatial Data Abstraction Library
- OpenCV : C++ Image Processing and Computer Vision Library
- OpenSceneGraph - Open Scene Graph 3D Library

### Mac OSX with MacPorts

- texlive-latex-extra
- cmake

### Fedora Packages Required Using DNF/Yum

- opencv-devel
- gdal-devel
- GeographicLib-devel
- OpenSceneGraph-devel
- ImageMagick
- texlive-scheme-full (Pretty hefty, so scale down if needed).
- cmake


## Building the Document

Build the CMake Project

    mkdir release
    
    cd release

    cmake ..
    
    make
    
