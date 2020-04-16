# PCG를 활용한 심장질환 예측 모델 개발

### 1. 프로젝트 소개

- PCG를 활용한 심장질환 예측 모델 개발
- PCG란 Phonocardiogram의 약자로 청진음을 의미
- PCG는 심장질환 예측시 분석이 주관적이고 간단하다는 이유로 잘 사용되지 않았지만 **데이터의 정량적 지표**와 올바르게 학습된 **컴퓨터 네트워크 모델**이 있다면 사람이 분석하는 것보다 빠르고 정확한 결과를 낼 수 있음
- PCG 신호는 크게 4가지 상태로 분류됨(S1, Systole, S2, Diastole)
- 정상적인 심장음에는 잡음이 거의 없지만 비정상적인 심장음에는 잡음미 많이 섞여 있음
- 이렇게 정상, 비정상으로 나뉜 데이터와 구간별로 획득된 데이터를 컴퓨터 모델을 학습
- 모델 학습을 통해 입력 받은 pcg신호의 구간을 나누고 상태를 분류후 질병의 유무를 판정
### 2. 팀 소개
- 산학협력 분반(연세의료원)
- 정주영

### 3. Abstract
- This project's goal is **develope a PCG segmentation model and analysis cardiac disorder**
- This project can help decrease patient's cost for diagnosing disease
- In this project we use open datasets to train model
- PCG is Phonocardiogram's abbreviation
- We will use 1 dimensional(or 2D) CNN and LSTM(like RNN) to predict PCG signal's state
- PCG signal has 4 states which is S1, Systole, S2, Diastole
- Normal PCG has no murmur or click sound in Systole or Diastole
- But abnormal PCG has noise in Systole or Distole
- So Computer Network model can learn normal and abnormal pcg's features

### 4. 소개 영상

### 5. 결과 영상
