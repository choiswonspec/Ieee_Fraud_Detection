2020-11-13

# 캐글 IEEE Computational Intelligence Society

- https://www.kaggle.com/c/ieee-fraud-detection/overview
- 카드 기록을 활용한 사기 거래 탐지
- 대부분 컬럼이 비식별화 되어 있어, 데이터 탐색을 통한 데이터에 대한 이해가 매우 중요하다.

# 사용 데이터

#### train.csv: 모델 학습용 데이터(데이터가 커서 샘플링된 데이터 제공) / test.csv: 모델 평가용 데이터

- TransactionID: 거래 ID ( 비식별화 )
- TransactionDT: 거래 시각 ( 비식별화 )
- TransactionAmt: 거래 금액(US Dollar)
- ProductCD: 상품 코드
- card1 – card6: 카드 관련 정보(비식별화)
- P_emaildomain, R_emaildomain: 이메일 정보
- M1 – M9: 기존 거래와의 매칭 정보
- isFraud : 사기 거래 여부
