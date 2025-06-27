# 🐾 pawpal-linebot

**PawPal 毛毛探員** 是一個協助使用者查詢「欲認領養的動物」與「附近合法獸醫院」的 LINE Bot。  
未來如有空，將隨緣加入「特定寵物業合法名單查詢」功能。

---

## 🔗 使用資料來源（政府開放平台與地理位置服務）

### 🐶 動物認領養
- **平台**：政府資料開放平台
- **API**：  
  [連結](https://data.moa.gov.tw/Service/OpenData/TransService.aspx?UnitId=QcbUEzN6E6DL&IsTransData=1)  
- **用途**：查詢待認養的動物（狗、貓、其他等）資訊

---

### 🧑‍⚕️ 獸醫師（佐）開業執照
- **平台**：政府資料開放平台  
- **API**：  
  [連結](https://data.moa.gov.tw/Service/OpenData/DataFileService.aspx?UnitId=078&IsTransData=1)  
- **用途**：比對合法開業的獸醫診所，顯示鄰近機構

---

### 📍 地址轉經緯度（地理編碼）
- **平台**：Nominatim（OpenStreetMap）  
- **API**：  
  [連結](https://nominatim.openstreetmap.org/search)  
- **用途**：將獸醫診所地址轉換為經緯度以計算距離（資料緩存機制）

---

## 🤖 加入 PawPal LINE Bot 好友

- **LINE ID**：[@447ezqmj](https://line.me/R/ti/p/@447ezqmj)  
- 📱 點擊這裡快速加入好友：  
  👉 [連結](https://line.me/R/ti/p/@447ezqmj)

---

## 📘 使用說明

使用者只需輸入以下指令，即可查詢相關資訊。支援文字指令與位置傳送。

### ✅ 支援指令範例：

| 指令內容 | 說明 |
|----------|------|
| 傳送「位置資訊」 | 查詢附近的合法獸醫院與距離（有部分資料誤差待修正，當前參考用） |
| 傳送文字「認領養」 | 顯示多層快速選單，查詢想要的動物 |

### 🔎 圖片範例：
<div style="display: flex; gap: 20px;">
  <img src="./images/example_introduce.jpg" alt="Introduction image" height="400" >
  <img src="./images/example.png" alt="Example image" height="200" >
  <img src="./images/example_animal2.png" alt="Animal image 2" height="400" >
  <img src="./images/example_animal.jpg" alt="Animal image 1" height="400" >
  <img src="./images/example_vet.jpg" alt="Veterinarian image" height="400" >
</div>