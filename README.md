==   INSTALLATION Instructions   ==
===================================

Binaries in this package will work for Windows (64-bit) only. To compile OpenCV 3.0 libraries in other systems, copy the contents of the modules/* directories to the OpenCV source location, replacing the existing files that have the same names.

 *  Clone this repository to some location, e.g. C:\Experiments\opencv-ecs.
 *  EITHER edit your Matlab `startup.m` to have it modify the system path, by adding lines as follows (with the appropriate modifications for where you have installed the repository):
`setenv('PATH', [getenv('PATH'), pathsep, 'C:\Experiments\opencv-ecs\x64\vc11\bin']);`

 *  OR add the subdirectory "C:\Experiments\opencv-ecs\x64\vc11\bin" of the above directory to your system path as follows:
     -  Windows 10 : Open Control Panel, then search for "environment variables". Click on the link "Edit environment variables for your account".
     -  Older versions of Windows : Open Control Panel -> System Properties, select the "Advanced" tab, then select "Environmental Variables".
     -  In the "User variables" list box, select the variable called "PATH" and click "Edit". If it does not already exist, create a new variable.
     -  Append C:\Experiments\opencv-ecs\x64\vc11\bin to the PATH variable, remembering to separate paths by a semicolon (;).
     -  For Windows 10, you can just enter a new line in the list instead of appending it.
