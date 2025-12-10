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


### Hardware:
Raspberry 3, Raspberry 4B, Raspberry zero are support. <br>

### Usage:

#### 1. download image
https://github.com/iottq/livecam-arm/releases/download/v1.0.0/2025-12-10-raspios-bookworm-arm64-lite.img.xz

#### 2. flash image with Raspberry Pi Imager

#### 3. download LiveCam Pi app