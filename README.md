# NS 홈쇼핑

# Overview

- **Title** : NS SHOP+ 판매실적 예측을 통한 편성 최적화 방안(모형) 도출
- **Organization** : 2020 빅콘테스트 (NIA 한국정보화진흥원, KBD 빅데이터포럼), NS 홈쇼핑
- **Description** : NS Shop+편성데이터(NS홈쇼핑) 를 활용하여 방송편성표에 따른 판매실적을 예측하고, 최적 수익을 고려한 요일별/ 시간대별 / 카테고리별 편성최적화 방안(모형) 제시
- **Author** : 김홍엽
- **Date** : 20/08/19 ~

# Dataset

- **실적데이터(sales_result.xlsx)** : 19년1월~19년12월 프로그램별 실적 데이터
- **외부데이터(rating.xlsx)** : 요일별/시간대별 분단위 시청률 데이터 (단위 %)
- **예측시점(test.xlsx)** : 20년6월 프로그램별 분당실적 예측

## Timeline

|date|day|note|
|:-----:|:-----:|:------|
|20/08/20|thur|Data Preparation, Analyzing the Features(노출(분) 분석)|
|20/08/21|fri|Analyzing the Features(방송일시, 상품군 분석)|
|20/08/22|sat|Analyzing the Features(마더코드, 상품코드, 노출 횟수 분석)|
|20/08/23|sun|Analyzing the Features(상품명 분석, Conclusion)|

## Notebooks and Analysis

The project includes the following notebooks:

- [Data Preparation & Exploration](https://github.com/hngyb/Project/blob/master/NS-Shop/Data-Preparation-and-Exploration.ipynb "")
- [EDA Colab](https://colab.research.google.com/drive/1dWjT8E7oJeT037ptJeBe-3uwG_papIeo?usp=sharing)

## Reference

|#|title|source|note|
|:---:|:--------:|:---------:|:---------|
|1|[최규민님의 Instacart EDA](https://gist.github.com/goodvc78/3653c8f6a510f619d7ad6570111f38d8 "")|최규민|Week-Hour analysis 참고|
