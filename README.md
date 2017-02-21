
## Stereo Calibration Executable

<<<<<<< HEAD
this is the executable of stereo calibration for VisionerTech VMG-PROV 01. use this to get camera intrinsic and rectify map for see-through, marker-based AR and SLAM-based AR.
=======
This is the executable of stereo calibration for VisionerTech VMG-PROV 01. Use this to get camera intrinsic and rectify map for see-through, marker-based AR and SLAM-based AR. Source code of this executable could be found here.
>>>>>>> d25957d98ea57e4cd2c9489668cc94110a2e3e63

## Requirement:

1.  Recommended specs: Intel Core i5-4460/8G RAM/GTX 660/at least two USB3.0/
2.  Windows x64 version.(tested on win7/win10)

## Installation

1.  Install the Visual C++ Redistributable for Visual Studio 2012 Update 4  ["/exe/vcredist_x64.exe"](https://github.com/VisionerTech/stereo_calib_executable/blob/master/exe/vcredist_x64.exe).

2.  Plug camera cables(blue color-coding) in USB3.0 ports. Device manager would have cameras devices like,     ![alt text](https://github.com/VisionerTech/stereo_calib_executable/blob/master/readme_image/usbwebview4.png "usbwebview4").

    If it's recognized as a "USB web cam"

    ![alt text](https://github.com/VisionerTech/stereo_calib_executable/blob/master/readme_image/usbwebcam.png "usbwebcam")

    uninstall the driver

    ![alt text](https://github.com/VisionerTech/stereo_calib_executable/blob/master/readme_image/usbwebview2.png "usbwebview2")

    rescan for hardware

    ![alt text](https://github.com/VisionerTech/stereo_calib_executable/blob/master/readme_image/usbwebview3.png "usbwebview3")

    success!

    ![alt text](https://github.com/VisionerTech/stereo_calib_executable/blob/master/readme_image/usbwebview4.png "usbwebview4")

## How to Run
<<<<<<< HEAD
1.print out ["acircles_pattern.png"](https://github.com/VisionerTech/stereo_calib_executable/blob/master/acircles_pattern.png) and stick it to a rigid surface, make it a "calibration board".
2.  run ["/exe/stereo_calib.exe"](https://github.com/VisionerTech/stereo_calib_executable/blob/master/exe/stereo_calib.exe)， and you will see the image from left and right camera.
3.  place the "calibration board" in front of the camera, press "c" on the key board to capture an image pair(a blue flash appears with success capture). try to capture around 10 pair of the "calibration board" with different angle orientation and distance, try to cover the whole field of view of the cameras.  you can watch a video sample here. the captured image pairs is list in /save_image/ folder.
=======
1.  Print out ["acircles_pattern.png"](https://github.com/flankechen/stereo_calib_executable/blob/master/acircles_pattern.png) and stick it to a rigid surface, make it a "calibration board".
2.  Run ["/exe/stereo_calib.exe"](https://github.com/flankechen/stereo_calib_executable/blob/master/exe/stereo_calib.exe)， and you will see the image from left and right camera.
3.  Place the "calibration board" in front of the camera, press "c" on the key board to capture an image pair(a blue flash appears with success capture). Try to capture around 10 pair of the "calibration board" with different orientation and distance, try to cover the whole field of view of the cameras.  You can watch a video sample here. The captured image pairs is list in /save_image/ folder.
>>>>>>> d25957d98ea57e4cd2c9489668cc94110a2e3e63
![alt text](https://github.com/VisionerTech/stereo_calib_executable/blob/master/readme_image/calib_snap1.png "snap1")
![alt text](https://github.com/VisionerTech/stereo_calib_executable/blob/master/readme_image/calib_snap2.png "snap2")
4.  Press "Esc" on the keyboard. Program finds the pattern, perform stereo calibration and show the result. check the blue parallel lines to see left and right image is rectified.
![alt text](https://github.com/VisionerTech/stereo_calib_executable/blob/master/readme_image/rectified.png "rectified")
5.  Press "Esc" on the keyboard to save the result to /save_param/ folder. Copy the whole folder to where it's needed.
![alt text](https://github.com/VisionerTech/stereo_calib_executable/blob/master/readme_image/saved_files.png "saved_files")
