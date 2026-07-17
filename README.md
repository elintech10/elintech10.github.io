# 4WD 載具扭矩與功率計算器

此資料夾可直接部署至 GitHub Pages。

## 檔案

- `index.html`：網站主頁與全部計算功能
- `.nojekyll`：停用 GitHub Pages 的 Jekyll 處理

## 部署方式

### 方式一：從儲存庫根目錄部署

1. 建立新的 GitHub repository。
2. 將本資料夾中的 `index.html` 與 `.nojekyll` 上傳到 repository 根目錄。
3. 開啟 repository 的 **Settings → Pages**。
4. 在部署來源選擇從分支部署。
5. 選擇 `main` 分支與根目錄 `/`。
6. 儲存後，GitHub Pages 會產生網站網址。

### 方式二：使用 `docs` 資料夾

也可將這些檔案放入 repository 的 `docs/` 目錄，並在 Pages 設定中選擇 `main` 分支與 `/docs`。

## 特性

- 單一 HTML，不依賴外部 JavaScript 或 CSS。
- 支援手機、平板與桌面版面。
- 可離線使用；下載 `index.html` 後直接以瀏覽器開啟即可。
- 可部署於 GitHub Pages、一般網站空間或公司內部伺服器。
