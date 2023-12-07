# Sit_to_Stand

Sit to Stand.ipynb 是自己跑可以使用的空白程式碼，只需要下載影片改最後一個cell的路徑即可<br>
Sit to Stand_run.ipynb 是我完整跑完程式碼的樣子（可以參考結果）


&emsp;<font size=6><table><tr><td bgcolor=#ffff99> 
Sit to Stand 2023/12/5-2023/12/7&ensp; </td></tr></table></font>
<br>
<h3>判讀程式碼目標：</h3>
<h4>透過MediaPipe分析每個影片中人體姿勢的變化：起立-坐立幾次</h4> 

使用 Mediapipe 的姿勢檢測模型結合 OpenCV 來處理影片數據，透過關鍵點「右側：12, 14, 16」來評判角度變化，以「170」、「130」分別為坐立、起立的角度臨界值，藉此判斷影片中起立-坐立次數的計數，並即時顯示在影片播放的視窗左上角。
<br>
<br>

Mediapipe 的骨架模型：
<br>
![](https://imgur.com/C98MGPb.png)<br>
<br>
Sit_to_stand 的關鍵點：右側：12, 14, 16/ 左側：11, 13, 15，此次程式碼取「右側」作為關鍵點偵測。
<br>

<h3>6.mov 影片讀取結果：</h3>
程式碼運行畫面<br>

![](https://imgur.com/HQbCSQ0.png)<br>
<br>
程式碼運行完結果<br>

![](https://imgur.com/kVSayuH.png)<br>
<br>

<h3>運行全部程式碼：</h3>
https://youtu.be/C9ue8Oc9A8M
<br>
<br>
<br>
