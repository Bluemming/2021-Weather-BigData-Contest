# 2021 날씨 빅데이터 콘테스트 (참여 분야 - 민간협력형)

✔️ '비건웨더', 날씨에 따른 비건 친환경 제품 추천 플랫폼 앱

🔗 공모전 URL : https://bd.kma.go.kr/contest/main.do

**공모 배경**

기후 위기, 미세먼지 등 급변하는 환경 속에서 '윤리적 소비'에 대한 관심이 높아짐에 따라

'비건 화장품'의 시장가치가 증가하고 있습니다.

환경을 생각하는 가치 소비의 시대에 발맞춘 '비건 친환경 제품 추천 플랫폼'을 만들게 되었습니다.

**분석 기법**
1. 실시간 날씨 크롤링
2. 예측 데이터셋 생성
3. (모델1) 10만건당 건수 예측
4. (모델2) 구매 건수 예측
5. 비건 및 친환경 화장품 추천 시스템

✔️*2가지 모델 : 최종 예측인 '구매 건수'에 대한 설명 변수로 사용하기 위해 '10만건당 건수'에 대한 1차 예측 필요*


**사용 모델**
RandomForest Regression
- n_estimators : 100
- min_samples_split : 2

**활용 - 어플 서비스**
1. 고객 맞춤 회원 서비스
2. 날씨 기반 비건 제품 추천 서비스
3. 제품 상세 제공 페이지
4. 비건 스토어 리스트
