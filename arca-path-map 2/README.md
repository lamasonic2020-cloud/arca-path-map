# 方舟 ARCA 內部轉化路徑地圖 0 到 1

給 0 到 1 階段個人品牌經營者的互動式診斷工具。
五站轉化路徑：內容引流 → 進私域 → 信任累積 → 私訊對話 → 諮詢成交。
先做五題自我檢測找出卡點，再照該站的 SOP、公式與範例打通。

## 特點

- 單一 `index.html`，CSS、JS、logo 全部內嵌，零依賴、免建置
- 手機優先設計（受眾從 Skool / IG / LINE 點進來）
- 五站內容集中在檔案內的 `STATIONS` 物件，改文案只需要改那一個地方

## 部署到 GitHub Pages

1. 在 GitHub 開一個新 repo（例如 `arca-path-map`）
2. 把這個資料夾裡的檔案上傳（`index.html` 和這份 `README.md`）
3. 到 repo 的 **Settings → Pages**
4. Source 選 **Deploy from a branch**，Branch 選 `main`、資料夾選 `/ (root)`，按 Save
5. 等一兩分鐘，網址會是 `https://<你的帳號>.github.io/arca-path-map/`

之後要改內容，直接在 GitHub 上編輯 `index.html` 裡的 `STATIONS` 物件，存檔後幾分鐘內自動更新。

## 修改文案

打開 `index.html`，搜尋 `const STATIONS`。
每一站是一個物件，包含：站名、一句話說明、檢測問題、目標、具體做法、公式與範例、常見錯誤、過關基準。
站四另外有 `compare`（對照範例）和 `niches`（四個行業的私訊範例分頁）。
