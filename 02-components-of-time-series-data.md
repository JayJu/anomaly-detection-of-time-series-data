## Components of Time Series Data

#### 시계열 데이터의 패턴 유형
    1. ##### Trend(추세)
        ![](/img/time_series_trend.jpg)
        * 설명
            * 오랜 기간 동안 나타나는 패턴. 긍정적/부정적/선형/비선형 등 모든 형태의 불규칙적인 결과들
            * 시계열에 증가 또는 감소하는 패턴이 없으면 변화가 없는(stationary) 것으로 간주
        * Trend 의 두가지 유형
            1. Deterministic(확정적) 추세
                * 시계열의 값이 시간의 함수로 주어짐
                * 추세를 제거하는 방법은 모수에 관한 선형 또는 비선형모형을 이용(회귀모형)
            2. Stochastic(확률적) 추세
                * 시계열의 성장이나 감소율이 자기 과거 값들의 종속관계로 설명됨
                * 추세를 제거하는 방법은 적절한 차수의 차분을 이용(차분모형)
        
    2. ##### Cyclical(순환)
        ![](/img/time_series_cyclical.jpg)
        * 설명
            * 특정 트렌드 주변으로 나타나는 증가/감소 패턴
            * 시계열 에서 진동 처럼 나타나는 패턴
            * 순환 주기는 비즈니스 문제나 산업군에 따라 다름
            
    3. ##### Seasonal(계절)
        ![](/img/time_series_seasonality.jpg)
        * 설명
            * 규칙적인 파동으로 나타나는 패턴
            * 데이터가 계절적인 요인이나 맞춤요인(Custom Factor)으로 인해 일정한 간격으로 정기적으로 발생
            * 항상 고정적이고 알려진 기간으로 구성
        * 계절성(seasonality)를 갖는 대표적인 데이터
            * 기후(Climate)
            * 제도(Institutions)
            * 사회적인 습관이나 관행(Social hibits & practics)
            * 일정(Calendar)
        * 시계열 데이터에서 계절성 패턴을 생성하는 두 가지 모형
            * 가법모형(Additive Model of Time Series )
            * 승법모형(Multiplicative Model of Time Series)
            
    4. ##### Irreguar(불규칙성)
        ![](/img/time_series_irregular.jpg)
    