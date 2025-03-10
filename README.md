# AI 기반 지하수 수위 예측 시스템

> **기상 및 지하수 수위 데이터를 활용한 AI 기반 지하수 수위 예측 모델**  

## 프로젝트 개요  
- **프로젝트명:** AI 기반 지하수 수위 예측 시스템
- **목적:** **기상 및 지하수 수위 데이터를 활용하여 지하수 수위를 일주일 사전 예측**하는 AI 모델 개발  
- **개발 기간:** 2024년 8월 ~ 2024년 12월 (5개월)
- **활용 기술:** 시계열 분석, 상관 분석, 공간 분석, 기계 학습, 심층 신경망(DNN), LSTM  

🔹 **실시간 기상 데이터와 지하수 센서 데이터를 분석하여 수위 변동을 예측**  
🔹 **시계열 분석과 기계 학습 기법을 활용한 예측 모델 구축** 

---

## 주요 기능  
### 🔹 데이터 수집 및 전처리 
- **기상 예보 데이터, 실시간 기상 센서 측정값, AWS(자동기상관측시스템) 기상자료 활용**  
- **홍천 관청 총 6개 중 3개를 선정하여 테스트 시도**
- **여러 관정중 결측치가 가장 적은 관정을 선택하였으며 일주일 미만의 결측치들은 선형 보간법을 사용해서 처리**
- **홍천 (3, 4, 5) 관정의 다양한 기간(1~5년)의 데이터를 이용하여 학습**



### 🔹 수위 예측 모델 개발  
- **시계열 분석 모델**  
  - ARX(선형 모델)와 LSTM (Long Short-Term Memory) 중 LSTM을 담당
  - 학습 중 가장 성능이 잘나오는 파라미터 은닉층 3개, 뉴런 64개, drop 0.3, 활성함수 adam 등을 설정
  

### 🔹 예측 결과 시각화  
- **지하수 수위 예측 차트 및 지도 시각화**  
- **공구별 수위 예측 결과 제공**  
- **상관 분석 결과 조회 및 비교 가능**

### 결과 도출
![image](https://github.com/user-attachments/assets/58e81f5e-8e9d-44b6-8d0d-faa380f35d25)
![image](https://github.com/user-attachments/assets/83d87f74-8512-4f24-bff8-cf068ca9c2bd)
![image](https://github.com/user-attachments/assets/64003cfa-2c0b-490a-87f0-ca1e644dac06)

---

## 핵심 기술  
| 분야        | 사용 기술 |
|---------------|--------|
| **데이터 수집** | AWS 기상 데이터, 지하수 수위 데이터 |
| **AI 모델링**  | LSTM, ARX, DNN |
| **데이터 분석** | 시계열 분석, 공간 분석, 상관 분석 |
| **백엔드** | Python (Pytorch, Tensorflow, pandas) |
| **데이터베이스** | MySQL |

---


## 기대 효과    
- **공공 수자원 관리의 효율성 증가**  
- **지하수 생산/공급 계획 수집 활용**  
- **지하수 이상 변화 예측**

---

## 연구팀 소개 
| 이름       | 주요 역할 |
|---------------|--------|
|김 린 |	데이터 수집	|
|김주현 |	AI 모델 개발	|
|송경근 |	발표 및 기획	|
|이원찬 | AI 모델 개발 |

