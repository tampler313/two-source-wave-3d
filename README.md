# 雙點波源・3D 水波干涉實驗室

完全前端、無外部程式庫的 WebGL / Canvas 3D 雙點波源干涉展示。適合手機 Safari 與桌面瀏覽器。可調整波源間距、頻率、波速、振幅與相位差，提供 3D 波面、振幅包絡、節線／腹線及雙曲線退化射線預設。

## 發布到 GitHub Pages

1. 到 https://github.com/new 建立 `two-source-wave-3d` **Public** 儲存庫（GitHub Free 的 Pages 需公開儲存庫）。
2. 使用 `Add file` → `Upload files`，把本資料夾的 `index.html`、`.nojekyll`、`README.md` 上傳到儲存庫根目錄並提交。
3. 在 `Settings` → `Pages` 將 Source 設成 `Deploy from a branch`，Branch 設定 `main`、`/(root)`，按 `Save`。
4. 部署成功後，網站預期會位於 `https://<GitHub使用者名稱>.github.io/two-source-wave-3d/`。以 GitHub Pages 設定頁顯示的實際網址為準。

## 技術說明

- `index.html` 內含樣式、介面及 3D 渲染程式，沒有外部 JS/CDN。
- iOS Safari：單指旋轉，雙指縮放，按「俯視」可檢視等路徑差曲線。
- 支援 WebGL；無 WebGL 時改用 Canvas 2D 軟體繪圖備援。
- 理想化水波：不含水深色散、容器反射；距離衰減為近似示意。
- 站點公開，請勿把個人資料或秘密放入程式碼。