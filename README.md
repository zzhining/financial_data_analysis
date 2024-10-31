# 금융 관련 데이터 분석

국내 주식, 해외 주식, 환율, ETF, 지수 등 주요 경제 관련 데이터를 분석합니다.

## 개별종목 대시보드
- `pykrx`를 사용하여 개별 주식 종목을 수집하고, 일자별 종가 변화량, 요일별 상승/하락 비율 등을 시각화한 대시보드를 생성
- [코드 바로가기](https://github.com/zzhining/financial_data_analysis/blob/main/pykrx_dashboard.ipynb)
- (참고) [pykrx](https://github.com/sharebook-kr/pykrx)


## 거래량 기반 매매타점 확인 알고리즘
- `Finance Data Reader`를 사용하여 개별 주식 가격 정보를 수집하고 , `거래량으로 분석하라` 책의 내용을 참고하여 **거래량 기반 매매타점** 판별 알고리즘을 구현
- [코드 바로가기](https://github.com/zzhining/financial_data_analysis/blob/main/volume_mass_analysis.ipynb)
- (참고) [FininceDataReader](https://financedata.github.io/posts/finance-data-reader-users-guide.html), [S&P500 분석]()

## 신문기사 스크랩
- 네이버 증권의 일자별 신문기사 스크랩하여 csv 파일로 저장하는 코드
- [코드 바로가기](https://github.com/zzhining/financial_data_analysis/blob/main/finance_news_scrap.ipynb)

## 증권 리포트(paxnet) 스크랩
- [Paxnet](https://www.paxnet.co.kr/stock/report/report?wlog_rpt=jm&menuCode=2222)의 투자 의견(매수/매도 등)을 스크랩하여 csv파일로 저장하는 코드
- [코드 바로가기](https://github.com/zzhining/stock_market_analysis/blob/main/4%EC%A3%BC%EC%B0%A8/10_paxnet_%EC%A6%9D%EA%B6%8C%EC%82%AC_%EC%A2%85%EB%AA%A9_%EB%A6%AC%ED%8F%AC%ED%8A%B8.ipynb)

## 주가 데이터 예측
- 주가 데이터(종가)를 활용한 ML 기반 회귀모델: [코드 바로가기]()
- 주가 데이터(종가)를 활용한 DL 기반 회귀모델: [코드 바로가기]()

---
## 참고자료
- [시계열데이터 선형회귀분석 코드](https://github.com/zzhining/time_series_basic/blob/main/02_time_series_prediction_toy_model.ipynb)
- [시계열데이터 하이브리드 분석 코드](https://github.com/zzhining/time_series_basic/blob/main/06_hybrid_models.ipynb)
