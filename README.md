kaggle에서 쓰레기데이터 사용</br>
https://www.kaggle.com/datasets/sumn2u/garbage-classification-v2?select=trash</br>
</br>
</br>
1채널 - 그레이스케일 , 외삽법, sobel, canny</br>
ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ</br>
1채널학습(그레이스케일) : 그레이스케일 및 데이터 전처리 후 그레이스케일 학습</br>
sobel(그레이스케일 + 데이터전처리) : 그레이스케일 및 데이터 전처리 후 소블학습</br>
0717 canny : 데이터 전처리 후 캐니학습</br>
</br>
</br>
3채널 - 외삽법, 데이터증강, mobilenet_v2, resnet18</br>
ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ</br>
mobilenet(데이터증강) : 데이터증강 전/후 mobilenet_V2 모델 사용 모델학습 & 시각화</br>
resnet18(데이터증강) : resnet18 모델 사용 모델학습 (과적합 및 학습시간이 너무 오래걸려 학습중단)</br>
mobilenet(랜덤서치_시각화) : mobilenet_V2 모델 사용 랜덤서치를 통한 최적의 하이퍼 패러미터 도출</br>
0717 최적의하이퍼파라미터 : 랜덤서치를 통해 도출한 최적의 하이퍼 패러미터 mobilenet_v2모델을 통해 학습</br>
efficientnet_b2 랜덤서치, 그리드 서치</br>
ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ</br>
### <최종> </br>
최적의 하이퍼파라미터: 'learning_rate': 0.0002091067002623071, 'weight_decay': 0.0042590114903666605, 'dropout': 0.4 </br>
최종: Best train loss: 0.1653, Best train accuracy: 0.95%
