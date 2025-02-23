# Bank-Customer-Churn-Prediction
本專案使用 TensorFlow Keras 進行深度學習建模，並透過 Pandas 和 Seaborn 進行資料預處理與視覺化分析。資料庫來源為公開的 Banking Customer Churn Prediction Dataset 數據集，並透過 Scikit-learn 進行資料分割、特徵工程以及模型評估。
包含了探索性資料分析（EDA）、敘述性統計、特徵工程和深度學習模型建置等步驟。模型訓練過程中運用EarlyStopping 避免過擬合，並使用混淆矩陣與分類報告進行效能評估。整個流程強調資料分佈分析、變數關聯性檢測及偏態修正，以提升預測精準度。

此專案為紀錄自己的資料科學學習歷程，從數據探索到模型應用，深入理解銀行客戶流失問題，並實踐機器學習在商業場景中的應用。

資料庫參考自：https://www.kaggle.com/datasets/saurabhbadole/bank-customer-churn-prediction-dataset/data

程式碼參考自：https://www.kaggle.com/code/danishmubashar/88-bank-customer-churn-prediction-ann

# 資料說明(Features)
RowNumber: 資料集中每筆資料的序號
CustomerId: 客戶的唯一識別碼
Surname: 暱稱
CreditScore: 信用評分
Geography: 地理位置(如：國家或地區)
Gender: 性別
Age: 年齡
Tenure: 客戶在銀行的年資(以年為單位)
Balance: 帳戶餘額
NumOfProducts: 擁有的銀行產品數量
HasCrCard: 是否擁有信用卡(binary)
IsActiveMember: 是否為活耀會員(binary)
EstimatedSalary: 預估薪資
Exited: 是否已流失(離開銀行) (binary)
