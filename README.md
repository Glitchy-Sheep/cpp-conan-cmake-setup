## About

<img src="https://github.com/Glitchy-Sheep/cpp_conan_cmake_setup/raw/assets/logos.png" title="" alt="" data-align="center">

This is a simple setup for a **C++** project with **conan** as a package manager and **cmake** as a build automation system. I use it pretty often, so I made a repo for it to automate cmake/conan/project configuration.

You can simply copy all these files to some directory, add a few libraries requirements to the `conanfile.txt` and run the configure scripts. **Be aware** that configure scripts has `--build missing` option which means your system will build all the libraries which are not available in prebuild form for your tool chain.
