---
layout: post
title: C++ Libraries and tools
---
### Libraries and tools I use

#### Selected Libraries

After some years of developing c++ applications, here are some libraries I recommend for beginners to investigate.

* <strong>Standart Template Library (STL)</strong>: Of course, it's a must for modern programming. The container classes and algorithms are enough for small projects (you can explore more [here](https://en.cppreference.com/w/)).
* <strong>GUI Libraries</strong>: there are a lot of c++ Gui Libraries out there, but my preference is  [FLTK](https://www.fltk.org/). It is very easy to understand, has some nice widgets, is multiplatform and supports multithreading. If you need more advanced interfaces consider use to QT or WxWidgets.
* <strong>Json Libraries</strong> (for messages content): my preference is [cJSON](https://github.com/DaveGamble/cJSON). Although it's a c library, I've used it without any problems in some projects.  
* <strong>Testing</strong>:  I choose [Google Test](https://github.com/google/googletest) for my projects.
* <strong>Web</strong>: I use [Crow](https://github.com/CrowCpp/Crow/tree/master) for REST API and [Paho MQTT CPP](https://github.com/eclipse/paho.mqtt.cpp) for messaging using websockets and Mqtt.

#### Tools

* <strong>IDE</strong>: when developing in Ubuntu, I choose Vscode(it is just nice). When using Windows, I use the more traditional [Code::Blocks](https://www.codeblocks.org/), with ["CygWin"](https://www.cygwin.com/).
* <strong>Compiler</strong>: Currently I use [GCC](https://gcc.gnu.org/).
* <strong>Compilation tool</strong>: [CMake](https://cmake.org/). It is a little hard to learn, but after some work, it is very nice. It lets you generate packages and organize your code.
* <strong>Packaging</strong>: In Windows, I use CPack, and sometimes [InnoSetup](https://jrsoftware.org/isinfo.php). For Linux CPack.
* <strong>Documentation</strong>: [Doxygen](https://www.doxygen.nl/).
* <strong>Dynamic Analysis</strong>: [Valgrind](https://valgrind.org/), it lets you check memory leaks and others issues. I recommend to use it with massif, and the tool [Massif-visualizer](https://github.com/KDE/massif-visualizer).
* <strong>Software Versioning</strong>: [Git](https://git-scm.com/).
* <strong>Package Manager</strong>: in some projects I've used [Conan](https://conan.io/) and in other just fetching the libraries with CMake.

#### Books I have read about c++

* Marius Bancila,["Modern c++ Progamming Cookbook"](https://www.amazon.com/-/es/Marius-Bancila/dp/1800208987): I have the second edition, it has a lot of examples and tips that help to use c++ in an effective manner.
* Bjarne Stroustrup, ["A tour of C++"](https://www.stroustrup.com/Tour.html): Currently reading it. Very compact, right to the point book.
* Bjarne Stroustrup, ["Programming, Principles and practices using c++"](https://www.stroustrup.com/programming.html): It's a general programming book. Coming from the embedded field, it shows me a lot of good practices.
* Eric Gamma et al,["Patrones de diseño"](https://www.amazon.com/-/es/Erich-Gamma/dp/8478290591): Spanish version of the classic book "Design patterns".

The objective of this post is to give the reader the framework that I use so that you can follow the upcoming ones.
