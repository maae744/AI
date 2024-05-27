
1.인공지능에서 지능에 해당하는 기능은 무엇인가?
-인공지능을 사용하면 기계가 경험을 통해 학습하고, 새로운 입력에 적응하고 인간과 유사한 작업을 수행할 수 있습니다.

2.인공지능의 종류 3가지에 대해서 설명하시오 (지도학습, 반지도학습, 강화학습)
-지도학습은 레이블이 지정된 데이터 세트를 사용하여 알고리즘을 훈련하여 결과를 예측하고 패턴을 인식하는 기계 학습의 한 범주입니다.
-반지도학습은 레이블이 있는 데이터와 레이블이 없는 데이터를 모두 활용하는 광범위한 기계 학습 기술 범주입니다.
-강화학습은 원하는 행동에 보상을 하고 바람직하지 않은 행동에 처벌하는 것을 기반으로 하는 기계 학습 훈련 방법입니다.

3.전통적인 프로그래밍 방법과 인공지능 프로그램의 차이점은 무엇인가?
-기존 프로그래밍에서는 데이터를 구조화해야 하며 변경에 어려움을 겪을 수 있습니다. 
그러나 AI는 자연어와 같은 비정형 데이터 작업에 능숙하며 사물 AI 개념에서 볼 수 있듯이 명시적인 재프로그래밍 없이도 새로운 정보에 적응할 수 있습니다.

4.딥러닝과 머신러닝의 차이점은 무엇인가?
-머신러닝은 인간의 간섭을 최소화하면서 자동으로 적응할 수 있는 AI입니다. 딥러닝은 인공 신경망을 사용하여 인간 두뇌의 학습 과정을 모방하는 기계 학습의 하위 집합입니다.

5.Classification과 Regression의 주된 차이점은?

-Classification은 개별 레이블 또는 범주를 예측합니다.
-Regression은 연속적인 숫자 값을 예측합니다.

6. 머신러닝에서 차원의 저주(curse of dimensionality)란?
-차원이나 기능의 수가 증가함에 따라 기계 학습 모델을 정확하게 일반화하는 데 필요한 데이터의 양이 기하급수적으로 증가합니다.

7.Dimensionality Reduction는 왜 필요한가?
-Dimensionality Resuction은 데이터 압축 프로세스를 지원하여 데이터가 더 적은 저장 공간을 차지하고 계산 시간을 단축할 수 있게 해줍니다.

8. Ridge와 Lasso의 공통점과 차이점? (Regularization, 규제 , Scaling)
-Ridge Regression은 계수의 제곱에 비례하는 페널티 항을 추가합니다. Lasso는 계수의 절대값에 비례하는 페널티 항을 추가합니다.

9. Overfitting vs. Underfitting.
-Overfitting은 모델이 복잡하고 데이터에 밀접하게 맞는 경우 발생하고 Underfitting은 모델이 너무 단순하여 관계와 패턴을 정확하게 찾을 수 없는 경우 발생합니다.

10. Feature Engineering과 Feature Selection의 차이점은?
-Feature Engineering은 새로운 기능을 생성하거나 기존 기능을 변환하여 알고리즘에 더 유용하게 만드는 데 중점을 둡니다.
-Feature Selection은 데이터 세트에서 가장 유익한 기능 하위 집합을 선택하는 데 중점을 둡니다.

11. 전처리(Preprocessing)의 목적과 방법? (노이즈, 이상치, 결측치)
-전처리(Preprocessing)는 원시 데이터를 깨끗한 데이터 세트로 변경하는 개념입니다.

12. EDA(Explorary Data Analysis)란? 데이터의 특성 파악(분포, 상관관계)
-EDA(Exploratory Data Analysis)은 데이터의 일반적인 패턴을 식별하는 분석 접근 방식입니다. 이러한 패턴에는 예상치 못한 데이터의 이상값과 특징이 포함됩니다. EDA는 모든 데이터 분석의 중요한 첫 번째 단계입니다.

