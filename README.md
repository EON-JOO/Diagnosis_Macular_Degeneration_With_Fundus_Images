# Diagnosis Of Macular Degeneration With Fundus Images
## 2021.05 ~ 2021.07

## 주제
- 딥러닝을 이용하여 Fundas Image로부터 Macular Degeneration(황반변성)을 판별할 수 있는 모델 개발

## 요약
- Kaggle에 있는 Color Fundus Image 데이터를 Gray-scale로 바꾸어 사용했습니다.
- LeNet-5를 이용하여 학습했습니다.
- 전체 데이터 중 Mecular Degeneration을 판별하는 모델과 Mecular Degeneration의 dry/wet 유형을 판별하는 모델을 학습했습니다.

## 결과
### Model ver3 : Mecular Degeneration 판별
- train loss:  0.00018383996561169625
- train accuracy:  1.0
- valid accuracy:  0.5645161271095276

![image](https://user-images.githubusercontent.com/84446424/182026946-d7752662-e15f-45b6-8dc3-73f555d23c2e.png)
- 구별 이미지 예시

![image](https://user-images.githubusercontent.com/84446424/182027179-d36477bb-a4ec-4a41-a0fd-a3512564e8af.png)

### Model ver4 : Dry/Wet 판별
- train loss:  0.001539267748594284
- train accuracy:  1.0
- valid accuracy:  0.7666666507720947

![image](https://user-images.githubusercontent.com/84446424/182027251-534aa034-435f-4e4f-96df-77ba6775f308.png)
- 구별 이미지 예시

![image](https://user-images.githubusercontent.com/84446424/182027312-e49efa96-5db5-4f94-83f0-3c69a4590037.png)
