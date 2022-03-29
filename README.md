# OpenCL_1
This challenge focuses on developing an OpenCL kernel, using C++, that you can load, activate and send data back and forth to, from a C / C++ host application.
## The Programming Model
OpenCL uses a programming and memory model similar to OpenGL. The CPU must copy data to the GPU and then tell a kernel (OpenCL worker) to process the data. When the kernel is finished, the CPU can read back the result.
