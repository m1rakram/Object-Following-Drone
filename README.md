# Object-Following-Drone
Project intends to make drone to follow predefined objects autonomously. Task was assigned as final exam project of Mechatronics class.
We used F450 drone kit with full specifications. Arducopter is used as main controller. Raspberry is used for image processing in python. We used color detection for our task and camera is located under dron. Raspberry PI processes image frames to detect the object. We pass dimensions of this object to arduino which uses data in Pİ control and give decisions. Commands to drone are given through serial communcication
