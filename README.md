# PandaForReuleaux

Repo containing the packages for the simulation of the Panda robot used for the work on the repo Reuleaux_new (https://github.com/LucreziaPonti/Reuleaux_new)

### Installation
As of now cloning this repo is equivalent to cloning the original one:
```
git clone https://github.com/moveit/panda_moveit_config.git -b noetic-devel
```
In both cases to simulate the robot, before building this package you need to do the following installation:
```
cd ~/ws_moveit/src
rosdep install -y --from-paths . --ignore-src --rosdistro noetic
```
which should install the package *ros-noetic-franka-description* (or you can also install it manually by using "*sudo apt install"*)

