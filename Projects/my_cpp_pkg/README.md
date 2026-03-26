# ROS2 기반 캠핑 안전 감지 시스템

## 📌 개요
캠핑 환경에서 유해 가스를 감지하고 실시간으로 위험을 판단하는 시스템입니다.

## ⚙️ 구조
Sensor → Filter → Processing → Alert

## 🛠️ 기술
- ROS2 Humble
- C++
- Arduino
- Serial Communication

## 🚀 실행 방법
```bash
colcon build
source install/setup.bash
ros2 launch my_cpp_pkg my_cpp_launch.py
