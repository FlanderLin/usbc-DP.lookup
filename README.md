# Type-C 支援影像輸出查詢

查詢哪些筆電、平板、手機的 USB-C 孔可以直接接螢幕（DisplayPort Alt Mode，含 Thunderbolt 3）。可依類別、品牌、年份篩選，也可直接搜尋型號。

網站：啟用 GitHub Pages 後，開啟 `index.html` 即可使用（單一檔案，不需要後端）。

## 檔案

| 檔案 | 說明 |
|---|---|
| `index.html` | 查詢網站，資料已內嵌 |
| `devices.json` | 完整資料（brand、category、model、year、year_estimated、note） |
| `devices.csv` | 同上，可用 Excel 開啟 |

## 資料來源與限制

- 主要整理自 EverybodyWiki「List of devices with video output over USB-C」。資料授權請以該來源頁面的條款為準。
- 型號已逐筆對照來源頁面，並另外查證年份可疑的項目。與來源頁面不同的年份會在 `note` 欄寫明。
- 來源頁面的筆電清單沒有年份，`year_estimated` 為 true 的筆電年份是查證或推估值，僅供參考。
- 這是「已確認支援」的清單，沒列出的型號不代表不支援。來源頁面為社群維護，無法保證每一筆都正確。實際能否輸出影像，請以廠商規格、機型版本、線材與轉接器為準。
- 目前收錄 419 筆（手機、平板、電腦）。資料持續補充中。

## 授權

程式碼（`index.html`）採用 MIT 授權。資料授權見上方說明。
