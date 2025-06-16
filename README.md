# 🎬 영화진흥위원회(KOBIS) API 기반 박스오피스 데이터 수집 프로젝트

## 📌 과제 소개
이 프로젝트는 ai 응용 빅데이터프로그램1 기말과제로, 영화진흥위원회(KOBIS) 오픈 API를 활용하여 일간 박스오피스 데이터를 수집하고 분석하는 파이썬 기반 프로그램입니다.

Python의 requests, pandas 라이브러리를 활용하여 데이터를 수집하고, 분석 결과를 `.xlsx` 파일로 저장합니다.

---

## 🔧 사용 기술
- Python (Colab)
- requests
- pandas
- JSON API 응답 처리

---

## 🔗 API 정보
- API 제공: [영화진흥위원회(KOBIS)](http://www.kobis.or.kr/kobisopenapi/homepg/main/main.do)
- 사용 API: `searchDailyBoxOfficeList.json`
- 주요 파라미터:
  - `key`: 개인 인증키
  - `targetDt`: 조회일자 (YYYYMMDD 형식, 하루 전 데이터 사용)

---

## 📂 실행 결과 예시

| 순위 | 영화명     | 개봉일     | 당일 관객수 | 누적 관객수 |
|------|------------|------------|--------------|--------------|
| 1    | 범죄도시4  | 2024-05-15 | 124,000       | 3,550,000     |
| 2    | 악마와의 약속 | 2024-06-14 | 95,300        | 1,220,000     |

👉 엑셀 파일로 저장: `박스오피스_오늘.xlsx`
🔗 실행하기 (Google Colab)  
[Colab에서 보기](https://colab.research.google.com/drive/1IMQROqa-vVFC3wfVF4q-km6YWBnXdo0n)

---

## 📁 파일 구성
| 파일명 | 설명 |
|--------|------|
| `kobis_boxoffice_final.ipynb` | 코드 및 실행 결과가 담긴 Colab 노트북 |
| `박스오피스_오늘.xlsx` | 분석된 박스오피스 표 |
| `README.md` | 프로젝트 설명서 |

---

## 📈 배운 점
- API 키 기반으로 안정적인 데이터 수집이 가능하다는 점을 이해함
- JSON 파싱을 통해 실시간 데이터를 수집, 정제하는 과정을 익힘
- 공공데이터 API를 활용한 실무적 활용법을 체득함

---

## 👤 만든이
- 이름: 곽라온
- 학번: 2024581003
- 과목명: ai응용빅데이터프로그램1
