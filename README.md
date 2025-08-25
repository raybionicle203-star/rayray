# GitLab Pages 上線指南（台灣 & 大陸可開）

此專案為「零外部依賴」的最小網站：所有字型/JS/圖片都自託管，避免 Google Fonts/YouTube/FB 等在大陸常被擋的來源。

## 發佈步驟
1. 在 GitLab 建立專案（要根域網址就把專案命名為 `你的帳號.gitlab.io`；或用一般專案名）。
2. 將本資料夾所有檔案上傳到該專案的 **預設分支**（通常是 `main`）。
3. 稍等 CI 跑完（Job 名稱 `pages`）。
4. 進入 **Settings → Pages** 取得公開網址。若要對外開放，專案建議設為 **Public** 或將 Pages 設為 **Everyone**。

## 注意
- 請勿在 HTML 中引用 Google、YouTube、Facebook、Twitter 等第三方腳本或字型。
- 若要更換圖片，替換 `assets/img/line-family-day.jpg` 與 `assets/img/line-family-day.webp`，並保持路徑不變即可。