13. 회귀에서 절편과 기울기가 의미하는 바는? 딥러닝과 어떻게 연관되는가?
-x의 1단위 변화에 대한 y의 변화를 나타냅니다. y절편이라고도 하는 절편은 가장 잘 맞는 선이 y축과 교차하는 곳입니다. 데이터의 초기 조건 또는 시작점을 나타냅니다.

14. Activation function 함수를 사용하는 이유? Softmax, Sigmoid 함수의 차이는?
-Activation function는 뉴런이 활성화되어야 하는지 여부를 결정합니다. 이는 더 간단한 수학적 연산을 사용하는 예측 과정에서 네트워크에 대한 뉴런의 입력이 중요한지 여부를 결정한다는 의미입니다.
--"softmax"는 다중 클래스 분류에도 적용할 수 있는 반면 "sigmoid"는 이진 분류에만 적용할 수 있습니다. Softmax는 각 출력 노드에 대해 0과 1 사이의 값을 예측하며, 모든 출력은 합이 1이 되도록 정규화됩니다.

15. Forward propagation, Backward propagation이란?
-역방향 전파는 오른쪽(출력 계층)에서 왼쪽(입력 계층)으로 이동하는 프로세스입니다. 순방향 전파는 신경망에서 데이터가 왼쪽(입력 계층)에서 오른쪽(출력 계층)으로 이동하는 방식입니다. 신경망은 연결된 입력/출력 노드의 모음으로 이해될 수 있습니다.

16. 손실함수란 무엇인가? 가장 많이 사용하는 손실함수 4가지 종류는?
-알고리즘을 이론적인 것에서 실용적인 것으로 가져오고 신경망을 미화된 행렬 곱셈에서 딥러닝으로 변환합니다.
-교차 엔트로피 손실, 평균 제곱 오차, 휴버 손실, 힌지 손실

17. 옵티마이저(optimizer)란 무엇일까? 옵티마이저와 손실함수의 차이점은?
-옵티마이저(optimizer)는 학습 속도 및 가중치와 같은 신경망의 속성을 조정하는 알고리즘 또는 함수입니다.
-손실함수는 모델이 얼마나 '잘못'되었는지를 정량화하고 옵티마이저는 모델의 매개변수를 변경하여 이 오류를 최소화하려고 시도합니다.

18. 경사하강법 의미는? (확률적 경사하강법, 배치 경사하강법, 미치 배치경사하강법)
-경사 하강법은 미분 가능한 함수의 국소 최소값을 찾는 최적화 알고리즘입니다. 기계 학습의 경사하강법은 단순히 비용 함수를 최대한 최소화하는 함수의 매개변수 값을 찾는 데 사용됩니다.
-경사하강법 학습 알고리즘에는 배치 경사하강법, 확률적 경사하강법, 미니배치 경사하강법의 세 가지 유형이 있습니다.

19. 교차검증, K-fold 교차검증의 의미와 차이
-교차검증 - 데이터를 두 부분으로 나누어 학습 알고리즘을 평가하고 비교하는 통계적 방법입니다.
K-Fold - 예측 모델을 평가하는 기술입니다.
차이: cross_val_score는 데이터를 평가하고 점수를 반환하는 함수입니다. 반면, KFold는 데이터를 K개의 폴드로 분할할 수 있는 클래스입니다.

20. 하이퍼파라미터 튜닝이란 무엇인가?
-하이퍼파라미터는 학습 알고리즘이 훈련되기 전에 값이 선택되는 머신러닝 매개변수입니다. 하이퍼파라미터를 매개변수와 혼동해서는 안 됩니다. 머신러닝에서 레이블 매개변수는 훈련 중에 값이 학습되는 변수를 식별하는 데 사용됩니다.

https://sdc-james.gitbook.io/onebook/4.-and/5.2./5.2.3.
