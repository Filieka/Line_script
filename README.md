# Line_script

### 1. 開啟[LINE Notify](https://notify-bot.line.me/zh_TW/)點選右上角登入
![螢幕擷取畫面 2023-12-13 143521](https://github.com/Filieka/Line_script/assets/144932126/53f9b5d6-0327-4f02-ab10-d1112fbc1ddf)
### 2.開啟個人頁面
![螢幕擷取畫面 2023-12-13 144040](https://github.com/Filieka/Line_script/assets/144932126/f0fbaf72-d811-4dd2-80ed-cee4853da461)
### 3.進入後會看到已連結的群組，接著向下找到發行存取權杖
![螢幕擷取畫面 2023-12-13 144356](https://github.com/Filieka/Line_script/assets/144932126/34f12b12-06f8-4b68-af45-77896ac66729)
### 4.在下方選取要連結的群組或個人，在上方輸入傳送訊息時要顯示的名稱，完成後按下發行
![螢幕擷取畫面 2023-12-13 144906](https://github.com/Filieka/Line_script/assets/144932126/1043b948-1097-43ea-9ede-30474c552882)
### 5.複製權杖並謹慎保存
![螢幕擷取畫面 2023-12-13 145500](https://github.com/Filieka/Line_script/assets/144932126/64efd396-44dc-42a2-81bc-08da6fb5e7cc)
### 6.開啟一個試算表，選擇擴充功能中的APP Script
![螢幕擷取畫面 2023-12-13 150416](https://github.com/Filieka/Line_script/assets/144932126/ca570d30-d64f-4166-950e-ccc2f3fd488e)
### 7.貼上從[code](https://github.com/Filieka/Line_script/blob/main/code)複製的所有程式碼
![螢幕擷取畫面 2023-12-13 150743](https://github.com/Filieka/Line_script/assets/144932126/1fe079d8-6ebf-4bfd-88fc-cfd5e379e2cc)
### 8.找到"Your Token"，將剛剛得到的權杖貼上
![螢幕擷取畫面 2023-12-13 150908](https://github.com/Filieka/Line_script/assets/144932126/a6c32b8c-b9bc-41ac-9ed7-d3f25f84c419)
### 9.回到試算表複製網址的這一段，貼到程式碼中的'sheet id'，下方的名稱可以更改，改完之後到程式碼中的'sheet name'打上一樣的名稱
![螢幕擷取畫面 2023-12-13 1524251](https://github.com/Filieka/Line_script/assets/144932126/f0e05951-dcb2-4d15-94d8-79cb2d522ccf)
![螢幕擷取畫面 2023-12-13 152425](https://github.com/Filieka/Line_script/assets/144932126/5e1a3610-9918-41f1-a003-e8460d0e9aa6)
### 10.將試算表的第一列打上想要的標題，不一定要每個都打，可以根據自己想要的規律選擇需要的數據，程式提供，年，月，日，星期，時間(***注意!月，日，時間的格式必須保持位數固定，建議利用工具列中的`格式`->`數值`->`自訂數字格式`輸入所需位數的0，例如在時間欄位公式就是0000，日跟月則是00***
![螢幕擷取畫面 2023-12-13 154720](https://github.com/Filieka/Line_script/assets/144932126/7c75e20d-76bd-4877-bf86-c3b68e5c8878)
### 11.回到程式碼中將所需的時間迴圈及資料範圍進行修改，以下是需要修改的範圍
![螢幕擷取畫面 2023-12-13 154830](https://github.com/Filieka/Line_script/assets/144932126/983aa946-8979-43f7-8535-027317565374)
### 12.照著下面的說明修改，修改完按下ctrl+s儲存
![未命名繪圖](https://github.com/Filieka/Line_script/assets/144932126/8ed13e15-57ba-4e0d-b777-80c2a3fdf848)
### 13.從左邊選擇觸發條件
![螢幕擷取畫面 2023-12-13 230456](https://github.com/Filieka/Line_script/assets/144932126/3c11894b-e95e-495a-be71-5f36feaa096b)
### 14.`部署`->`新增部署作業`
![螢幕擷取畫面 2023-12-13 232516](https://github.com/Filieka/Line_script/assets/144932126/bdc574c1-8a03-4d06-8100-9c7d1f158b84)
### 15.`選取類型`->`網頁應用程式`->`部署`
![螢幕擷取畫面 2023-12-13 233012](https://github.com/Filieka/Line_script/assets/144932126/a6b45a8e-9c86-482d-a56e-7db7e15867d4)
### 16.`新增部署條件`->執行功能選擇`doPost1`->應執行的部署作業選擇`上端`->活動來源選擇`時間驅動`->觸發條件鉉則使用的最小時間單位->`儲存`
![螢幕擷取畫面 2023-12-13 234241](https://github.com/Filieka/Line_script/assets/144932126/7e6b2917-9b02-455d-93f5-bdf3277a8b38)
### 17.回到試算表輸入時間及提醒內容就完成了
![螢幕擷取畫面 2023-12-13 235009](https://github.com/Filieka/Line_script/assets/144932126/5566c7d9-e10f-4f9a-9077-36e6998c9a87)
