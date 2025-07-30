# cnn_chart_pattern_filter
CNN을 통해서 차트의 기술적 모양을 분류해 낸다.
지금 초기 단계에서는 밑의 4가지 서로다른 패턴(파이썬의 숫자들을 약간씩 조정하면서 서로 유사하지만 완전히 같지 않은 샘플 50개씩을 준비해서 학습 시켰다.
<img width="1690" height="762" alt="image" src="https://github.com/user-attachments/assets/2b8de7f0-9991-4b63-a9cc-f49263c16e97" />

<img width="1687" height="772" alt="image" src="https://github.com/user-attachments/assets/e72a4c2d-6376-4234-bf71-682759a0320d" />

<img width="1698" height="766" alt="image" src="https://github.com/user-attachments/assets/26788f1e-a2e2-4525-bd7a-b50eb59df55a" />

<img width="1678" height="756" alt="image" src="https://github.com/user-attachments/assets/49857a29-ab4f-4272-ba45-be12cb6ebd56" />

그래서 실제로 주식의 패턴을 잘 식별 할 수 있는지 밑의 테스트 셋으로 실험해 보았다.

<img width="1183" height="208" alt="image" src="https://github.com/user-attachments/assets/11b8b4a6-2784-49c5-b0dd-9993c228860f" />
밑의 그림들은 트레이더, 투자자들 사이에서 회자되는 종목들의 과거 차트를 가져온 것인데 잘 구분하는 모습을 보인다.

느낀 점은 이미 잘 개발되어져 있는 모델을 '깃' 해서 사용하면 되니까 매우 편리한데 가설을 세우고 데이터를 나누고 
이를 정제하는 것이 더 어렵다는 것을 느꼈다.

사실 이런 패턴에 따라서 매매를 한다고 해서 드라마틱하게 수익이 좋아지는 것은 아니지만 그래도 확률이 조금 더 높은 곳에 
배팅하는 것이 유리한 것은 사실이며 이후 위의 패턴에 따른 수익률도 추적해서 비교해 보면 더 좋을 것 같다.

일단! 지금 해야 하는 것은 더 많은 패턴들을 공부해서 이 녀석에게 학습시키는 것이다.
