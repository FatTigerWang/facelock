# Facelock
Face recognition control lock

[Demo Video](https://wangshenjie-standard.oss-cn-shanghai.aliyuncs.com/%E7%8E%A9%E8%BD%AC%E6%A0%91%E8%8E%93%E6%B4%BE.mp4)
### Power By
* [Face Recognition](https://github.com/ageitgey/face_recognition)
* [Python3.7](https://www.python.org)
* [opencv-python](https://pypi.org/project/opencv-python)
* [gpiozero](https://gpiozero.readthedocs.io/en/stable)
* [Raspbian](https://www.raspberrypi.org/documentation/raspbian)

### Hardware
* [Raspberry Pi 4B](https://www.raspberrypi.org/products/raspberry-pi-4-model-b)
* RTSP Protocol Camera
* Electromagnetic Relay
* Electromagnetic Lock

### Layout

![file](design.png)

### Run
```
python3 main.py source/ rtsp://IP
```

PS:
Due to the performance reasons of Raspberry Pi, you cannot process pictures in too large format, otherwise the frame reading delay will be caused due to I/O.

Camera parameters
```
Resolution: 640 * 352
FPS: 30
Bit Rate: 512 kbps
```
