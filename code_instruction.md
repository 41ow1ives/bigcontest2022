READ_ME
--------
코드 순서
--------
0-1. VISITJEJU_CRAWLING.ipynb : 비짓제주 크롤링 코드
0-2. VEGANMAP_CRAWLING.ipynb: 제주비건지도 크롤링 코드
0-3. TRIPADVISER_MYREALTRIP_CRAWLING.ipynb : 트립어드바이저/마이리얼트립 숙박정보 크롤링 코드
0-4. RENTCAR_CRAWLING.ipynb: 올댓여행렌터카/엔젤렌터카 크롤링 코드
0-5. NAVERMAP_CRAWLING.ipynb:네이버맵 크롤링코드 (데이터 보완을 위해 추가적으로 전처리 데이터 검색 크롤링 코드- 전처리 과정 중 나오는 데이터셋 사용하여 코드와 함께 data 폴더에 정리)

1-0. CO2_VISITJEJULOG_PREPROCESSING.ipynb :  지번주소 단위 온실가스 배출량 데이터와 비짓제주 조회데이터 전처리 코드로 향후 모든 데이터셋 전처리에서 활용할 예정

2-1. ACCOMMODATION_PREPROCESSING.ipynb : 숙박데이터셋 전처리 코드
2-2. F&B_PREPROCESSING.ipynb : F&B데이터셋 전처리 코드
2-3. TOUR_PREPROCESSING.ipynb : 관광지 데이터셋 전처리 코드 
2-4. SHOP_PREPROCESSING.ipynb : 쇼핑 데이터셋 전처리 코드
2-5. TRAFFIC_PREPROCESSING.ipynb : 교통 데이터셋 전처리 코드

3-1. F&B_RECOMMEND_GRADE.ipynb : F&B 추천점수 산정 코드
3-2 JEJU_ZONE_DIVISION.ipynb : 클러스터링 통해 제주 구역 세분화 코드
3-3 TOUR_SIMILARITY_CALCULATION.ipynb : 관광지 벡터 생성 및 유사도 계산 코드
3-4 TOUR_RECOMMEND_GRADE.ipynb : 관광지 추천점수 산정 및 구역별 여행 추천지 선정 단계 코드


----------
사용한 외부 데이터

(1)  제주도청 관광숙박업 및 도내 숙박업소 공공데이터 
출처: 공공데이터 포털 https://www.jeju.go.kr/news/news/data.htm?act=view&seq=1382795
데이터명:  
5. 숙박시설 현황 세부내역(22.7.31.기준)_도수합.xlsx.
 5-1. 숙박시설(농어촌민박) 현황 세부내역(22.7.31.기준)_도수합.xlsx

(2)  제주바람지도/제주푸른컵지도 크롤링 데이터
출처 : 제주특별자치도지속가능발전협의회 제주푸른컵 https://pruncup.com/faq/
데이터명:
제주바람지도.csv, 
제주푸른컵지도.csv

(3) 제주 비건 지도 크롤링 데이터
출처: 사단법인 생명환경권행동 제주비건 http://www.jejuvegan.com/vegan_map
데이터명: 제주비건식당크롤링.csv

(4) 제주도장소(POI)데이터 
출처: 공공데이터포털 https://www.data.go.kr/data/15004770/fileData.do
파일명 :제주특별자치도_제주도장소(POI)데이터_20151231.csv

(5) 신한카드 올댓여행 렌트카 사이트/ 엔젤렌트카 올댓여행 렌트카 사이트 크롤링 데이터
출처: 
신한카드 올댓여행 렌트카  https://allthat.travelbonus.co.kr/Main.asp?BIGDIV_VAL=RentCar#tabRentcar01,
엔젤렌트카 올댓여행 렌트카 https://jejuangelcar.com/tour.php?p=realcar-list
파일명 : ALLTHAT_제주렌터카크롤링.csv


(6) 비짓제주 크롤링 데이터 
출처 : 비짓제주 https://www.visitjeju.net/kr/#
파일명: 
VISITJEJU_관광지정보크롤링.csv,
VISITJEJU_쇼핑정보크롤링.csv,
VISITJEJU_숙박정보크롤링.csv

(7) 마이리얼트립 크롤링 데이터 
출처 : 마이리얼트립 https://www.myrealtrip.com/
파일명: MYREALTRIP_숙소크롤링.csv

(8) 트립어드바이저 크롤링 데이터 
출처 : 트립어드바이저 https://www.tripadvisor.co.kr/
파일명: TRIPADVISOR_숙소크롤링.csv


(9) 네이버맵 크롤링 데이터
출처: NAVER MAP  https://map.naver.com/v5
파일명: 
 F&B데이터_네이버크롤링.csv,
관광지데이터_네이버크롤링.csv,
관광지데이터_네이버크롤링_835.csv,
쇼핑데이터_네이버크롤링.csv
