## Detecting Anomaly in Time Series Data

#### R 을 이용한 이상감지

#### 주요 구성요소(Principal Component) 분석

#### Chisq 제곱분포(Square dictribution)

---

## What are Breakouts in Time Series Data?

#### Breakout
    * 시계열 데이터에서 관찰 된 중요한 변화
    * 아래에 주어진 두 가지 특성으로 구성됨
        * **Mean shift**
            * 시계열 데이터 내 갑작스러운 **변화**를 의미
            * 시계열이 하나의 고정적인 상태에서 다른상태로 옮겨갈 때 추가됨
            * 예) cpu 사용율이 35% 에서 75%로 증가한 경우
        * **Ramp Up**
            * 하나의 정상 상태에서 다른 상태로 메트릭 값이 갑자기 증가하는 것
            * mean shift 과 비교하여 하나의 안정된 상태에서 다른 상태로 천천히 전이하는 과정
    * 종종 위 두가지 특성이 같이 나타나기도 함
        
#### 시계열에서 Breakout 감지하기
    * Breakout 을 찾아내기 위해 트위터에서 "BreakoutDetection" 이라는 패키지 발표
    * 빠른 속도로 Breakout 을 감지하는 오픈 소스 패키지
    * E-Divisive with Medians (EDM) 알고리즘을 사용하여 평균 내 분기를 감지
    * 시계열 내의 분포 변화를 감지하는 데에도 사용 가능
    