=============================
  INSTALLATION Instructions
=============================

Binaries in this package will work for Windows (64-bit) only. To compile OpenCV 3.0 libraries in other systems, copy the contents of the modules/* directories to the OpenCV source location, replacing the existing files that have the same names.

 *  Clone this repository to some location, e.g. C:\Experiments\opencv-ecs.
 *  Add the subdirectory "x64\vc11\bin" of the above directory to your system path:
     -  Open Control Panel -> System Properties.
     -  Select the "Advanced" tab.
     -  Select "Environmental Variables".
     -  In the "User variables" list box, select the variable called "PATH" and click "Edit". If it does not already exist, create a new variable.
     -  Append C:\Experiments\opencv-ecs\x64\vc11\bin to the PATH variable, remembering to separate paths by a semicolon (;).