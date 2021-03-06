# 2021-2 자료분석특론 Final Project

2021년 대학원 자료분석특론 수업의 Final Project로 진행한 내용으로, 수업 내용에서 배운 모델만을 가지고 분석을 진행하였다. 2개의 데이터를 분석하였으며, 구조화된 데이터 1개와 이미지 데이터 1개이다.
<br>
:smiley: [발표 자료](https://github.com/jihye0115/2021-Advanced-Data-Analysis-Final-Project/blob/main/Project%20Presentation.pdf)는 두 주제를 합산하여 10분 이내에 발표한 자료로 매우 축약되어 있으며, 각 변수에 대한 EDA부터 모델링 과정 전체를 확인하려면 [보고서](https://github.com/jihye0115/2021-Advanced-Data-Analysis-Final-Project/blob/main/Project%20Report.pdf)를 참고하는 것이 좋다.
<br/> <br>

## 첫 번째 데이터 - Levels Fyi Salary data
데이터 과학 분야와 STEM(Science, Technology, Engineering, and Mathematics) 분야의 연봉에 대한 데이터로, Levels.fyi에서 스크래핑하여 캐글에 올려놓은 자료이다. Levels.fyi는 IT 업계의 각 회사별 직책과 연봉을 비교해주는 미국 스타트업이다. 이 데이터에는 매우 다양한 회사와 직무, 지역 등이 있고 결측치가 많으며 범주형 변수의 경우 정규성을 만족하지 못해 관심있는 범위로 주제를 좁혀 분석을 진행하였다.
<br/> <br>데이터 출처 : https://www.kaggle.com/jackogozaly/data-science-and-stem-salaries?select=Levels_Fyi_Salary_Data.csv
<br/> <br>
:chart_with_upwards_trend: 분석 목표 : 관측치가 가장 많고 유명한 아마존, 마이크로소프트, 구글, 페이스북, 애플 다섯개의 회사에 다니는 사람들의 직책, 직무, 경력, 학력 등 관측치에 대한 정보를 통해 회사로부터 받는 연봉, 보너스 등을 예측해보고 중요한 요인을 탐색하였다.
<br/> <br>

## 두 번째 데이터 - Mobile phone Image data
이 데이터는 스마트폰 사진 데이터로, 스리랑카 전자상거래 사이트 Ikman.lk에서 스크래핑하여 캐글에 올려놓은 자료이다. 해당 스마트폰의 기종과 브랜드를 포함하고 있어 두 가지 측면에서 분류 가능하다. 중고 품목이 약 80%를 차지하며, 판매자가 직접 찍은 사진이기 때문에 스마트폰 뿐 아니라 다양한 배경이 포함되어 있다. 또한, 어떤 사진들은 스마트폰 물건 자체가 아닌, 제품 상자를 찍은 사진이라 이를 잘 구별해내거나 학습하는 것이 중요하다.
<br/> <br> 데이터 출처 : https://www.kaggle.com/lasaljaywardena/mobile-smartphone-images-dataset
<br/> <br>
:chart_with_upwards_trend: 분석 목표 : 기본적인 이미지 분석 방법만을 사용하였기 때문에 애플과 삼성 두 회사에 대해서만 분류하였다.
<br>
