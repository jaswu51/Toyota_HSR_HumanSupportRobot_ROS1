hsr_description
===============================================================================

# Toyota HSR

This repo combines the following two repos and gets a full 3D model of the HSR robot. 
* https://github.com/ToyotaResearchInstitute/hsr_description
* https://github.com/ToyotaResearchInstitute/hsr_meshes

Clone this repo, build and source it. 
```
catkin build -DPYTHON_EXECUTABLE=/usr/bin/python3
source devel/setup.bash
```


Debug
* Replace torso.std's suffix to torso.stl

### Visulization in Rviz (Ros1 noetic)
```
roslaunch hsr_description display.launch
```

![Screenshot from 2023-05-26 08-10-41](https://github.com/jaswu51/hsr_description/assets/91216581/5083af24-05ca-481b-b8aa-dd1c0e2d1f74)

### Visulization in Isaac Sim
* Issac Utils -> Work Flows -> URDF Importer
* Issac Utils -> Work Flows -> Articulation Inspector -> Play(Space) -> Selection Panel -> Position/Velocity/Efforts Controllers

![Screenshot from 2023-05-26 08-33-53](https://github.com/jaswu51/hsr_description/assets/91216581/53ab031e-dbb4-4900-9676-b4549f7f975a)
