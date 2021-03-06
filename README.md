# Kaggle_Practice
- Kaggle 우승작으로 배우는 머신러닝 탐구생활 참고 EDA 및 Baseline 코드 작성
- 2.8 (토) ~ 

### (1) 산탄데르 제품 추천 경진대회 (Santander-Product-Recommendation)
- 대회의 목적 : 고객이 신규로 구매할 제품을 찾는 것.
- 주어진 월별 데이터를 이용해 신규 구매를 예측하는 것

#### ** 후기 : 데이터 변수명 파악이 까다롭고 많은 전처리 과정이 필요(날짜 파생변수 등)해서 조금 어려웠던 것 같음
#### ** 난이도 : ★★★★☆

### (2) 포르토세구로 안전 운전자 예측 경진대회 (Porto Seguro's Safe Driver Prediction)
- 대회의 목적 : 모델을 통해 운전자에게 합리적인 가격을 제공하고, 더 많은 운전자들이 자동차 보험의 혜택을 받을수 있게 함

#### ** 후기 : 탐색적 데이터 분석 과정을 통해 확인결과 변수들은 모두 익명화되어있고 값들은 숫자로 치환되어있고 범주형 변수도 이미 숫자로 치환되어있어, 데이터 전처리를 수행할 필요가 없을 만큼 데이터가 깔끔하고 깨끗하여 비교적 분석하는데 용이했던 것 같음.
#### ** 난이도 : ★★☆☆☆

### (3) 텐서플로 음성인식 경진대회 (Tensorflow Speech Recognition)
- 대회 목적 음성 클립에서 무슨 단어가 들리는 지를 예측하는 경진대회
- 수천명의 목소리로 이루어진 30개의 짧은 단어들에 대한 1초 가량의 65,000개 이상의 1초 가량의 음성 데이터셋
- 이 경진대회를 통해 30개의 짧은 명령어를 90% 가량의 정확도로 맞추는 모델이 공개됨.
- 약 1초 길이의 음성 클립은 10개의 단어(yes, no, up, down, left, right, on, off, stop, go)와 무음을 의미하는 silence 그리고 10 개단어에 속하지 않는 unknown 총 12개로 분류됨.

#### ** 미완 : EDA만 진행
#### ** 후기 : Pytorch 및 컴퓨팅 제약사항 떄문에 EDA까지만 진행하였는데 처음 다뤄보는 음성데이터라 신기하고 많은 것을 배웠음.
#### ** 난이도 : ★★★☆☆

### (4) 스테이트 팜 산만한 운전자 탐지 경진대회 (State_Farm_Distracted Driver Detection)
- 대회 목적 : 이미지 안의 운전자가 어떤 자세를 취하고 있는지 예측
- 26명의 운전자의 이미지 데이터가 훈련 데이터로 제공되고, 그 외 새로운 운전자 n명의 이미지 데이터가 포함된 테스트 데이터로 제공됨.
- 교차검증, 데이터 어그멘테이션, 전이학습, 앙상블 등을 사용하여 해결 필요

#### ** 미완 : EDA만 진행
#### ** 후기 : 컴퓨팅 제약사항 떄문에 EDA까지만 진행 전이학습에 대해 배웠음.
#### ** 난이도 : ★★★☆☆

### (5) 자전거 수요 예측 (Bike Sharing Demand Prediction) - 2020/05/15
- 대회 목적 : 워싱턴 공공 자전거 데이터를 바탕으로 수요를 예측하는 모델을 만드는 것

#### ** 후기 : 어렵지는 않음. 
#### ** 난이도 : ★★★☆☆

### (6) 타이타닉 생존자 예측 (Titanic Survivor Prediction) - 2020/05/23
- 대회 목적 : 캐글에서 가장 유명한 타이타닉 대회 / 생존자 예측

#### ** 후기 : 유투브 허민석님 동영상 보고 참고해서 했는데 굉장히 설명을 잘해주심. + 중간중간 보완했으면 좋을 부분도 생각이 들었음.
#### ** 난이도 : ★★★☆☆
