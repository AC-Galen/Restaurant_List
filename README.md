# A3:打造餐廳清單

利用 Node.js 和 Express 打造的餐廳清單網頁。

## 基本功能

使用者可以在首頁看到餐廳清單和基本資料：

- 照片
- 名稱
- 分類
- 評分

使用者點擊餐廳可以看到餐廳的詳細資訊：

- 類別
- 地址
- 電話
- 描述
- 圖片

使用者可以在首頁透過餐廳名稱或類別查詢餐廳。

## 指定規格

- 讀取 JSON 檔案載入種子資料
- 使用 handlebars 將資料動態呈現在頁面上
- 使用 handlebars 的 each 迴圈渲染多張餐廳卡片
- 使用 params 打造動態路由
- 使用 query 打造搜尋功能

## 安裝流程

打開終端機，使用git clone將專案下載至本地資料夾 : 
git clone https://github.com/AC-Galen/Restaurant_List.git

進入專案資料夾 :
 cd Restaurant_List

安裝專案需求套件 : 
npm install 
npm i nodemon

啟動伺服器 : 
npm run dev

終端機顯示 The server is listening on http://localhost:3000 代表伺服器成功啟動 可至瀏覽器網址輸入 http://localhost:3000 瀏覽專案功能
