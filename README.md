# 功生聯 — 推廣網頁（GitHub Pages）

靜態網站：次世代跨域功能性分子與生化檢測整合技術聯盟（功能性分子與生化檢測聯盟 · 功生聯）。

## 本機預覽

以瀏覽器開啟專案根目錄的 `index.html`，或使用本機伺服器（例如 `npx serve .`）。

## 發布到 GitHub Pages

1. 在 GitHub 建立新儲存庫，將本資料夾內容推送上去（保留 `index.html` 在根目錄）。
2. 儲存庫 **Settings → Pages**。
3. **Source** 選擇 `Deploy from a branch`，**Branch** 選 `main`（或 `master`）且資料夾選 `/ (root)`。
4. 儲存後數分鐘內可透過 `https://<使用者名稱>.github.io/<儲存庫名稱>/` 存取。

已包含 `.nojekyll`，避免 Jekyll 處理造成路徑問題。

## 檔案說明

| 路徑 | 說明 |
|------|------|
| `index.html` | 首頁 |
| `charter.html` | 組織章程（網頁版） |
| `membership.html` | 入會資訊與下載 |
| `assets/logo.jpg` | 聯盟標誌 |
| `files/*.docx` | 章程與會員合約書原始檔 |

若更新 Word 原文，請替換 `files/` 內對應檔案，並視需要同步修改 `charter.html` 內文。
