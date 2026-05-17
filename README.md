# 南臺流音系首頁 Demo 專案

建立時間：2026-05-17 20:19 Asia/Taipei

## 專案目的

這個資料夾是「南臺科技大學流行音樂產業系首頁改版 demo」的前置工作區。目標不是修改學校正式網站，而是先用公開資料與公開照片做一個可上 GitHub Pages 的單頁首頁 demo，給 Jay 自己評估視覺方向。

## 目前狀態

- 已建立專案資料夾結構。
- 已盤點公開首頁的主要導覽、最新訊息與可保留功能。
- 已下載一批公開照片與 Logo 作為 demo 素材。
- 已選定 RunwayML 方向作為設計參考，但會轉譯成「流行音樂產業系」自己的視覺語言。
- 已建立第一版首頁 demo：`index.html`、`styles.css`、`script.js`。
- 尚未建立 GitHub repo。
- 尚未部署 GitHub Pages。

## 建議位置

AI 雲端工作區：

```text
AI共同工作區/02_網站與數位產品/pmi-homepage-demo
```

正式 GitHub repo 建議日後另開，不要直接把學校正式站或 USR 官網 repo 混用。

## 資料夾說明

```text
pmi-homepage-demo/
├── README.md
├── DESIGN.md
├── source-notes/
│   ├── 原網站盤點.md
│   ├── 公開素材來源.md
│   └── 首頁內容架構.md
├── assets/
│   ├── photos/
│   │   ├── home-banner/
│   │   └── facilities/
│   ├── logos/
│   └── raw/
├── site/
│   └── README.md
├── index.html
├── styles.css
├── script.js
└── deploy/
    └── GitHubPages上架紀錄.md
```

## 下一步

Jay 說「我要上架」後，建議執行：

1. 建立 GitHub repo：`pmi-homepage-demo`。
2. commit 專案根目錄中的首頁、素材與文件。
3. push 到 GitHub。
4. 啟用 GitHub Pages，發布來源使用 repo root。
5. 開啟公開網址確認首頁可讀、圖片正常、手機版導覽可用。
