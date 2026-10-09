# 待辦清單 · Todo List

一個單一 HTML 檔、零後端嘅待辦清單 web app — 資料儲存於瀏覽器 `localStorage`。

## 功能
- 加入 / 刪除 / 標記完成
- 三頁籤篩選：全部、未完成、已完成
- 進度條、深色／淺色主題、手機響應式

## 使用
直接打開 `index.html`（或 `todo.html`），唔需要任何 build 或 server。

## 部署
透過 GitHub Actions 自動部署到 **GitHub Pages**：
`.github/workflows/deploy-pages.yml`

公開網址：`https://klchan-learning.github.io/klchan-learning/`

## 檔案
| 檔案 | 用途 |
|---|---|
| `index.html` | 網站入口（Pages 根） |
| `todo.html` | 同上（獨立入口） |
| `.github/workflows/deploy-pages.yml` | 自動建置 + 部署 |
| `.gitignore` | 忽略系統／暫時檔案 |
