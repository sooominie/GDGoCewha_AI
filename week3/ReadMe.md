# 📝 3F 회고 — GDGoC AI 3주차  
**출처: GDGoC 7th AI 3주차 강의자료 — GDGoC_7th_AI_3주차**

---

# **Fact**

이번 주차 강의에서는 **머신러닝 모델의 성능 향상을 위한 핵심 개념**을 다루었다.

## **1. Overfitting vs Underfitting**
- 과소적합·과적합 개념 및 차이  
- **Bias–Variance Tradeoff 구조**  
- 해결 방법: **Regularization**, **Early Stopping**, **파라미터 조정**

## **2. Hyperparameter Tuning**
- 하이퍼파라미터의 개념과 역할  
- **Grid Search / Random Search / Bayesian Optimization 비교**

## **3. Cross-Validation**
- 데이터를 여러 Fold로 나누어 검증하는 방식  
- **K-Fold Cross Validation 구조**

## **4. 평가 지표**
- **분류**: Accuracy, Precision, Recall, F1 Score  
- **회귀**: MAE, MSE, RMSE, MAPE, R²

## **5. Ensemble 학습**
- **Bagging(Random Forest)**  
- **Boosting(XGBoost, LightGBM)**

## **6. Feature Engineering**
- 결측치 처리  
- 범주형 인코딩 (One-Hot / Label Encoding)  
- 스케일링 (StandardScaler, MinMaxScaler)

---

# **Feeling**

- 프로젝트에서 예측 성능이 불안정했던 이유가 **과적합·과소적합과 Bias–Variance 구조 때문**이라는 점을 다시 이해할 수 있었다.  
- 하이퍼파라미터 튜닝이 단순 성능 향상이 아니라 **일반화 능력을 확보하는 핵심 전략**이라는 점이 명확해졌다.  
- Ensemble 학습의 직관적 설명 덕분에 **약한 모델 여러 개가 강한 모델 하나가 되는 구조**를 명확하게 이해했다.

---

# **Finding**

## **1. 전처리·검증·튜닝의 중요성 재확인**
모델 종류보다  
**데이터 전처리 → 교차검증 → 하이퍼파라미터 튜닝**  
이 전체 파이프라인이 성능에 더 중요한 요소임을 배웠다.

## **2. Overfitting을 해결하는 구조적 접근 습득**
- Regularization  
- Dropout  
- Early Stopping  
- 데이터 분할 전략  
- 모델 복잡도 제어  

이 방법들이 모두 **과적합 방지 전략**이라는 점을 명확히 이해했다.

