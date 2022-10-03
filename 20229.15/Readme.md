# 서울시 지역별 생활 쓰레기 배출량 분석
####                                                                          2022-09-24 스터디 내용
## 1. 스터디원이 각자 분석한 자료 공유 및 의견공유
- read_csv 사용시 header 을 사용하면 전처리시 칼럼 수정을 안해도 됨
- astype 으로 일일히 변경하지 않고 to_csv 및 read_csv 사용하면 자동으로 변경됨
- 연령별, 지역별 비율로 새로운 feature을 만드는 방안
- 머신러닝 및 딥러닝 모델 결과 공유

## 2. 공모전 관련 정보
- 스터디 원 간에 kt genie 랩 공모전 참가자가 많으므로 의견 공유
- 캐글이나 데이콘의 코드를 참고하면 좋음
- 최근 많이 사용하는 모델은 catboost 와 optuna 의 조합임
- optuna의 경우 회귀형이면 minimize, 범주형이면 maximize 를 준다고 함
- test와 train 데이터를 그냥 분할하면 데이터 불균형을 초래 할 수 있음
- 위 경우 onesideselection과 stractified kfold 를 사용하는 방법도 있음
