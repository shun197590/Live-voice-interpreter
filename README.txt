雙向即時口譯 PWA｜安裝說明
================================

檔案：
1. index.html
2. manifest.json
3. service-worker.js
4. icon-192.png
5. icon-512.png

建議使用方式：
A. 將五個檔案全部上傳到同一個 GitHub Repository 的根目錄。
B. GitHub → Settings → Pages。
C. Build and deployment → Deploy from a branch。
D. Branch 選 main / root，按 Save。
E. 用手機開啟 GitHub Pages 網址。
F. iPhone Safari：分享 → 加入主畫面。
   Android Chrome：⋮ → 加到主畫面／安裝應用程式。
G. 第一次打開 PWA，依畫面完成 ChatGPT Voice 與自訂指示設定。
H. 完成後，以後點「即時口譯」桌面圖示即可自動嘗試開啟 ChatGPT。

重要：
- ChatGPT App 內請選 Settings → Voice → Live。
- 同一頁請開啟 Start with Voice。
- PWA 不包含 API Key，也不會額外產生 OpenAI API 費用。
- 手機作業系統可能限制網頁自動喚起 App，因此程式內保留備援按鈕。
- ChatGPT 介面與深層連結行為可能隨 App 版本調整。
