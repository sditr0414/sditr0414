# 정승호 · Seungho Jung

### 로봇 제어 · 비전 · 임베디드

펌웨어부터 로봇팔 제어, 비전 모델 실행까지 직접 만들고 확인합니다.

### [포트폴리오 사이트 ↗](https://sditr0414.github.io/)

---

## 기술

### 제어·임베디드

<p>
<img src="https://img.shields.io/badge/C-2d4a6b?style=for-the-badge&logo=c&logoColor=white" alt="C" height="32"/>
<img src="https://img.shields.io/badge/C%2B%2B-2d4a6b?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" height="32"/>
<img src="https://img.shields.io/badge/STM32-2d4a6b?style=for-the-badge&logo=stmicroelectronics&logoColor=white" alt="STM32" height="32"/>
<img src="https://img.shields.io/badge/FreeRTOS-2d4a6b?style=for-the-badge" alt="FreeRTOS" height="32"/>
<img src="https://img.shields.io/badge/PLC-2d4a6b?style=for-the-badge" alt="PLC" height="32"/>
</p>

### 로봇·비전

<p>
<img src="https://img.shields.io/badge/Python-1f6f6b?style=for-the-badge&logo=python&logoColor=white" alt="Python" height="32"/>
<img src="https://img.shields.io/badge/ROS2-1f6f6b?style=for-the-badge&logo=ros&logoColor=white" alt="ROS2" height="32"/>
<img src="https://img.shields.io/badge/OpenCV-1f6f6b?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV" height="32"/>
<img src="https://img.shields.io/badge/YOLO-1f6f6b?style=for-the-badge" alt="YOLO" height="32"/>
<img src="https://img.shields.io/badge/TFLite-1f6f6b?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TFLite" height="32"/>
</p>

### 설계·개발 도구

<p>
<img src="https://img.shields.io/badge/SolidWorks-5b6472?style=for-the-badge" alt="SolidWorks" height="32"/>
<img src="https://img.shields.io/badge/MATLAB-5b6472?style=for-the-badge" alt="MATLAB" height="32"/>
<img src="https://img.shields.io/badge/MuJoCo-5b6472?style=for-the-badge" alt="MuJoCo" height="32"/>
<img src="https://img.shields.io/badge/Isaac%20Sim-5b6472?style=for-the-badge&logo=nvidia&logoColor=white" alt="Isaac Sim" height="32"/>
</p>

---

## 프로젝트

<table>
<tr>
<td width="50%" valign="top">
<a href="https://sditr0414.github.io/#opencv"><img src="assets/opencv.jpg" alt="비전 기반 로봇팔 조립·검사" width="100%"/></a>
<h3>비전 기반 로봇팔 조립·검사</h3>
<p>지그 위치를 다시 측정해 동작을 보정하고,<br/>부품 종류와 안착 상태를 검사</p>
<p><code>Python · ROS2 · OpenCV · YOLO</code></p>
<p><a href="https://sditr0414.github.io/#opencv">상세 보기</a> &nbsp;·&nbsp; <a href="https://github.com/7s-FA/opencv-teach">코드</a></p>
</td>
<td width="50%" valign="top">
<a href="https://sditr0414.github.io/#robot"><img src="assets/robot.jpg" alt="원격 물품 회수·운반 로봇" width="100%"/></a>
<h3>원격 물품 회수·운반 로봇</h3>
<p>스마트폰으로 주행과 로봇팔을 조작하고,<br/>저장한 동작을 재생하는 4륜 로봇</p>
<p><code>C · STM32F411 · FreeRTOS</code></p>
<p><a href="https://sditr0414.github.io/#robot">상세 보기</a> &nbsp;·&nbsp; <a href="https://github.com/sditr0414/mobile-retrieval-robot">코드</a></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://sditr0414.github.io/#vision"><img src="assets/vision.jpg" alt="AI 기반 보행 보조 장치" width="100%"/></a>
<h3>AI 기반 보행 보조 장치</h3>
<p>객체 검출과 지면 분할로<br/>보행 경로의 위험을 음성으로 안내</p>
<p><code>Python · YOLO · TFLite · Raspberry Pi5</code></p>
<p><a href="https://sditr0414.github.io/#vision">상세 보기</a> &nbsp;·&nbsp; <a href="https://github.com/sditr0414/GreenLight">코드</a></p>
</td>
<td width="50%" valign="top">
<a href="https://sditr0414.github.io/#plc"><img src="assets/plc.jpg" alt="PLC 기반 창고 적재 제어" width="100%"/></a>
<h3>PLC 기반 창고 적재 제어</h3>
<p>금속·비금속 소재를 판별해<br/>1~4층 창고에 병렬로 적재</p>
<p><code>Mitsubishi Q PLC · GX Works2</code></p>
<p><a href="https://sditr0414.github.io/#plc">상세 보기</a></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://sditr0414.github.io/#thesis"><img src="assets/knock.jpg" alt="노크 위치 탐지 연구" width="100%"/></a>
<h3>노크 위치 탐지 연구</h3>
<p>피에조 센서 8개의 진동 신호로<br/>두드린 위치를 9개 구역으로 분류</p>
<p><code>MATLAB · K-NN · SVM · ANN</code></p>
<p><a href="https://sditr0414.github.io/#thesis">상세 보기</a></p>
</td>
<td width="50%" valign="top">
<a href="https://sditr0414.github.io/#travel"><img src="assets/travel.jpg" alt="Travel Visualizer" width="100%"/></a>
<h3>Travel Visualizer</h3>
<p>여행 사진과 이동 기록을<br/>지도 위 경로로 잇는 웹앱</p>
<p><code>React · TypeScript · MapLibre</code></p>
<p><a href="https://sditr0414.github.io/#travel">상세 보기</a> &nbsp;·&nbsp; <a href="https://github.com/sditr0414/Travel-Visualizer">코드</a></p>
</td>
</tr>
</table>

---

## 학력·교육

- **대한상공회의소 서울기술교육센터** · AI융합 로봇 SW개발자 3기 수료 (2026.04 – 2026.11)
- **순천향대학교 기계공학과** 졸업 (2019.03 – 2026.02)
