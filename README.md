# object_detection_torch_vision
object detection using pytorch vision

## Input Data
Input data: image + csv </br>
csv must be following format

|filename   |width  |height |class  |xmin   |ymin   |xmax   |ymax   |
|-----------|-------|-------|-------|-------|-------|-------|-------|
|abc1.JPG   |1200   |800    |A      |340    |748    |382    |780    |
|example.JPG|1200   |800    |B      |140    |248    |182    |780    |
|abc2.JPG   |1200   |800    |A      |240    |648    |282    |780    |

## Requirement
* torch==1.13.1
* torchvision==0.14.1
* numpy==1.22.4
* pandas==1.1.4
* opencv-python==4.6.0.66
* albumentations==1.3.0
* matplotlib==3.6.2
