雙向即時口譯 PWA｜9 語言版
================================

支援語言
--------
1. 英文
2. 日文
3. 西班牙文
4. 韓文
5. 越南文
6. 印尼文
7. 泰文
8. 法文
9. 德文

本版功能
--------
- 首頁直接顯示 9 種語言選單
- 自動產生該語言的雙向即時口譯指令
- 可一鍵複製口譯指令
- 記住上次選擇語言
- 一鍵嘗試開啟 ChatGPT App
- 保留網頁版備援
- 可安裝為 PWA 到手機桌面
- 離線可開啟介面（Service Worker 快取）

重要限制
--------
目前一般 PWA／網頁沒有官方公開方式，可以保證：
1. 強制建立 ChatGPT 全新空白對話
2. 直接指定 ChatGPT Live Voice
3. 將 PWA 選到的語言自動注入同一個 Live Voice 工作階段

因此，本 PWA 的定位是：「語言選單 + 口譯指令準備 + ChatGPT 啟動器」。

若要更接近真正一鍵直達 Voice：
- iPhone：建議使用 Apple「捷徑」App 的 ChatGPT Voice Mode 動作
- Android：長按 ChatGPT App 圖示，查看是否有 Voice／語音快捷動作

GitHub Pages 更新方式
--------------------
若原本已有 live-voice-interpreter Repository：
1. 進入 Repository。
2. 覆蓋更新：index.html、manifest.json、service-worker.js、icon-192.png、icon-512.png、README.txt。
3. Commit changes。
4. 等待 GitHub Pages 重新部署。
5. 手機重新開啟 PWA。
6. 若仍顯示舊版，完全關閉 PWA 再開；必要時刪除桌面 PWA 後重新加入主畫面。

使用流程
--------
1. 點桌面「雙向即時口譯」。
2. 選擇語言。
3. 視需要按「複製口譯指令」。
4. 按「開啟 ChatGPT」。
5. 進入 Voice 後開始口譯。
