# 🦠 COVID-19 생존 예측 모델 (Mexico)

이 프로젝트는 멕시코의 코로나19 환자 데이터를 기반으로, 환자의 사망 여부를 예측하는 AI 분류 모델을 개발한 것입니다.  
의료 자원 배분 및 조기 대응에 도움을 줄 수 있는 의사결정 지원 모델을 목표로 합니다.

---

## 📌 프로젝트 개요

- **데이터 출처**: [Kaggle - COVID-19 Mexico](https://www.kaggle.com/datasets)
- **목표**: 환자의 인적/건강 정보를 바탕으로 `사망 여부(생존/사망)` 예측
- **데이터 전처리**: 결측치 처리, 범주형 인코딩, 클래스 불균형 처리
- **사용한 알고리즘**:
  - XGBoost
  - SVM (서포트 벡터 머신)
  - 로지스틱 회귀 (비교용)

---

## ⚙️ 사용 기술

| 기술 | 설명 |
|------|------|
| Python | 전체 분석 및 모델링 언어 |
| Pandas, NumPy | 데이터 전처리 및 통계처리 |
| Seaborn, Matplotlib | 시각화 도구 |
| Scikit-learn | 머신러닝 모델 개발 |
| XGBoost | 고성능 분류기 |
| Jupyter Notebook | 분석 환경 |

---

## 📊 주요 변수 예시

- 나이 (Age)
- 성별 (Sex)
- 기저질환 유무 (Diabetes, Hypertension 등)
- 입원 유무 (Hospitalization)
- 호흡기 질환 (COPD)
- 사망 여부 (Target: 1 = 사망, 0 = 생존)

---

## ✅ 모델 성능

- 정확도(Accuracy): **약 85% 이상 (XGBoost 기준)**
- 주요 변수 중요도 분석 수행 (Feature Importance)
- 오버샘플링(SMOTE) 등 클래스 불균형 해결

---

## 📂 파일 구성

| 파일명 | 설명 |
|--------|------|
| `Mexico corona.ipynb` | 전체 데이터 분석 및 예측 모델 구현 notebook |
| `README.md` | 프로젝트 설명 파일 (현재 문서) |

---

## 📌 향후 개선 방향

- 딥러닝 기반 모델 적용 (예: MLP, DNN)
- SHAP 또는 LIME을 통한 모델 해석력 강화
- 멕시코 외 국가 데이터 비교 분석

---

## 🙋‍♂️ 작성자

**김현수**  
📘 Notion 포트폴리오: [https://www.notion.so/1f4f07bf279d80918d01ef6f82496da2](https://www.notion.so/1f4f07bf279d80918d01ef6f82496da2)  
📧 Email: mici1111@naver.com  
🔗 GitHub: [https://github.com/hyunsu3408](https://github.com/hyunsu3408)

