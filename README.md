욕설 및 폭언과 같은 데이터들은 딥러닝 모델의 성능을 저하할 수 있으며, 더 나아가 윤리적인 문제가 발생할 수 있다. 또한 윤리적 문제 뿐만 아니라 외국인 입장에서 욕설을 판단해줄 수 있는 서비스가 필요함을 느꼈다. 

기존의 욕설 필터링 프로젝트와 다른 점은 GRU 모델과 kobert 모델을 함께 사용한다는 점과, 웹 크롤링 코드를 추가하여 해당 모델이 학습에 필요한 데이터를 자동적으로 추가해주는 기능이 있다는 것이다. 신조어가 자주 나타나는 요즘, 구글사의 bert 라이브러리와 직접적인 성격이 강한 크롤링을 함께 사용한다면 다양한 단어에 대한 분석이 더욱 원활해질 것이라고 판단하였다.

**동국대학교 공개소프트웨어 소속 팀 '다국적 기업'에서 프로젝트를 진행하였습니다**
yeonsik님의 nlp-filter-out-main/SKTBrain님의 kobert 프로젝트를 기반으로 하였습니다
