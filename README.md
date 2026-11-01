# GLRR Demo

Global Liquidity & Risk Radar（全球資金水位與風險雷達）的唯讀靜態 Demo。

- 資料擷取於 2026-11-02（v1.4.0，見 `site/demo-data/meta.json`），之後不會自動更新。
- 全部是 build 好的靜態檔案，不連後端、不需要登入；所有操作都是唯讀。
- 台灣市場鑽取（選股和交易訊號）僅最高權限帳號提供，Demo 只顯示遮罩畫面。
- 授權限內部使用的資料（ICE BofA、Tiingo、臺灣證券交易所網站資料）不包含在本 Demo，畫面以遮罩取代。
- 各資料來源的出處與授權聲明列在每頁頁尾。

`site/` 由主專案的 `scripts/local/publish-demo.sh` 產生，push 到 `main` 後由 GitHub Actions 發佈到 GitHub Pages。
