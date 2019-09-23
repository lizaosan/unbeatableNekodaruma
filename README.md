# 打不倒的貓貓不倒翁 Unbeatable Nekodaruma
## 簡介
- DEMO 作品
- javascript / socket.io
- 請以手機進入[Heroku](https://ancient-everglades-84501.herokuapp.com/ "Unbeatable Nekodaruma")

## 操作與效果
- 旋轉手機嘗試打倒貓貓不倒翁
- 檢測手機陀螺儀，預期上貓貓不倒翁的圖片會一直依據 Beta 與 Gamma 值旋轉
- 伺服端與用戶端有 socket.on 雙向收發事件，所以可以閱覽桌機網頁，用手機實現遠端操控

## 注意事項
- 伺服端沒有路由，所以目前若同時有多人玩貓貓不倒翁，**貓貓不倒翁會抽筋**

## 參考資源
- [js調用手機陀螺儀API與原理](https://blog.csdn.net/yangxun983323204/article/details/79208342 "deviceorientation")
- [使用 socket.io 製作網頁聊天應用](https://www.bilibili.com/video/av27804509/ "socket.io")