# Readme
The current project comes from: https: //github.com/prabindh/darknet, here is only the CPU on the Windows compiler, upload the file contains compiled results.

# Build.
The current project is in the original author of the project on the appropriate revision of the compiler environment, easy to compile. At compile time, you need to install and unzip OpenCV3.1.0 to the following directory: D: \ Applicaton \ DevTools \ opencv \ 3.1.0 because the project will use the following header file: D: \ Applicaton \ DevTools \ opencv \ 3.1.0 \ opencv \ Build \ include,
After compiling, copy opencv_world310.dll under the D: \ Applicaton \ DevTools \ opencv \ 3.1.0 \ opencv \ build \ x64 \ vc14 \ bin to the directory of the project output (. \ Darknet \ bin \ win64 \ Release) And the main program can be put together. In addition to the completion of the compiler to run, you need to go to the official website (https://pjreddie.com/darknet/yolo/) download https://pjreddie.com/media/files/yolo.weights file in the compiled output directory Under data. And then directly in the folder to open the main test program arapaho.exe can.


	sindrol (email: china-psu@hotmail.com) 2017-07-22