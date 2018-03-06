## What is Anomaly?

#### 이상(Anomaly) 이란
    * 정상적인 행동 또는 예상되는 행동에서 벗어나는 것 또는 상태
    * 은행출금의 예
        * 나의 저축은행계좌 에서는 만원 정도가 출금된다
        * 어느날 내 계좌에서 10만원이 출금되었다면 이는 은행원의 입장에서 이상(anomaly) 행위가 된다
    * 이상(Anomaly)은 데이터 내에서 모순된 관찰 (contradictory observation) 의 한 종류이며 특정 모델 또는 가정이 문제 설명에 맞지 않는다는 증거를 제공함
    
#### 이상(Anomaly)의 유형
    * Point Anomalies
        * 데이터 집합 내의 특정 값이 전체 데이터와 관련하여 변칙적 인 경우
        * 예) 위에서 언급한 출금트랜잭션
    * Contextual Anomalies
        * 특정 상황에서 데이터가 비정상적으로 발생하는 경우
        * 예) 특정 기간에만 발생하는 이상
    * Collective Anomalies
        * 수집된 데이터 집합이 나머지 데이터 집합과 관련하여 변칙적 인 경우
        * 예) 심전도에서 관찰 된 추세(trend)와 분열된 이상
    
---
## Models of Time Series Data

* #### ARIMA(Autoregressive Integrated Moving Average) 모형
    * 자기회귀(Autoregressive) 모형과 이동평균(Moving Average) 모형의 결합(Integrated)
    * 자동 회귀 (Auto-Regressive, AR)는 차분 계열의 시차를 말하며, 이동 평균 (MA)은 오차의 차이이며 I는 시계열을 고정(stationary)시키는 데 사용 된 차수를 나타냄

* #### Holt-Winters 모형