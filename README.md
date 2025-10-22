# livecam-arm


## 🧠 项目简介
本项目基于 WebRTC 实现手机与树莓派之间的实时视频传输。
树莓派通过摄像头采集视频流，并利用 WebRTC 协议进行编码与推流；
手机端可通过原生 App 实时查看视频画面，支持低延迟、点对点传输。
该系统适用于远程监控、机器人视觉、无人机视频传输等场景。

This project enables real-time video streaming from a Raspberry Pi camera to a mobile device using WebRTC.
The Raspberry Pi captures video through its camera and streams it using the WebRTC protocol.
A mobile device can view the live video either via a native app, achieving low-latency, peer-to-peer communication.
It’s ideal for remote monitoring, robotics vision, and UAV (drone) video transmission applications.


### Usage:
run on raspberry pi <br>

#### download binary
```
wget https://github.com/iottq/livecam-arm/releases/download/v1.0.0/livecam-arm
```

#### install package
```
sudo apt install cmake clang clang-format mosquitto-dev libpulse-dev libasound2-dev libjpeg-dev libcamera-dev libmosquitto-dev protobuf-compiler libprotobuf-dev
```


#### start program with command

```
./livecam-arm --camera=libcamera:0 --uid=064b75d9-c5b6-4e6a-9f1d-e6068aad6507
or 
./livecam-arm --camera=v4l2:0 --uid=064b75d9-c5b6-4e6a-9f1d-e6068aad6507
```