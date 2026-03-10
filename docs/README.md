# 文件導覽（Prototype）

## 你要給客戶看的
- 客戶版系統規格書：`docs/客戶版_系統規格書.md`

## 你要給內部（PM/開發）對齊的
- 產品/使用者規格（較完整）：`docs/表單查詢Prototype_產品規格.md`
- AI/開發規則（Copilot 指示）：`.github/copilot-instructions.md`

## 多畫面擴充方式（之後新增畫面不會亂）
- 每個畫面一份文件：放在 `docs/screens/`
- 每個畫面一張或多張截圖：放在 `docs/assets/screens/<畫面代號>/`

> 目前本 Prototype 只保留「表單查詢頁（query）」的畫面規格；其他占位頁已移除。

### 命名規則（建議）
- 畫面代號：用英文小寫與底線，例如：`query`、`detail`、`apply`、`admin_list`
- 主要截圖檔名：`screen.png`
- 若同畫面有多張：`screen_01.png`、`screen_02.png`

## 截圖放好後怎麼確認
- 用 VS Code 打開客戶版文件：`docs/客戶版_系統規格書.md`
- 若圖片路徑正確，文件內會直接顯示截圖。
