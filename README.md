# 🐾 Walky6Go

**Walky6Go** 是一款為台灣打造的寵物遛狗媒合平台，結合 Line Pay 金流、Walker 審查機制與簡單美觀的介面設計，協助飼主與專業遛狗者輕鬆、安全地媒合、預約與管理服務。

> Built for dog lovers in Taiwan — match, walk, and pay with trust.

---

## 🌟 核心功能特色

### 👤 雙身分登入機制
- 支援 Line Login，一鍵快速登入
- 單一帳號可切換【飼主】或【Walker】角色

### 🐕 飼主功能
- 填寫狗狗資料與需求時段、地點
- 自動媒合或手動選擇附近合適的 Walker
- 使用 Line Pay 完成付款並享受平台保障
- 評價 Walker 並瀏覽歷史訂單

### 🧍‍♂️ Walker 功能
- 註冊後提交身分證件與資料，平台人工審查
- 設定服務區域與可接單時段
- 接單並打卡回報遛狗狀況（支援簡易 GPS 或圖片上傳）
- 查看歷史收益與評價紀錄

### 💬 雙方互動與信任機制
- Walker 審查進度標示（審查中／通過）
- 每筆服務皆可互評
- 顯示保險說明與平台責任免除聲明

---

## 🧱 技術架構（Tech Stack）

- **Next.js**：前端架構，支援 SSR 與 SEO
- **Firebase**：Auth / Firestore / Storage
- **Tailwind CSS**：統一 UI 設計語言
- **Line Pay API**：台灣金流整合與自動分帳
- **Vercel**：部署平台

---

## 🗂️ 專案結構（簡略）

- `/pages`：主要頁面（首頁、Walker 註冊、發案流程…）
- `/components`：共用 UI 元件（卡片、表單、按鈕…）
- `/firebase`：Firebase 初始化與資料處理
- `/lib`：Line Pay API 串接、資料工具
- `/styles`：Tailwind 設定與全域樣式

---

## 🧩 MVP 階段功能進度

| 功能模組         | 狀態     |
|------------------|----------|
| Line 登入         | ✅ 已完成 |
| 飼主發案流程       | ✅ 已完成 |
| Walker 註冊與審查 | ✅ 已完成 |
| Line Pay 串接     | 🔄 開發中 |
| 評價系統         | ✅ 已完成 |
| 打卡機制         | 🔜 預計加入 |
| Walker 收益報表   | 🔜 MVP 2.0 |
| 保險條款／平台聲明 | ✅ 已設計嵌入 |

---

## 📄 聯絡與貢獻

由 [Jazmyn Han](https://github.com/trygoatlife) 經營與開發。

歡迎提供回饋與交流，未來會逐步開放接案者資格申請、商業合作、保險業者串接等擴充功能。

---

## 🐾 品牌精神

「**Walky6Go** 是一個讓人與毛孩都能感到信任的媒合平台。」  
從 UX 設計、付款機制到 Walker 的專業培訓，我們期望用簡單而溫暖的方式，讓每一次出門都安心、愉快。

---
