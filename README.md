[![Documentation](https://codedocs.xyz/HipsterSloth/PSVRTracker.svg)](https://codedocs.xyz/HipsterSloth/PSVRTracker/)

# PSVRTracker
A sample application that demonstrates optical position and orientation tracking of the PSVR headset as well as sensor fusion with the accelerometer and gyro.

![Tracking Sample](https://github.com/HipsterSloth/PSVRTracker/raw/master/misc/images/TrackingSample.gif)

# Prebuilt Releases
You can download prebuilt releases (Windows only at the moment) from the [Releases](https://github.com/HipsterSloth/PSVRTracker/releases) page. Then follow the initial setup instructions found in the [wiki](https://github.com/HipsterSloth/PSVRTracker/wiki#initial-setup). 

# Building from source
If you want to make modifications to the service or want to debug it, you can build the project from source by following the  [Building-from-source](https://github.com/cboulay/PSMoveService/wiki/Building-from-source) instructions. Currently supported build platforms are Win10 and OS X with Linux support hopefully coming in the near future.

# Documentation
* General setup guides, troubleshooting and design docs can be found on the [wiki](https://github.com/HipsterSloth/PSVRTracker/wiki)
* Documentation for the code is hosted on [codedocs](https://codedocs.xyz/HipsterSloth/PSVRTracker/)

# Near Term Goals
* Create a new Tracker class for the PS4 camera that mirrors the PS3EyeTracker class
* Create a KalmanFilter for the MorpheusHMD

# Usage in other projects
Feel free to use this code as-is, modified or adapted in other projects (commercial or otherwise). It's intended to be a reference algorithm that I hope other can make use of in any way they see fit.

# Attribution and Thanks
Special thanks to the following people who helped make this project possible:
* Chadwick Boulay - Owner of PSMoveService whose help and guidance made this project possible
* Antonio Jose Ramos Marquez - Work on PS4EyeDriver and PSX hardware reverse engineering
* Jules Bock - Got the PS4 camera driver working on Windows
* Agustín Gimenez Bernad - For his work on reverse engineering the PSVR sensor data
