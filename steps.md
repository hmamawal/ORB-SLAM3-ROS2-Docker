comment out vscode lines

in docker
sudo apt install xauth x11-apps

https://medium.com/@potatowagon/how-to-use-gui-apps-in-linux-docker-container-from-windows-host-485d3e1c64a3


sudo apt-get install net-tools
export DISPLAY=172.19.192.1:0.0
xeyes
root@docker-desktop:/opt/ros/humble# source setup.bash

but got new error haven't solved yet: 
```
CMake Error at CMakeLists.txt:36 (find_package):
  By not providing "FindSophus.cmake" in CMAKE_MODULE_PATH this project has
  asked CMake to find a package configuration file provided by "Sophus", but
  CMake did not find one.

  Could not find a package configuration file provided by "Sophus" with any
  of the following names:

    SophusConfig.cmake
    sophus-config.cmake

  Add the installation prefix of "Sophus" to CMAKE_PREFIX_PATH or set
  "Sophus_DIR" to a directory containing one of the above files.  If "Sophus"
  provides a separate development package or SDK, be sure it has been
  installed.
```
