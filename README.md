這是一個簡單的英語家教聊天應用程式，使用 HTML、CSS 和 JavaScript 建立。

結構:
- 使用 Bootstrap 進行樣式設計。
- 包含一個聊天框和一個輸入框，使用者可以在輸入框中輸入訊息並點擊 "Send" 按鈕發送訊息。

樣式:
- #chatbox: 設定聊天框的高度、邊框、滾動條和背景顏色。
- .user-message: 設定使用者訊息的顏色為綠色。
- .bot-message: 設定機器人訊息的顏色為藍色。

JavaScript:
- 使用 jQuery 來處理 DOM 操作。
- 當使用者點擊 "Send" 按鈕時，將使用者輸入的訊息儲存到 messages 陣列中，並顯示在聊天框中。
- 使用 fetch API 將使用者訊息和上下文傳送到伺服器端的 English_tutor.php。
- 接收伺服器回傳的機器人回覆，並顯示在聊天框中。
- 自動滾動聊天框到最底部以顯示最新訊息。
