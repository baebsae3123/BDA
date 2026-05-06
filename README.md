#빅데이터분석프로그래밍

1일차 패키지 사용 matplotlib , seaborn 

시험예상
<img width="1170" height="689" alt="화면 캡처 2026-04-08 140531" src="https://github.com/user-attachments/assets/a5515b77-8a74-406c-8540-5567ebd13cf9" />

## 라이브러리
numpy 👉 숫자 계산용  라이브러리 배열(Array) 기반

matplotlib 👉 그래프 그리는 기본 라이브러리 가장 기본적인 시각화 도구

matplotlib.pyplpot 👉 matplotlib 안에 있는 그래프 전용 기능

seaborn 👉 더 예쁘고 쉽게 그래프 그리는 라이브러리

pandas 👉 데이터 분석용 (엑셀 느낌) 표 형태 데이터 처리

datetime 👉 날짜 출력

## 그림을선명하게 하는것
%config lnlineBackend.figure_format = 'retina'
## 한국어 설치
!pip install koreanize-matplotlib

## matplotlib 기능
plt.title('데이터시각화')
plt.plot([10,5,20,30])
plt.show()


## pandas
pop = pd.read_csv(("popmonth csv" encoding=encoding='cp949 index_col=0 thousands=pop)👉 데이터를 읽어오는 기능

pop.columns = ['총인구수','세대수','세대당인구','남자인구수','여자인구수','남여비율'] 👉열이름을 새로 정하는거

pop.head() 👉 데이터프레임의 상위 5개 행을 보여줌

pop.index 👉행이름을 새로 정하는거

pop.index[i].split()[0] 👉 나눠서 리스트 형태로 만들어주는거

df.copy() 👉 데이터를 “복사해서 새로 만드는 것”

## seaborn





## 용어 정리
cp949 윈도우에서 많이 쓰던 한글인코딩 방식
index_col=0 첫번쨰 열을 인덱스로 쓰겠다
thousands=pop 숫자에서 천 단위 구분기호


<img width="466" height="174" alt="image" src="https://github.com/user-attachments/assets/24f5d3da-642d-4fb9-973d-a4eaf92a0899" />

# 기말고사

# 10주차 - 9장 49페이지

<img width="784" height="433" alt="image" src="https://github.com/user-attachments/assets/51d724d7-7ba9-4ac7-91a2-bc2e55d989fd" />

COL= 부분 시험 나온다함
