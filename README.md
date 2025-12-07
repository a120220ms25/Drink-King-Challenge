# 🍹 飲料王挑戰 👑

> 測試你對台灣飲料連鎖店的了解程度！

![VibeCoding Games](https://img.shields.io/badge/VibeCoding-Games-D69396?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 📖 專案簡介

「飲料王挑戰」是一款互動式問答遊戲，讓你測試對台灣飲料連鎖店的熟悉度。透過 20 道精心設計的題目，檢驗你是否真的是飲料專家！

🎮 **線上體驗：** [https://a120220ms25.github.io/Drink-King-Challenge/](https://a120220ms25.github.io/Drink-King-Challenge/)

## ✨ 功能特色

### 🎯 核心遊戲機制
- **20 道問答題**：涵蓋台灣知名飲料連鎖品牌
- **計分系統**：基礎 5 分/題，連擊獎勵加成
- **連擊系統**：連續答對可獲得額外分數
- **即時反饋**：答題後立即顯示正確答案

### 🏆 成就系統
- 完美首殺：首次獲得滿分
- 連擊王：達到 15 連擊
- 不敗傳說：連續 5 局不答錯
- 速度惡魔：30 秒內答完 10 題
- 逆轉勝：從 0 分逆轉到 80 分
- 老將：遊玩 10 次以上

### 📊 統計追蹤
- 個人統計中心：總遊戲次數、歷史最高分、平均分數
- 歷史記錄：保留最近 100 場遊戲記錄
- 趨勢圖表：視覺化呈現最近 10 局表現
- 最快完成時間追蹤

### 🎨 使用者體驗
- 簡約品牌風格設計系統
- 完整 RWD 響應式設計
- 煙火特效慶祝
- 音效回饋系統
- 沉降式按鈕設計

### 📤 分享功能
- IG Story 圖片生成
- 複製遊戲連結
- 分享遊戲結果
- 答案檢視功能

## 🎮 遊戲規則

1. 輸入你的名字開始挑戰
2. 每題為單選題，從 4 個選項中選擇正確答案
3. 每題基礎分數 5 分
4. 連續答對可獲得額外加分（連擊加成）
5. 完成 20 題後獲得稱號與成績

### 🏅 稱號系統

| 分數範圍 | 稱號 | 說明 |
|---------|------|------|
| 100+ | 👑 飲料王 | 您可能就是那個發明波霸的人 |
| 81-99 | 🥤 手搖達人 | 您的舌頭已經投保千萬 |
| 61-80 | 🧋 配料收藏家 | 您知道每一顆芋圓的產地 |
| 41-60 | ☕ 冰塊甜度糾察隊 | 能分辨七分糖和八分糖 |
| 21-40 | 🚶 永遠點錯店的悲劇人物 | 至少您走對了排隊的方向 |
| 0-20 | 💧 白開水信徒 | 您顯然與茶飲無緣 |

## 🛠 技術架構

### 技術棧
- **前端**：純 HTML5 + CSS3 + Vanilla JavaScript
- **字體**：Google Fonts (Inter)
- **儲存**：LocalStorage（成就、歷史記錄）
- **圖片生成**：Canvas API

### 設計系統
```css
/* 品牌色系 */
--bg-canvas: #DFDFDF;      /* 背景灰 */
--panel-color: #FFFFFF;    /* 面板白 */
--accent-color: #D69396;   /* 品牌粉 */
--shadow-color: #B07C7F;   /* 陰影色 */
```

### 專案結構
```
Drink-King-Challenge/
├── index.html          # 主程式檔（含 HTML/CSS/JS）
└── README.md          # 專案說明文件
```

## 🚀 快速開始

### 線上遊玩
直接訪問：[https://a120220ms25.github.io/Drink-King-Challenge/](https://a120220ms25.github.io/Drink-King-Challenge/)

### 本地運行
1. Clone 專案
```bash
git clone https://github.com/a120220ms25/Drink-King-Challenge.git
```

2. 開啟 `index.html`
```bash
cd Drink-King-Challenge
open index.html  # macOS
# 或直接用瀏覽器開啟 index.html
```

## 📱 響應式設計

- **桌面版**：完整功能體驗
- **平板版**：自適應佈局調整
- **手機版**：優化觸控操作與顯示

## 🎯 使用場景

- 朋友聚會破冰遊戲
- 飲料愛好者知識測試
- 團隊建設活動
- 社群媒體互動內容

## 📝 開發者資訊

**Author**: Sabrina
**Brand**: VibeCoding Games
**Version**: 1.0.0
**License**: MIT

## 🤝 貢獻

歡迎提出問題和建議！

1. Fork 專案
2. 建立功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交變更 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 開啟 Pull Request

## 📄 版本歷程

- **v1.0.0** (2024) - 正式發布
  - 完整 RWD 響應式設計
  - IG Story 分享功能
  - 個人統計中心
  - 成就系統

## 💡 未來計畫

- [ ] 多人對戰模式
- [ ] 題庫擴充
- [ ] 難度選擇
- [ ] 主題切換（深色模式）
- [ ] 更多成就類型

## 📞 聯絡方式

有任何問題或建議，歡迎透過 [GitHub Issues](https://github.com/a120220ms25/Drink-King-Challenge/issues) 聯繫我們。

---

<div align="center">

Made with ❤️ by VibeCoding Games

**[開始挑戰](https://a120220ms25.github.io/Drink-King-Challenge/)** | **[回報問題](https://github.com/a120220ms25/Drink-King-Challenge/issues)**

</div>
