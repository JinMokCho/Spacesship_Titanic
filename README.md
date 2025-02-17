Spaceship Titanic Machine Learning Project

프로젝트 개요
이 프로젝트는 "Spaceship Titanic" 데이터셋을 사용하여 승객의 생존 여부를 예측하는 머신러닝 모델을 구축하는 것입니다. 
데이터 전처리, 탐색적 데이터 분석(EDA), 여러 머신러닝 모델 학습 및 하이퍼파라미터 튜닝을 포함합니다.


데이터 전처리
결측치 처리: KNNImputer를 사용하여 결측치를 대체합니다.
열 삭제: 분석에 필요 없는 열(Name, PassengerId, Cabin)을 삭제합니다.
범주형 변수 인코딩: 범주형 변수를 숫자로 변환하여 머신러닝 모델이 이해할 수 있도록 합니다.

탐색적 데이터 분석 (EDA)
이산형 및 범주형 변수에 대한 기초 통계량 및 시각화를 수행합니다.
상관 분석 및 가설 검정을 통해 변수 간 관계를 분석합니다.

모델 학습 및 평가
데이터를 학습 세트와 테스트 세트로 분할합니다.
여러 머신러닝 모델(SVC, KNN, Decision Tree, Logistic Regression, Random Forest, XGBoost, LightGBM)의 성능을 교차 검증을 통해 평가합니다.

하이퍼파라미터 튜닝
LightGBM 모델의 하이퍼파라미터를 그리드 서치를 통해 최적화합니다.

결과
LightGBM 모델이 가장 높은 정확도(0.799)를 기록하였으며, 최적의 하이퍼파라미터는 다음과 같습니다:
learning_rate: 0.05
max_depth: 5
n_estimators: 175

기여
이 프로젝트에 기여하고 싶으신 분은 자유롭게 Pull Request를 보내주세요.

라이센스
이 프로젝트는 MIT 라이센스 하에 제공됩니다.
