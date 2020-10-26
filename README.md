# DarkCamCalibrator

### Camera Calibration Tool
This is a utility program that helps calibrating normal and fisheye cameras. Anyone can use it for non-commercial purposes.

### Download Executable
* [DarkCamCalibrator1.1.zip](https://github.com/darkpgmr/DarkCamCalibrator/releases/download/darkcamcalibrator1.1-release/DarkCamCalibrator1.1.zip)
(currently, only binary executable can be downloaded)

![My image](https://github.com/darkpgmr/DarkCamCalibrator/blob/master/image/DarkCamCalibrator_gui.png)

### Supported Camera Models
* Z. Zhang's model (opencv default model)
  * Z. Zhang. “A Flexible New Technique for Camera Calibration”, IEEE Trans. Pattern Analysis and Machine Intelligence, 22(11):1330-1334, 2000
  * Distortion parameters (k1, k2, p1, p2, ...) are estimated on normalized image plane
* FOV model (coupled)
  * F. Devernay and O. D. Faugeras. Straight lines have to be straight. Machine Vision and Applications, 13(1):14?24, 2001.
  * Distortion parameter (w) is estimated on normalized image plane.
* FOV model (decoupled)
  * F. Devernay and O. D. Faugeras. Straight lines have to be straight. Machine Vision and Applications, 13(1):14?24, 2001.
  * Distortion parameter (w) is estimated on original pixel image plane.
