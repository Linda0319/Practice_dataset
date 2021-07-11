# Practice_dataset
- 這邊會放我平時練習的一些 open data，網路上通常都找得到厲害的大神作品，我這邊就是一個練習跟成長的軌跡
### 因為都會參考網路上的 code，自己做統整修改、測試跟註解，可能會有部分類似，不過若您覺得有冒犯到的，請務必聯繫我！！！

# 主要 CODE 
### MNIST_CNN 0~9手寫字辨識資料集，這個資料集本身品質非常好，分類的正確率都會達 99% 以上
- 資料集：28*28pixel的0~9手寫數字圖片，Test：10,000筆，Train：60,000筆
- 使用 keras 的 Sequential 建立 CNN 模型，使用 2 層卷積層、1 層池化層、relu 激勵函數、Adam 優化器，加上避免 overfitting 的 dropout
- 我做了比較清楚的資料集觀察，訓練時的 loss 與 accuracy 變化
- 最後模型評估的分類矩陣，觀察分類錯誤的資料以及 CNN 模型存檔

### Diabetes_DNN 印第安人糖尿病診斷預測，共768筆資料，9個欄位（8個變數、1個預測值），根據變數預測是否為糖尿病患者
- 欄位介紹
  - Pregnancies：懷孕次數
  - Glucose：口服葡萄糖耐量測試中2小時的血漿葡萄糖濃度
  - BloodPressure：舒張壓(毫米汞柱)
  - SkinThickness：三頭肌皮膚褶皺厚度(毫米)
  - Insulin：2小時血清胰島素(μIU /mL)
  - BMI：質量指數(體重(kg)/(身高(m))^ 2)
  - DiabetesPedigreeFunction：糖尿病家族史
  - Age：年齡
  - Outcome：類別1/0(全部768筆中有268筆是1，表示糖尿病患者有268位）



