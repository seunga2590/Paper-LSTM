# Prediction of Particulate matter in Urban and Industrial areas Using a Long Short-Term Memory Model with Comparative Analysis of the Predictive Contributions by Variables(thesis)

#### 논문 작성 기간 : 2020.09.01 ~ 2022.07.31
#### 사용 기술 
    | API crawling
Time_series : <img src="https://img.shields.io/badge/ARIMA-61DAFB?style=flat&logo=ARIMA&logoColor=white"/> <img src="https://img.shields.io/badge/RNN-6#FFB399?style=flat&logo=RNN&logoColor=white"/> <img src="https://img.shields.io/badge/LSTM-D27D32?style=flat&logo=LSTM&logoColor=white"/> <img src="https://img.shields.io/badge/CNN-LSTM-FFAAAF?style=flat&logo=React&logoColor=white"/>

    | XAI : Permutation Importance, SHAP
#### "미세먼지 예측"의 큰 주제를 시작
### # 머신러닝을 이용한 예측(AUTOML(Pycaret), ARIMA, Random Forest, XGBOOST, LightGBM, Catboost) 
#### ## 머신러닝 튜닝(Grid Search CV, Randomized Search CV, Optuna)
### # 딥러닝 이용한 예측(RNN, LSTM, CNN-LSTM)
### # XAI(eXplainable AI) : SHAP(SHapley Additive exPlanation)
### # 그래프 시각화 (Feature Importance, Summary plot, Dependence plot)



#### * 현재 산업에선 딥러닝의 소요비용과 시간으로 인해 머신러닝을 주로 사용
####  그 중, 딥러닝의 계산 원리의 블랙박스로 인한 비신뢰감도 큰 이유로 작용
####  XAI를 통해 딥러닝을 이용한 미세먼지의 예측과정을 해석함으로써 신뢰감을 줄 수 있지 않을까?의 생각으로 XAI 적용
####  하지만 현재 XAI는 개발 단계에 있음으로 'XAI를 이용해 해석할 수 있으니 딥러닝을 통해 예측해도 된다'보다는 
####  XAI를 이용한 딥러닝 예측 과정의 설명이 설득력 있는지를 우선 살펴보고자 논문을 작성



### * 결론 : XAI의 시각화 그래프를 통해 어느 정도 예측 과정에 어떤 변수끼리의 영향이 크게 작용했고 예측력을 낮추거나 올리는지를 확인할 수 있는 지표로 사용가능하나
###        실제 인간의 생활에 영향을 주는 만큼 더 확실한 설명과정이 추가되어야 한다고 봄
