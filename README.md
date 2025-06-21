# SNS_Collab
---

## 📁 스프레드 파일 위치

| 파일명                              | 설명                                         |
| ------------------------------------ | -------------------------------------------- |
| `yes24_bestseller_full`          | https://docs.google.com/spreadsheets/d/1K0IhHBsc7o3NoP9yjvaG-vW1Y6bAxmjYrpoAZLqsjs8/edit?gid=0#gid=0 |
| `yes24_bestseller_one_page`      | https://docs.google.com/spreadsheets/d/1a8Q1TuqoXFlXCjkHkV5HfcX5pax4DCEs0beAV9Lvwmo/edit?gid=0#gid=0 |

---

## 📚 YES24 베스트셀러 크롤링 프로젝트

본 프로젝트는 YES24 웹사이트의 베스트셀러 전체 목록을 자동으로 수집하고,  
수집된 데이터를 스프레드시트로 보여주는 구현한 코드 입니다.

---

## 📌 프로젝트 개요

- **목표**: YES24 베스트셀러 순위 정보를 페이지별로 수집하여 정리
- **크롤링 대상**:
    - YES24 베스트셀러
- **수집 항목**:
    - 순위
    - 제목
    - 저자
    - 출판사
    - 가격
- **크롤링 크기**:
    - 한페이지 분량
    - 전체 페이지 분량

---

## 🛠️ 사용 기술

- Python
- BeautifulSoup(bs4)
- Pandas
- ChromeDriver 	


---

## 📁 파일 구성

| 파일명                              | 설명                                         |
| ------------------------------------ | -------------------------------------------- |
| `yes24_bestseller_full.xlsx`          | 크롤링한 전체 베스트셀러 정보 XLSX 파일(스프레드시트)  |
| `yes24_bestseller_one_page.xlsx`      | 한 페이지만 크롤링한 예시 XLSX 파일(스프레드시트)           |
| `yes24_bestseller_full.csv`          | 크롤링한 전체 베스트셀러 정보 csv 파일(스프레드시트, 온라인 뷰어 파일, 다운로드시 글자 깨짐)  |
| `yes24_bestseller_one_page.csv`      | 한 페이지만 크롤링한 예시 csv 파일(스프레드시트, 온라인 뷰어 파일, 다운로드시 글자 깨짐)           |
| `yes24베스트셀러_전체목록4.ipynb`    | 크롤링 코드가 포함된 Jupyter Notebook 파일   |
| `yes24베스트셀러_전체목록4.py`       | 크롤링 코드 Python 파일    (py로 변환)       |

---
