# American_Sign_Language_Recognition

 Pytorch와 Resnet152를 이용한 수화 인식 프로그램입니다. Kaggle American Sign Language의 데이터셋을 바탕으로 학습시켜 수화를 object detection하는 모델을 만들었습니다.


## 알고리즘
 작성중입니다.
 
## Repository 구성
 작성 중입니다
 
## 0. 개발환경
 작성중입니다.

## 1. DataSet
 Kaggle [hand-sign-images](https://www.kaggle.com/datasets/ash2703/handsignimages) 데이터셋을 사용하였씁니다. ASL(American Sign Language)는 미국 및 캐나다에서 주로 사용하는 수화입니다.
 ![ASL](/image/ASL.png)
 알파벳 A부터 Z까지 26개 전부 표현이 가능하지만 **Z의 수화는 검지 손가락으로 Z모양을 그리는 것**이기 때문에 학습에 사용한 데이터셋는 제외되어있습니다. 따라서 총 A부터 Y까지 총 25가지의 label이 있습니다.
 |알파벳 A|알파벳 Y|
 |--------|-------|
 |![A_ASL](/image/A_ASL.png)|![Y_ASL](/image/ASL.png)|
## 2. Train
 학습에 사용한 Hyperparameter은 다음과 같습니다
  > ~

## 3. Loss
 모델의 성능은 다음과 같습니다.

## 4. 실행방법
 작성중입니다.
 
## 5. 개선점
 작성중입니다.

 
## 참고 자료
[Hand Gesture Recognition Database](https://www.kaggle.com/datasets/gti-upm/leapgestrecog/code)

[2021 Ego-Vision 손동작 인식 AI 경진대회](https://dacon.io/competitions/official/235805/overview/description)

[2021 교통 수(手)신호 동작 인식 AI 경진대회](https://dacon.io/competitions/official/235806/overview/description)

[Hand Gesture Video Classification](https://www.kaggle.com/competitions/handgesturevideoclassification)

[Neural Sign Language Translation based on Human Keypoint Estimation](https://rladuddms.tistory.com/94)