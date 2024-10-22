# labeling-tool
易於上手的標註工具:
<br>
<br>收集好自己的圖片之後，就可以在每張圖片中標記自己的目標了。LabelImg是標記圖像的工具，很容易上手，GitHub頁面上也有關於如何安裝和使用它的說明。
<br>
<br>在這裡附上github標註工具的的連結 [LabelImg](https://github.com/tzutalin/labelImg "labelImg") .
<br>或者你可以下載我附的zip檔案，解壓縮此檔案之後，進行安裝(for windows)即可。
<br>
# 使用教學
<br>在CMD執行程式碼:```git clone https://github.com/tzutalin/labelImg.git```
<br>2.使用window+Anaconda執行以下命令:
<br>  ```activate <環境名稱>```
<br>  ```cd <labelImg目標資料夾>```
<br>  ```conda install pyqt=5```
<br>  ```pyrcc5 -o libs/resources.py resources.qrc```
<br>3.在目標資料夾執行:```python labelImg.py```
# 使用方法
<br>打開labelImg ，並點選「Open」開啟圖檔
<br>![step1](https://github.com/yuyangdanny/labeling-tool/blob/master/images/open.PNG)
<br>對著圖片按滑鼠右鍵(或是案快捷鍵W)，開始標註
<br>![step2](https://github.com/yuyangdanny/labeling-tool/blob/master/images/labeling.PNG)
<br>並將所有的句子標註，只要是中文字就標記成”text”
<br>![step3](https://github.com/yuyangdanny/labeling-tool/blob/master/images/text.PNG)
<br>將照片的標註儲存在同一個資料內
<br>![step4](https://github.com/yuyangdanny/labeling-tool/blob/master/images/xml.PNG)
<br>LabelImg保存一個.xml文件，其中包含每個圖像的標籤數據。這些.xml文件將用於生成TFRecords，可用於訓練圖像。
