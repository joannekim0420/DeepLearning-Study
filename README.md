﻿﻿Deep Learning Final Project for Deep Learning study

Weather Forecast using Deep Learning

>predicted the highest temperature of the day on Daejeon region (Korea) in order to distinguish whether or not there is heatwave. 

### 활용이론

- 폭염 주의보
일최고기온이 33도 이상인 상태가 2일 이상 지속될 것으로 예상될 때

-Univariable vs Multivariable (단변수/다변수)
독립변수 X의 개수에 하나인 경우 univariable, 여러 개인 경우 Multivariable.
- Univariate vs Multivariate (단변량/다변량)
종속변수 Y의 개수가 하나인 경우 univariate, 여러 개인 경우 Multivariate.


![thoery1](https://github.com/joannekim0420/DeepLearning-Study/blob/master/finalproejct/theory1.png)
- RNN (Recurrent Neural Network)
히든 노드가 순환 구조를 이루는 인공 신경망의 한 종류로 문장 번역, 이미지 주석 생성, 시계열 예측 등의 Sequence data를 다루는 데 용이하다. 히든 노드의 결과가 다시 같은 히든 노드의 입력으로 들어가도록 연결되어 있다. 이런 특성이 순서 또는 시간 측면을 고려할 수 있는 특징을 가져다 준다.


![thoery2](https://github.com/joannekim0420/DeepLearning-Study/blob/master/finalproejct/theory2.png)
- RNN의 문제점 : Vanishing Gradient Problem
출력 데이터와 참고해야 할 데이터 간의 차이가 클 때 성능 저하가 발생한다. 이는 반복되는 연산으로 먼거리에 있는 데이터의 영향력이 감소해서 발생하는 현상이다.


![thoery3](https://github.com/joannekim0420/DeepLearning-Study/blob/master/finalproejct/theory3.png)
- LSTM(Long Short-Term Memory models)
Vanishing Gradient problem 을 극복하기 위한 모델이다. RNN에 히든 state인 Cell state를 추가한 구조이다. 이는 어떤 정보를 버릴지 결정 하는 forget gate layer, 어떤 값을 업데이트 할지 정하는 input gate layer 등 으로 구성되어 있다.


![hyperparameter 조정](https://github.com/joannekim0420/DeepLearning-Study/blob/master/finalproejct/result1.png)

