# 이커머스 데이터 분석 프로젝트
![image](https://github.com/wbin0718/e-commerce_data_analysis/assets/104637982/f6a3f9a2-8a1e-495e-a5e7-8f310044521b)

Kaggle Brazilian E-commerce Public Dataset by Olist 데이터를 활용하여 EDA 및 sql을 활용해 간단한 비즈니스 분석을 위한 프로젝트입니다.

`분석 목표: 빅쿼리를 활용한 재구매율, 코호트, RFM 분석`

#### 데이터

* 출처: [데이터 셋 링크](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
* 설명: 브라질 이커머스 Olist Store의 주문 데이터
* 기간: 2016~2018년 사이의 약 10만건의 주문 데이터

#### 데이터 스키마
 
![image](https://github.com/wbin0718/e-commerce_data_analysis/assets/104637982/2d9cfc02-1a09-405b-9e22-673e5c12f211)

#### 분석

1) 데이터 탐색
  * 데이터 이해를 목적으로 각 테이블마다 어떤 값이 들어 있는지 확인 및 시각화를 진행했습니다.
  * EDA 링크 https://github.com/wbin0718/e-commerce_data_analysis/blob/master/e_commerce.ipynb
2) 빅쿼리 분석
  * 가장 주문율이 높은 상위 3개 카테고리를 찾고, 이후 분석에 활용을 했습니다.
  * 상위 3개 카테고리의 재구매율 분석을 진행했습니다.
  * 3개의 기준을 통해 코호트를 구성하고 기간별 리텐션 분석을 진행했습니다.
  * SQL 링크 https://github.com/wbin0718/e-commerce_data_analysis/blob/master/e_commerce_sql.ipynb
