## Face Anonymizer
Blur faces from image and video files in `/input/` folder.<br>

### Requirements
1. [yolov5-crowdhuman](https://github.com/deepakcrk/yolov5-crowdhuman)<br>
2. download `crowdhuman_yolov5m.pt` file in package folder.<br>
Download model trained on crowd human using yolov5(m) architeture.<br>
Download Link:  [YOLOv5m-crowd-human](https://drive.google.com/file/d/1gglIwqxaH2iTvy6lZlXuAcMpd_U0GCUb/view?usp=sharing)<br>

### Useage
`python run.py --weights crowdhuman_yolov5m.pt --source input/ --heads`

### Demo
Click image view Imgur demo<br>
[<img src="https://i.imgur.com/jP7URzA.png" width="512" height="512">](https://imgur.com/BEeOS5w)<br>
(note, demo is silent but videos in `/output/sound` contain audio)
