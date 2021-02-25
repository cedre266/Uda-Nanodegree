# Uda-Nanodegree

## Project: Build My World

Construction of a basic world in Gazebo.

Inside the project folder:
    mkdir build
    cd build/
    cmake ../
    make

A plug-in allows to automatically display a welcoming message once opening the world. In order to allow its execution, set the environment variable as follows:
    export GAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}:/full/path/to/project/build

The world can then be opened:
    cd /full/path/to/project/world
    gazebo my_world
