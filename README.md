# MarketAlert

MarketAlert 是一個自動提醒金融數據與股市開盤狀況的Discord機器人。主要功能包括在有金融數據公佈（例如：CPI）的前10分鐘和前30分鐘提醒，以及每天臺灣時間12:00公佈隔天證券不開盤的國家。
  
![MarketAlert](https://media.discordapp.net/attachments/1174561473570291792/1174561541505437706/coderyo.com_money.jpg?ex=65fbb2ad&is=65e93dad&hm=15643d4c5245cf0d230de49c2f9623cb9131fd27a2ef385bb11f7c01939fbf83&=&format=webp&width=250&height=250)

## 主要功能

1. 在有金融數據公佈（例如：CPI）的前10分鐘和前30分鐘在Discord頻道上提醒
2. 每天臺灣時間12:00公佈隔天證券不開盤的國家，例如5/1勞動節臺灣日本等沒開盤就要提醒「明日不開盤：臺灣、日本」
3. 24小時運作，無需指令設置

## 程式架構

- main.py: 主程式，負責處理相關金融資訊
- bot.py: Discord機器人，將處理後的資訊發佈至Discord頻道
- config.json: 配置檔案，存放Discord機器人的Token等配置信息
