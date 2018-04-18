# How to use these files
C++ source files flick.h and flick.cpp defines API class that provides programming interface for Flick 3D gesture boards.

Include flick.h and flick.cpp to your c++ project.

Depends on mraa library.

Build example program on Linux:
```bash
g++ flick_example.cpp flick.cpp -o flick_example -lmraa

```

Run example:
```bash
sudo ./flick_example
```

ths c++ language source library for flick boards. It is intended for advanced users familiar with c++ programming., and can be used on different platforms, like rpi, arduino or with small adaptation on other mcu platforms. It is not ready software to do something but software layer above flick hardware or shell, so user can easily interface flick functionality. It is based on 4 callback functions and polling from user software. There is example code flick_example.cpp you can look at how it can be used. There is Readme.txt describing how to build example.

Based on: https://github.com/PiSupply/Flick/tree/master/firmware/libcpp
