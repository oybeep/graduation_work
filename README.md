# Raspberry Pi 기반 시각장애인 보행 보조 시스템

Raspberry Pi와 YOLOv8을 활용한 시각장애인 보행 보조 시스템이다.
카메라를 통해 주변 객체를 인식하고, 음성 안내와 거리 센서를 통해 보행을 지원한다.

## 주요 기능

* YOLOv8 기반 객체 탐지
* CVAT를 이용한 데이터 라벨링 및 데이터셋 구축
* Raspberry Pi 기반 실시간 영상 처리
* PC ↔ Raspberry Pi 간 영상 및 탐지 결과 통신
* 객체 탐지 결과 음성 안내
* ToF 센서를 이용한 근거리 장애물 감지

## 사용 기술

* Python
* YOLOv8
* OpenCV
* Raspberry Pi 4B
* CVAT
* Google Colab
* Linux

## Model

* Model: YOLOv8n
* Input Size: 320 × 320
* Confidence Threshold: 0.7
* Dataset Split: 8 : 1 : 1
* mAP@50: 94.6%

## My Contribution

* 객체 탐지 데이터 수집 및 CVAT 라벨링
* 데이터 전처리 및 증강
* YOLOv8 모델 학습 및 성능 평가
* Raspberry Pi 환경 구축 및 배포
* PC ↔ Raspberry Pi 통신 구현
* 음성 안내 및 장애물 감지 기능 구현

## Hardware

* Raspberry Pi 4B
* USB Webcam
* ToF Sensor
* Speaker
* Vibration Motor
* PAM8403 Amplifier
* Power Bank
