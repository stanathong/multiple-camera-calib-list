# A list of tools for multi-camera calibration

## CamOdoCal
<br>
The package comes with both intrinsic and extrinsic calibration for multi-camera system. The advantage of this technique is that it does not require overlapping fields of view between cameras and thus this is applicable for the rear camera. A plus advantage is that this work has also been tested on a van mounted with a four-camera rigs on the roof, which is similar to our system. In order to determine the scale metric between cameras, it requires odometry data which can be from the wheel or GPS/IMU system. The package is developed in C++ on Ubuntu platform.<br>

__Tool:__ [Github](https://github.com/hengli/camodocal)<br>
__Platform:__ C++ executable on Ubuntu<br>
__Referrence:__ Bo, L., Heng, L., Koser, K., Pollefeys, M., 2013. A multiple-camera system calibration toolbox using a feature descriptor-based calibration pattern.<br>


## BACS - Bundle Adjustment for Camera System
<br>
This package implements a bundle adjustment algorithm for ominidirectional and multi-view cameras, which can be applied to obtain the pose of the cameras in the rig.<br>

__Tool:__ [Project Page and code](http://www.ipb.uni-bonn.de/data-software/bacs/)<br>
__Platform:__ MATLAB<br>
__Referrence:__ Schneider, J., Schindler, F., Labe, T., Forstner, W., 2012. Bundle adjustment for multi-camera system with points at infinity.<br>


## AMCC Toolbox - Automatic Multi-Camera Calibration
<br>
This toolbox uses a chessboard as a calibration object. This technique requires a high degree of overlap between cameras. The toolbox offers both intrinsics and extrinsics calibration. Another advantage point of this tool is that it offers parallel processing so speed up the computation.<br>

__Tool:__ [Project Page](https://bitbucket.org/michaeldwarren/amcctoolbox/wiki/Home)<br>
__Platform:__ MATLAB<br>
__Code:__ `git clone https://bitbucket.org/michaeldwarren/amcctoolbox.git`<br>
__Referrence:__ Warren, M., McKinnon, D., Upcroft, B., 2013. Online calibration of stereo rigs for long-term autonomy. <br>

