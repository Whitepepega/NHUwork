# 手寫數字影像辨識(Image recognition), 南華大學
訓練模型辨識手寫數字
# 目錄
-使用工具\
-實作方法\
-程式碼修改項目\
-參考資料\
-補充
# 使用工具
1.Google Colabratory\
2.Google 雲端硬碟\
3.小畫家
# 實作方法
在Google Colab上利用KNN演算法進行機器學習，訓練手寫數字辨識模型。將小畫家畫出的數字圖片上傳到雲端硬碟，再將圖片投入模型進行辨識。
# 程式碼修改項目
1.視訊影像檔改為雲端硬碟路徑\
2.影像辨識迴圈改為執行1次\
3.圖像擷取範圍改為整張圖片
# 參考資料
手寫影像辨識Code:https://ithelp.ithome.com.tw/articles/10307704 \
MNIST 手寫字符數據集:https://keras.io/zh/datasets/#mnist
# 補充
由於訓練數據量少，訓練時間和測試時間總共不超過3分鐘。即便預測準確度高達0.9，實際測試20張得出結果還是只有約3成正確率。主要有得出幾項提升辨識成功率的因素，例如:筆畫粗、字型工整、與其他數字較無相似等。
