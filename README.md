# ROS101
ROS101 class - from basic to advanced 
강의명: ROS와 Carmaker 기반 자율주행의 인지,판단,제어 구현(이론, 실습, 프로젝트 10일)​
강의일시: 2월 10일(4일차), 09:00-13:00, 14:00-18:00
강의장소: 충북대학교
수강대상: 학부생 및 대학원생, 재직자 (자율주행관련) 
강의주제: ROS 활용 및 예제

## Pre-requirement
- Ubuntu 16.04
- ROS kinetic

### Install Clang
``` Bash
sudo apt-get install clang, clang-format
```

### Build
``` Bash
catkin build
```
with alias
``` Bash
cb
```

## hello_world_ros_pkg
- hello world 를 terminal 또는 ros log file 에서 확인하도록 하는 pkg
- ros pkg 의 기본구조 학습

## pub_test
- ros 의 publisher 예제
- string data 와 float32 multi-array data 를 publish 하는 pkg

## sub_test
- ros 의 subscriber 예제
- string data 와 float32 multi-array data 를 subscribe 하는 pkg