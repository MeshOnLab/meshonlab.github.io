---
title: "HRM/SPO2/Temperature reference board(BLE)"
classes: wide
excerpt: "HRM SPO2 Temperatue 측정 BLE 전송 무선 충전 디바이스"
header:
  teaser: /assets/images/projects/HRM_SPO2_reference/board_smartring_proto_tn.png
gallery:
  - url: assets/images/projects/HRM_SPO2_reference/board_smartring_proto.jpg
    image_path: /assets/images/projects/HRM_SPO2_reference/board_smartring_proto_tn.png
    alt: "placeholder image 1"
  - url: assets/images/projects/HRM_SPO2_reference/sensor_data_on_pc.jpg
    image_path: assets/images/projects/HRM_SPO2_reference/sensor_data_on_pc_tn.png
    alt: "sesnor waveform on pc"
  - url: assets/images/projects/HRM_SPO2_reference/board_debug_connect.png
    image_path: assets/images/projects/HRM_SPO2_reference/board_debug_connect_tn.png
    alt: "board debugger connection"
---

SiliconLabs BLE SoC 기반에 HRM/SPO2 센서, 온도 센서, 무선 충전 기능을 추가하여 Hardware 를 설계하고 BLE 통신으로 스마트폰 앱에 센서 데이타를 전달한다.

{% include gallery caption="테스트 보드 및 PC를 통한 파형 출력" %}

제조사 제공 Device Test 보드용 프로그램과 통신하도록 테스트 펌웨어 개발 
프로토보드에서 센서 동작 제어 및 BLE 를 통한 데이터 전송
