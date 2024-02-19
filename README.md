# Unmanned Pesticide Precision Spraying vehicle
![Untitled](https://github.com/CNU-wintercamo-squad/UPPS/assets/146147393/73bdc167-8666-42d1-b8c9-dbc512fc89e2)

## 시스템 구성
![UPPS_System composition](https://github.com/CNU-wintercamo-squad/UPPS/assets/146147393/22b3e237-7190-4c8c-aa3b-a78e683ea3ba)

+ UPPS: 주행, 제초제 분사. 주행 및 분사 위치 기록
+ UPPS Manager: 차량 조종, 잡초 인식.

## 👥 팀원 및 역할
|구 분|성 명|역할|
|---|---|---|
|팀장|임금재|3D 프린팅 & 모델링 및 GPS 모듈 코드 작성|
|팀원|김태헌|잡초 이미지 웹 크롤링. YOLOv5 모델 학습. OpenCV-Arduino-모델 연동|
|팀원|조연우|데이터 라벨링. 차량 동작 및 주행 코드 작성.|
|팀원|한명현|사업계획서 & 프레젠테이션 작성|

## 📅 개발 기간
2022. 8 ~ 2022. 8 (중 2주)

## 🛠️ 사용 기술
| | |
|---|---|
|🔠 프로그래밍 언어|<img src="https://img.shields.io/badge/C/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"> <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">|
|🎛️ HW 플랫폼|<img src="https://img.shields.io/badge/Arduino-00878F?style=for-the-badge&logo=arduino&logoColor=white">|
|🤖 AI|<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white"> <img src="https://img.shields.io/badge/Pytorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white">
|🖥️ OS|<img src="https://img.shields.io/badge/Windows-0078D4?style=for-the-badge&logo=windows&logoColor=white">|
|➕ ETC|<img src="https://img.shields.io/badge/Fusion 360-000000?style=for-the-badge&logo=autodesk&logoColor=white"> <img src="https://img.shields.io/badge/3D Printer-DC0032?style=for-the-badge&logo=dpd&logoColor=white">|

## 🎯 프로젝트 목적
### 무인 정밀 농약 분사 차량과 주행/살포 기록 시스템
+ 인구 감소로 인한 노동력 감소 및 정밀 농업 분야에 대한 솔루션.
+ 주행 경로와 제초제 살포 위치를 지도 데이터로 저장하여 농장 운영에 대한 방향성 제시.

## 🚜 UPPS (무인 정밀 농약 분사차량)
### 1) 사용 시나리오
![UPPS_Scenario](https://github.com/CNU-wintercamo-squad/UPPS/assets/146147393/51d768c3-1b96-463c-a803-71df7b4643ba)

### 2) 하드웨어 구성
![UPPS_HW](https://github.com/CNU-wintercamo-squad/UPPS/assets/146147393/2a3495be-2f42-4b76-bc7a-e79f7b65e3fc)

### 3) 기능 리스트
+ UPPS
  + UPPS Controller
    1. 제초제 분사
    2. 제초제 잔량 표시
    3. 주행
  + Log Recoder : 주행 및 분사 위치 기록

+ UPPS Manager
  1. 잡초 인식
  2. 차량 조종
  2. Local에 Log data 저장. 

## 🖥️ PC (UPPS Manager)
### 1) 구성도
![PC_Manager](https://github.com/CNU-wintercamo-squad/UPPS/assets/146147393/4f46cd78-c124-49da-bcd6-a99c3839666c)

## 📽️ 결과
![20220824_092744](https://github.com/CNU-wintercamo-squad/UPPS/assets/146147393/382e7f13-31c8-4513-b889-06800aa03f0e)

## 참고 자료
https://www.crummy.com/software/BeautifulSoup/bs4/doc/  
https://selenium-python.readthedocs.io/  
https://github.com/ultralytics/yolov5  
https://projecthub.arduino.cc/ansh2919/serial-communication-between-python-and-arduino-663756
