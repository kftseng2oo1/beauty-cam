# ✨ 美顏相機

即時美肌濾鏡相機：用前鏡頭預覽、調整美顏參數，拍下後直接存檔。

**線上使用**：https://kftseng2oo1.github.io/beauty-cam/

## 主要功能
- 濾鏡預設：自然、粉嫩、清透、暖調、冷白、原圖
- 滑桿微調美顏參數，一鍵切換美顏 ON／OFF 對比
- 拍照後預覽並 💾 儲存

## 使用方式
按「啟動相機」並允許相機權限（需 HTTPS），選濾鏡、調整後拍照儲存。

## 技術與依賴
- 單檔 HTML PWA（`index.html` 內含全部 HTML/CSS/JS），`manifest.json` + `sw.js` 提供安裝到主畫面與離線快取。
- `getUserMedia` 取得鏡頭畫面，Canvas 套用 CSS filter 即時渲染
- 全部在本機處理，不上傳照片
