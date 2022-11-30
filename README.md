# How to add the message to your package
- copy the folder tdf_messages to the src folder in your catkin workspace
- cd to your catkin workspace
```
catkin_make 
source devel/setup.bash
```
- test the functionality with:
```
rosmsg show tdf_messages/DigitalTwin
```
- to include the tdf_messages to your package, open the CMakeLists.txt in your package folder 
and add tdf_messages to find_packages()
