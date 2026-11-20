# Type-C 支援影像輸出查詢

查詢哪些筆電、平板、手機的 USB-C 孔可以輸出影像（DisplayPort Alt Mode、Thunderbolt 3/4/5、USB4）。可依類別、品牌、年份篩選，也可直接搜尋型號。

## 檔案

| 檔案 | 說明 |
|---|---|
| `index.html` | 查詢網站，載入同資料夾的 `devices.json` 與 `references.json` |
| `devices.json` | 完整資料（brand、category、model、year、year_estimated、note、source_url、references） |
| `devices.csv` | 同上，可用 Excel 開啟 |
| `references.json` | 參考資料清單（編號、說明、連結），`references` 欄位的編號對應這裡 |

## 收錄範圍（共 1991 筆，42 個品牌）

- 手機 359 筆、平板 38 筆、筆電 1594 筆。
- 約 395 筆整理自公開的裝置清單，已逐筆核對，年份可疑者另外查證，附參考編號。
- 約 1596 筆為網路查證補充：2016–2026 年筆電、2024–2026 年手機，每筆附規格來源連結（`source_url`）。

## 限制

- 這是「已確認支援」的清單，沒列出的型號不代表不支援，也不是各品牌的完整型號。
- 補充資料部分來自搜尋摘要、第三方資料庫或 Wikipedia，`note` 欄有標示；部分型號代碼與年份為推估（`year_estimated` 為 true）。
- 無法保證每一筆都正確。實際能否輸出影像，請以廠商規格、機型版本、線材與轉接器為準。

## 授權

程式碼（`index.html`）採用 MIT 授權。資料授權請另行確認。
