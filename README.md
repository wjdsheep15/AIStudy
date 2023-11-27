# AIStudy and Machin Learning
데이터 전저리 하는 방식, 전처리한 데이터로 머신러닝 돌리기

## 공부 환경
Google Colaboratory 사용

언어 : Python

OS : Window11

공부 기간 : 2023년 9월 부터~~

# 데이터 전처리 방법
* 사용 라이브러리

  * matplotlib
  * seaborn
  * pandas
  * beautifulSoup
 
 
 
 1. plot.ipynb

    matplotlib 라이브러리 사용
      * 주어진 데이터를 이용하여 다양한 형태의 그래프를 그리는 함수
      * 데이터를 그래프로 표현하면 데이터의 분포나 항목 간의 상관관계를 쉽게 파악
      * 선 그래프 : plot()
        * plot( x값, y값, 선스타일문자열, marker='마커기호', label='그래프이름') y값은 필수이고 나머지는 생략가능
      * 산점도 그래프 : scatter()
        *  scatter( x값, y값, c='색 문자' 혹은 '색깔 문자열', marker='마커기호', label='그래프이름' , c, marker, label은 생략 가능
      * 막대 그래프 : bar()/barh()
        * bar( x값, y값, color='색 문자' 혹은 '색깔 문자열') 범주별 데이터를 나타내는 세로 막대 그래프 생성
        * barh( x값, y값, color='색 문자' 혹은 '색깔 문자열') 범주별 데이터를 나타내는 가로 막대 그래프 생성
      * 빈도 그래프(히스토그램) : hist()
        * hist( x값, bins = x값 구간 개수, color='색 문자' 혹은 '색깔 문자열', align='left'/'mid'/'right' 중 하나)

2. Seaborn.ipynb

    matplotlib, seaborn 라이브러리 사용
      * matplotlib을 바탕으로 통계 그래프를 그릴 수 있도록 기능을 추가한 라이브러
      * 판다스의 데이터프레임을 대상으로 그래프를 그리기 때문에 데이터프레임을 다양ㅇ한 그래프로 나타내기가 편함


3. pandas.ipynb
    pandas, beautifulSoup 라이브러리 사용


   pandas 라이브러리
   * pandas는 데이터를 불러오고, 전처리에 사용된다.
   * CSV 파일, 덱스트 파일, 엑셀 파일, SQL 데이터베이스, HDF5 포맷 등 다양한 외부 리소스에 데이타를 읽고 쓸 수 있는 기능 제공
   * 세 가지의 자료구조를 지원한다.
     * 1차원 자료구조인 Series
     * 2차원 자료구조인 DataFrame
     * 3차원 자료구조인 Panel
    
   * Pandas의 데이터형
     * Objects : 문자 또는 문자열 형
     * Int64 : 정수형
     * float64 : 실수
    
   beautifulSoup 라이브러리

   * HTML과 XML 파일에서 데이터를 읽어내준다 
  
