# **Project overview** #

## **What is Libtune?** ##
Libtune is a Dynamic Binary Instrumentation tool that allows the user to optimize an already compiled application, without changing the source code. That is, the optimizations offered by this tool are related to load-time and link-time optimizations. Libtune is actually a Pin tool.

## **What is Pin?** ##
Pin is a dynamic binary instrumentation framework for the IA-32 and x86-64 instruction-set architectures that enables the creation of dynamic program analysis tools.
The tools created using Pin, called Pin tools, can be used to perform program analysis on user applications in Linux and Windows.
This project was focused on Windows platform implementation only. As a dynamic binary instrumentation tool, instrumentation is performed at run time on the compiled binary files. Thus, it requires no recompiling of source code and can support instrumenting programs that dynamically generate code.
Libtune was designed to optimize common memory and trigonometric library functions. A special test program was developed and added with the Libtune code which allows a fast analysis of the potential improvement.


---



## **Project Documentation** ##
[The Project`s Book](https://dl.dropboxusercontent.com/u/14958672/Project%20stripped.pdf) , contains:
  * Project overview
  * Client requirements
  * Work plan
  * Processes & main flow of the tool
  * User manual
  * Monthly reports
  * And the rest of project`s requirements


[The project`s final presentation](https://dl.dropboxusercontent.com/u/1999316/LibTune%20presentation.pdf)

[Libtune User Manual](https://dl.dropboxusercontent.com/u/14958672/User%20Manual.pdf)

[Libtune Test Results ](https://dl.dropboxusercontent.com/u/1999316/LibTune%20Test%20Results.pdf)

[Tests code Source](https://dl.dropboxusercontent.com/u/1999316/test_code.zip)