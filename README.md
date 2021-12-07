# team_B

Project Proposal 

Team member : 박신범, 박준녕

Team name : Env

1. Content

2. Title
=> 수질 자료를 활용한 한강 유역의 수질분석과 이에 따른 지점 분류 및 시각화

3. Motivation for topic selection and goal description

a) What are the final goal?
=> ‘물 환경정보시스템’에서 내려받은 한강 유역의 수질 자료(수온, DO, BOD, TN, TP 등)를 바탕으로 누락값, 결측값 등 각 항목에 대한 전처리를 시행한다. 그리고 각 수질 항목의 경향성을 파악하고 이에 따라 특성이 뚜렷한 지점을 몇 가지 class로 분류하고자 한다. 마지막으로 분류된 지점별로 시각화를 진행하려 한다.

b) How does it fit your interests.
=> 팀원 모두 환경공학부이기 때문에 수질 분야에 익숙하고 관심이 많아 정하게 되었다.

c) Describe possible evaluation criteria. Include the ways to show each member’s contribution.
박준녕 : 데이터 전처리 및 시각화 
박신범 : 전처리된 데이터를 통한 지점 분류 및 시각화

4. What type of data and processing methods are involved?

a) Type of data and variables.
수질 데이터 : 수온, DO, BOD, COD, SS, TN, TP, TOC
형식 : excel 형태

b) Type of algorithm, functions, methods.
=> 물 환경정보시스템과 서울특별시에서 제공하는 공공데이터를 사용하여 excel 파일 형식으로 다운받은 후, 이를 불러온다. 이후 결측치는 그 행을 제외하는 형식으로 데이터를 처리한 후, 수질 데이터를 바탕으로 수질 지수를 계산하는 함수를 만든다. 미리 설정해둔 기준으로 수질 지수에 따라 분류하고 이를 기본적으로 matplotlib 라이브러리를 사용해 시각화한다. 가능하다면 gis를 이용한 고도의 시각화까지 진행할 계획이다.

c) Goal of the project
=> 수질자료를 수질 지수로 변환하고 이를 통해 수질분석을 잘 수행하여 분류하게 된다면, 향후 한강 수질관리를 위한 기초자료로 활용될 수 있을 것이다.


5. References

물환경정보시스템 : http://water.nier.go.kr/web
서울특별시,  「서울특별시 한강 및 주요지천 수질 측정 자료」
이진효, 하현주, 이만호, 이목영, 김태호, 차윤경, 구자용.(2020).수질지수와 군집분석을 활용한 서울시 주요 하천 수질평가.대한환경공학회지,42(10),452-462.
