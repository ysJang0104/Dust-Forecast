# 미세먼지 농도 예측 프로젝트 

### 📌 프로젝트 개요
- 공공데이터 API를 활용한 미세먼지 데이터 수집
- 머신러닝을 활용한 미세먼지 농도 예측
- FastAPI + Streamlit을 활용한 웹 대시보드
- 텔레그램/카카오톡 알림 시스템 구축

### 🛠 사용 기술
- Python, Pandas, Scikit-learn, TensorFlow
- FastAPI, Streamlit
- 공공데이터 API, 텔레그램 API

### 📊 데이터
- 미세먼지 농도 데이터 (공공데이터포털)
- 기상 데이터 (기상청 API)

### 📷 시각화 예시
(이미지 삽입)

### 🚀 실행 방법
```bash
# 필수 라이브러리 설치
pip install -r requirements.txt

# FastAPI 서버 실행
uvicorn app.main:app --reload

# Streamlit 실행
streamlit run app/dashboard.py
