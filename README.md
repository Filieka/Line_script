# Line_script

###1. 開啟[LINE Notify](https://notify-bot.line.me/zh_TW/)點選右上角登入
![螢幕擷取畫面 2023-12-13 143521](https://github.com/Filieka/Line_script/assets/144932126/53f9b5d6-0327-4f02-ab10-d1112fbc1ddf)
###2.開啟個人頁面
![螢幕擷取畫面 2023-12-13 144040](https://github.com/Filieka/Line_script/assets/144932126/5c4470d8-838e-4ac9-bdc1-93287a68b24c)
###3.進入後會看到已連結的群組，接著向下找到發行存取權杖
![螢幕擷取畫面 2023-12-13 144342](https://github.com/Filieka/Line_script/assets/144932126/3fe32edc-f61f-4593-9a46-34c41a4daf3e)
![螢幕擷取畫面 2023-12-13 144356](https://github.com/Filieka/Line_script/assets/144932126/3b50225e-d035-49ca-9fab-b1b10affc623)
###4.在下方選取要連結的群組或個人，在上方輸入傳送訊息時要顯示的名稱，完成後按下發行
![螢幕擷取畫面 2023-12-13 144906](https://github.com/Filieka/Line_script/assets/144932126/14a106d5-9ef0-4da5-b870-2c4102053322)
###5.複製權杖並謹慎保存
![螢幕擷取畫面 2023-12-13 145500](https://github.com/Filieka/Line_script/assets/144932126/df4b6b59-c91b-4b61-818e-2920f0f923b0)
###6.開啟一個試算表，選擇擴充功能中的APP Script
![螢幕擷取畫面 2023-12-13 150416](https://github.com/Filieka/Line_script/assets/144932126/e3bcaea2-a181-4ccf-ad0a-dfb0af883991)
###7.貼上從[code](https://github.com/Filieka/Line_script/blob/main/code)複製的所有程式碼
![螢幕擷取畫面 2023-12-13 150743](https://github.com/Filieka/Line_script/assets/144932126/1fe079d8-6ebf-4bfd-88fc-cfd5e379e2cc)
###8.找到"Your Token"，將剛剛得到的權杖貼上
![螢幕擷取畫面 2023-12-13 150743](https://github.com/Filieka/Line_script/assets/144932126/1aaff29b-e6ba-415b-926b-00c36ba10fba)
###9.回到試算表複製網址的這一段，貼到程式碼中的'sheet id'，下方的名稱可以更改，改完之後到程式碼中的'sheet name'打上一樣的名稱
![螢幕擷取畫面 2023-12-13 152425](https://github.com/Filieka/Line_script/assets/144932126/6570a793-5395-4cac-bb96-afb15571c5fb)
###10.將試算表的第一列打上想要的標題，不一定要每個都打，可以根據自己想要的規律選擇需要的數據，程式提供，年，月，日，星期，時間(***注意!月，日，時間的格式必須保持位數固定，建議利用工具列中的"格式"->"數值"->"自訂數字格式"輸入所需位數的0，例如在時間欄位公式就是0000，日跟月則是00***
![螢幕擷取畫面 2023-12-13 153212](https://github.com/Filieka/Line_script/assets/144932126/7148755a-3479-4fd3-80de-4cf7b4e8f253)
###11.回到程式碼中將所需的時間迴圈及資料範圍進行修改
