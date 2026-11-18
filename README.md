# 謝老師 AI 互動教室 · GitHub Pages

建議倉庫名稱：`xie-ai-classroom`

## ⚠️ 上傳方法（必讀）

**一定要這樣上傳，否則會出現 Jekyll `dir_chdir …/docs` 錯誤：**

1. 在 GitHub 建立一個**空的 Public** repository（建議名：`xie-ai-classroom`）。
2. 打開本資料夾 `xie-ai-classroom/`，上傳時**只選裡面的兩個項目**：
   - `README.md`
   - `docs/`（資料夾）
3. **不要**再包一層「xie-ai-classroom」或中文父資料夾再上傳。  
   Repo **根目錄必須直接見到** `docs/` 與 `README.md`。
4. 前往 **Settings → Pages**
   - Source：Deploy from a branch
   - Branch：`main`
   - Folder：**`/docs`**
5. 儲存後稍等一兩分鐘，網站網址會是：

   https://nhto.github.io/xie-ai-classroom/

## 為何會失敗？

若把成個外層資料夾一併上傳，真正檔案會落在 `某某資料夾/docs/`，Pages 找不到根目錄的 `docs/`，就會報 Jekyll / `dir_chdir` 錯誤。

## 重要提醒

- 本套件已包含 `docs/.nojekyll`，避免 GitHub Pages 的 Jekyll 處理破壞靜態 HTML。
- 入口頁為 `docs/index.html`（謝老師 AI 互動教室主頁）。自訂連結儲存在瀏覽器本機，不會一同上傳到 GitHub。

## 內容

- `docs/index.html`：課室入口（語文知識、寫作工坊、成語生詞、圖書教學、AI 影片及互動遊戲）
- `docs/.nojekyll`：關閉 Jekyll
