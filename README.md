# 프로젝트 개요
Deep Learning의 Model 중 시계열데이터 예측에 탁월한 성능을 갖추고 있는 LSTM과 
주가예측기법중 EMA(지수이동평균)법을 활용하여 국내에서 각 산업군별 대장주라고 불리우는
NAVER, KAKAO, LG화학, SK하이닉스, 삼성전자, 엔씨소프트의 주가를 예측하는 프로젝트

### [프로젝트 PPT](https://github.com/Liam427/lstm-ema-stock-prediction/blob/master/lstm-ema-stock-prediction-ppt.pdf)

# 프로젝트 한계점
EMA특성상 5일의 평균으로 다음날을 예측하고 10일의 평균으로 다음날을 예측하는 기법인데 이 기법이 과연 정확한지
그 다음날에 큰 이슈가 있다면 이 예측값은 맞지 않을 수도 있는데 그런것에서 오는 위험도를 가중하지 못하였다.
그리고 단지 종가평균으로 예측하기 보다는 각 회사의 재무적 관점 데이터인 EBIT, PER, EPS등을 더 활용하여 
예측을 한다면 앞서 말한 위험에서 좀 더 자유로워 질 수도 있다고 생각한다.

# Reference
  * https://github.com/huseinzol05/Stock-Prediction-Models
  * https://financedata.github.io/posts/finance-data-reader-users-guide.html
  * https://medium.com/mlreview/understanding-lstm-and-its-diagrams-37e2f46f1714
  * https://www.investopedia.com/terms/e/ema.asp
