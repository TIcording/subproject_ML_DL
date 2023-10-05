# subproject_ML_DL


# 1. DL_Personal Color
## 다양한 모델을 활용한 Classification 프로젝트로 사람의 얼굴에 가장 어울리는 색상을 찾는 퍼스널 컬러 프로젝트

## 아이디어
OpenCV, MidiaPipe를 이용하여 얼굴영역의 피부색을 추출후 그 값들을 조합하여 학습한다.
![image](https://github.com/TIcording/subproject_ML_DL/assets/131944225/71044652-53d3-4bad-800d-99ec5be16ea8)


# 2. 데이터분석 - 한류
## 한류가 외국인 방문객수에 미치는 영향을 분석해 보는 데이터 분석 프로젝트

## 기획 주제
한류는 한국의 엔터테이먼트 산업의 성공적 글로벌 확장과 함께 국제적 인기를 끌고있다. 이러한 상황에서 한류는 외국인 방문객 수에 영향을 미치지 않을까라는 의문에서 시작하였다. 과연 얼마나 영향이 있는지 예측해보는 모델을 만들어 보았음.

## 메인데이터
한국 관광 데이터랩: 관광객 데이터(목적별, 연령별)

![image](https://github.com/TIcording/subproject_ML_DL/assets/131944225/2a53037b-b403-48cb-a3f3-dc93168dd5a7)

한류지수(한류심리지수, 한류현황지수), 환율, 유가 ,행복지수, 직선거리 등을 추가적인 데이터로 사용

![image](https://github.com/TIcording/subproject_ML_DL/assets/131944225/67ae25af-32ed-422e-833b-9a26474218a2)

## 결과
Linear, LGBM, Random Forest 모델들을 사용하여 분석을 진행하였으며 각각의 feature 중요도를 보면 다음과 같다.


![image](https://github.com/TIcording/subproject_ML_DL/assets/131944225/db4628cb-acb5-4485-a9ad-8a7dbcfb2b07)

독립변수들의 수와 종류를 바꾸며 다양한 테스트한결과 한류지수는 꾸준한 영향을 주고있음을 확인함.


# 3. OCR Model

## 주제
현재 사용되고있는 다양한 OCR 모듈들에 대해 알아보고 그에 따른 장단점을 구분해보고자 한다.

### 1. EasyOCR 
#### 간단한 구조와 다양한 언어에 대한 지원으로 편하게 사용할 수 있지만 다른 모듈에 비해 속도가 다소 느린 단점이 있다.

![image](https://github.com/TIcording/subproject_ML_DL/assets/131944225/789b6309-d61c-41ac-9ff0-d003bada677b)


![image](https://github.com/TIcording/subproject_ML_DL/assets/131944225/153472ed-9d14-4290-8198-f3d1f1bc2fe3)


### 2. Google Cloud Vision
#### 굉장히 높은 정확도와 다양한 고급기능을 탑재하고 있지만 유료이다.


![image](https://github.com/TIcording/subproject_ML_DL/assets/131944225/0f284dde-20ab-4608-a85d-0655ec9ec7b2)



### 3. PaddleOCR
#### 빠른 속도와 정확서을 가지고 있지만 모델 사이즈 매우 커서 불편함이 있다.


![image](https://github.com/TIcording/subproject_ML_DL/assets/131944225/36002972-da06-4e13-8487-6f34de565c22)

#### 성능,정확도, 다국어 지원 비교분석

![image](https://github.com/TIcording/subproject_ML_DL/assets/131944225/e391e933-c58a-4208-a025-936580f90357)

![image](https://github.com/TIcording/subproject_ML_DL/assets/131944225/3da2d80d-6f79-400b-b8db-b3ed0e2cda68)

![image](https://github.com/TIcording/subproject_ML_DL/assets/131944225/dd31f883-3beb-47e4-ab39-bf8e24e99549)

## 결론

![image](https://github.com/TIcording/subproject_ML_DL/assets/131944225/92e330df-75aa-4cd5-bbf2-fd2434ed9287)










