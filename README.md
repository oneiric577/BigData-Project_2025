# BigData-Project

## Rental_Fraud_Local | 전국 전세 사기

## 전국 각지의 전세사기 비율은 어느 정도 일까?

## 주제 선정
2022년 12월 경 대한민국을 떠들썩하게 한 사건, '2022년 빌라왕 사태'가 있다.
이 사건은 악질적인 임대인, 일명 '빌라왕'들에 의해 수백 세대의 세입자들이 전세 보증금을
돌려받지 못하여 대규모 피해를 보게 된 사건이다. 이들의 행위는 조직적으로 이루어진
전세사기 범죄라는 정황이 드러났으며 이들 중 일부는 사망하여 보증금을 돌려받을 길이
사라진 피해자들도 존재한다. 하지만 여전히 신원확인이 되지 않은 여타 빌라왕들도 아직 활개치고 있으며
그외의 악질적 임대인에게 당한 전세사기 피해자들은 2025년인 현재까지도 계속 발생하고 있다.
그리하여 전국적으로 전세사기 피해의 비율이 어느정도인지 알아보기 위해 주제로 선정하게 되었다.

## 데이터 수집
수집기간 : 2025-08-25 ~ 2025-09-01

수집방법 : 공공데이터포털

## 사용 데이터
1. [부산광역시_전세사기 발생건수_20250331.csv](https://www.data.go.kr/data/15143009/fileData.do)
+ -> [busan.csv](https://github.com/oneiric577/BigData-Project/blob/main/busan.csv)로 파일 이름 변경
2. [광주광역시_전세사기피해자 결정 현황_20250331.csv](https://www.data.go.kr/data/15142922/fileData.do)
+ -> [gwangju.csv](https://github.com/oneiric577/BigData-Project/blob/main/gwangju.csv)로 파일 이름 변경
3. [울산광역시_구군별 전세사기피해자 결정건수_20250228.csv](https://www.data.go.kr/data/15142936/fileData.do)
+ -> [ulsan.csv](https://github.com/oneiric577/BigData-Project/blob/main/incheon.csv)로 파일 이름 변경
4. [인천광역시_연도별 연령별 전세사기 관련 통계_20250327.csv](https://www.data.go.kr/data/15142802/fileData.do)
+ -> [incheon.csv](https://github.com/oneiric577/BigData-Project/blob/main/ulsan.csv)로 파일 이름 변경

## 사용된 전처리 방법
1. 원소 값 재설정
2. 불필요 데이터 drop
3. 열 이름 재설정
4. stack 함수를 사용해 자료 변형

## 사용된 시각화 방법
+ -> sns.barplot

## 시각화 결과
* 인천
<img width="1126" height="481" alt="Image" src="https://github.com/user-attachments/assets/8400b6f5-ebc8-4d3c-b355-b0c12cb7bf6e" />

* 부산
<img width="1140" height="485" alt="Image" src="https://github.com/user-attachments/assets/68f51d83-8863-46ad-bf09-760d04d6b9b2" />

* 광주
<img width="1148" height="488" alt="Image" src="https://github.com/user-attachments/assets/f3659117-e573-4f83-abf3-f840e4b54875" />

* 울산
<img width="1140" height="498" alt="Image" src="https://github.com/user-attachments/assets/9adad6f0-6bae-42c1-beda-2a1287380164" />

* 전국
<img width="1046" height="480" alt="Image" src="https://github.com/user-attachments/assets/3b25c32c-2a78-4b31-a74b-5180c9ebdff9" />

## 시각화 결론(예측)
* 인천 전세사기 미래 예측(회귀_그래프)
<img width="728" height="473" alt="Image" src="https://github.com/user-attachments/assets/ae646b98-7d8f-4e09-a411-d8f5765cc344" />

## 보고서
+ -> [전국 각지의 전세사기 비율은 어느 정도 일까?]()
