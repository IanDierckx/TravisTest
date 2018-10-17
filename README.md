# session-2-travis-yml

There is a probability that by now you ran into problems with CMake and Travis. Travis runs CMake version 3.9.2 while your CMakeLists.txt file demands a higher version. That results in a build error. The easy solution is to edit the version number in your `CMakeLists.txt` file, but we want a better solution: edit the `.travis.yml` in this repo script so that an up-to-date version of CMake is installed on the VM on Travis. There are a lot of options to execute additional scripts and install dependencies in the `.travis.yml` configuration file. Use the [Travis CI documentation](https://docs.travis-ci.com/).

The most elegant solution will be used throughout the next practical sessions!
