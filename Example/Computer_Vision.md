# Computer Vision

## Computer Vision이란?

**컴퓨터 비전**은 컴퓨터가 이미지나 영상을 통해 **사람처럼 사물을 인식하고 이해할 수 있도록 만드는 기술**입니다.

<div style="text-align: center;">

  ![영상](https://github.com/user-attachments/assets/be232b0a-cbc7-460b-9e84-96811f8e4229)
  <br>
  *(컴퓨터 비전을 통해 물체의 색상을 인지하는 모습)*

<br>
</div>

 예시:  
 - 자율주행차의 카메라를 통한 보행자 감지  
 - 카메라를 통한 얼굴 인식으로 스마트폰 잠금 해제  
 - 카메라를 통한 객체 인식

<br><br>

---

## 컴퓨터 비전의 주요 단계

1. **이미지 획득(Image Acquisition)**: 카메라나 센서를 통해 데이터를 수집  

2. **전처리(Preprocessing)**: 노이즈 제거, 해상도 조정, 색 보정  

3. **특징 추출(Feature Extraction)**: 엣지, 윤곽선, 색상 등 추출  

4. **해석 및 판단(Interpretation)**: 객체 인식, 분류, 추적 등

<br><br>

---

##  주요 기술 및 알고리즘

###  이미지 처리 (Image Processing)

- **필터링**: GaussianBlur, Sharpen, Canny Edge Detection
- **이미지 변환**: 이미지 회전, Resizing, 이진화

<br>

###  객체 인식 (Object Detection)

- **YOLO (You Only Look Once)**
- **SSD**, **Faster R-CNN**

<br>

###  얼굴 인식 (Face Recognition)

- 얼굴 감지, 특징 추출, 식별 과정으로 진행
- 사용 라이브러리: OpenCV, Dlib, FaceNet

<br>

###  딥러닝 기반 비전

- CNN(합성곱 신경망)을 기반으로 객체 분류 및 탐지
- Transfer Learning으로 효율적인 학습 가능
- 예시 모델: `ResNet`, `VGG16`, `YOLOv8`

<br><br>

---

##  대표 라이브러리 및 프레임워크

| 라이브러리 | 설명 |
|------------|------|
| OpenCV   | 이미지 처리, 영상 처리의 대표 라이브러리 |
| YOLO     | 객체 탐지에 최적화된 딥러닝 프레임워크 |
| TensorFlow / PyTorch | 딥러닝 모델 구축용 프레임워크 |

<br><br>

---

##  활용 분야

| 분야 | 적용 예시 |
|------|-----------|
|  자율주행 | 차선 인식, 보행자 감지, 도로 표지판 인식 |
|  공장 자동화 | 불량품 검사, 로봇팔 제어 |
|  보안 | CCTV 얼굴 탐지, 사람 추적 |
|  의료 | X-ray 분석, 종양 검출 |

<br><br>

---


##  미래산업에서의 이용

- **AI, 로봇, 헬스케어, 자율주행 등 모든 스마트 산업의 핵심 기술**
- 딥러닝 발전에 따라 정확도와 속도 크게 향상
- **3D 비전**, **AR/VR**, **멀티센서 융합** 등으로 확장 중

<br><br>

---

