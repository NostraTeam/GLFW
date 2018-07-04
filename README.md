# Nostra GLFW

Standard GLFW with improved/adjusted CMake support

This library is part of a project made by students of the htw saar (https://www.htwsaar.de/) and supervised 
by Dipl-Inf (FH) Christopher Olbertz.

GitHub: https://github.com/NostraTeam/GLFW

If you do not have the code yet, use the following command to clone the repository to your local
machine:  
```bash
git clone https://github.com/NostraTeam/GLFW.git
```` 
or download the ZIP-compressed directly from GitHub using the link above.

**This code uses a modified version of GLFW (http://www.glfw.org/).** The used code is mostly unmodified 
GLFW, but parts of the CMake files have been adjusted to fit the Nostra build process. Also, files that are
not required to build GLFW, for example the tests, have not been imported into this repository. **The 
NostraTeam is not the author of GLFW.**

The currently used GLFW version is 3.2.1.

## Changes from Standard-GLFW

The GLFW C source code itself has remained completely unchanged, but the CMake build process has been 
adjusted.