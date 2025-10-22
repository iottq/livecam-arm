# livecam-arm


## 🧠 项目简介
本项目基于ARM嵌入式平台，支持树莓派等开发板，通过WEBRTC可以通过手机远程访问摄像头 



### Usage:
run on raspberry pi <br>

#### download binary
```
wget https://github.com/iottq/livecam-arm/releases/download/v1.0.0/livecam-arm
```
#### start program with command

```
./livecam-arm --camera=libcamera:0 --uid=064b75d9-c5b6-4e6a-9f1d-e6068aad6507
or 
./livecam-arm --camera=v4l2:0 --uid=064b75d9-c5b6-4e6a-9f1d-e6068aad6507
```