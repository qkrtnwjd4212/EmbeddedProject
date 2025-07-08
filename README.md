# 자동 소방 RC카 및 스마트 도로 통제 시스템
### 임베디드시스템프로그래밍2 프로젝트

[최종 발표 PPT 자료](https://drive.google.com/file/d/1Nef0HpQZqnrCfS2U3rZBhsGhqkoYTaEl/view?usp=drive_link)
<br />



## 🚨 배경 및 문제 정의

- 2025년 3월, 경북 의성 및 산청 등지에서 발생한 대형 산불은 역대 최악의 피해를 기록함
- 소방 인력의 약 95% 이상이 비전문가로 구성되어 초기 대응이 지연됨
- 소방 헬기 등의 장비가 노후화되어 많은 인명 피해가 증가함
<br />


## 🎯 프로젝트 목표 및 주요 기능 
**1. 자동 소방 RC카를 활용한 신속/자동화된 초기 대응**  
   - 각 방향별로 불꽃 감지 센서를 연결하여 불꽃을 빠르게 탐지하고, 장애물이 있거나 사람이 접근하기 어려운 지역에서도 RC카 자율주행을 통해 즉시 이동함 
   - 연결된 워터 펌프를 통해 불꽃이 완전히 소화될 때까지 화재 발생 장소에 물 분사

**2. 스마트 도로 통제 시스템**  
   - Edge Impulse 플랫폼에서 TinyML 모델을 빌드하여, ESP32의 카메라 모듈에 RC카가 인식되면 차량 차단바를 자동으로 해제함

<p float="left">
  <img width=300 src="https://github.com/user-attachments/assets/caf51b4f-8cbd-45f6-9953-fa6f6da19028">
  <img width=380 src="https://github.com/user-attachments/assets/548450d6-7a48-4081-8059-b7092f6a4cb7">
</p>
<br />


##  🦾 사용 부품
- 라즈베리파이
- ESP32
- 불꽃 감지 센서 * 3
- RC카 4륜 자동차키트
- 워터 펌프 모터
- DC 모터 * 4
- 3.7V 리튬 배터리, AA 배터리 * 4
- 모터드라이버 (RC카 - L298N 사용, 워터펌프 - L9110 사용)
- 라즈베리파이용 배터리 공급 쉴드
- 서보모터 * 2
<br />


## 🤖 회로도 
<p float="left">
  <img width=650 src="https://github.com/user-attachments/assets/3cc9cd93-4fa4-4911-837a-840ad5a49177">
  <img width=350 src="https://github.com/user-attachments/assets/f622ce78-98e8-4b65-9422-abccbeeaafad">
</p>


## 🪢 흐름도
![image](https://github.com/user-attachments/assets/78c252bc-0186-4b68-af34-c45e51299726)
<br/>


## 📹 시연 영상

### RC카 자동 소방 기능

https://github.com/user-attachments/assets/e7286674-6ad6-4301-95e6-5423cc52616f

<br/>


### 스마트 도로 통제 시스템

https://github.com/user-attachments/assets/f14c4332-eaa8-4c19-995e-14d081b9f1a2

<br />


