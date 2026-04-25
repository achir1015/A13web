A13web https://achir1015.github.io/A13web/
<img width="1866" height="722" alt="image" src="https://github.com/user-attachments/assets/f892be94-7fa0-4252-aaef-fecf510310d4" />
<img width="878" height="659" alt="image" src="https://github.com/user-attachments/assets/abf64bb4-31f6-4230-bc45-ff0a2d2bcbc0" />
⚠️ 重要提醒：client_secret 是機密資訊，請勿在公開場合分享，建議您事後至 Google Cloud Console 重新產生新的密鑰。
前端網頁只需要 client_id，不需要 client_secret（那是伺服器端用的）。我現在加入 Google Drive 整合：Viewed a file, edited a fileViewed a file, edited a file加入 Google Drive 相關 CSS：加入Google Drive UI的CSS樣式加入Google Drive UI的CSS樣式加入 Google Drive 工具列 HTML（放在 nav 下方）：在nav下方加入Google Drive工具列在nav下方加入Google Drive工具列加入 Google Drive JS（放在 init() 前）：Ran 2 commands, edited a file, read a fileRan 2 commands, edited a file, read a fileGoogle Drive 整合已加入！操作說明：

使用方式
頁面頂端出現藍色 Google Drive 同步工具列：
第一次使用：

點 「🔐 Google 登入」 → 跳出 Google 授權視窗 → 允許
登入後顯示您的 Google 帳號名稱

日常操作：
按鈕功能☁️ 存至 Drive將目前所有 XML 資料上傳到您的資料夾📂 從 Drive 讀取從 Drive 下載最新 XML 覆蓋到本機

技術說明

儲存位置：您的 Google Drive 資料夾內，檔案名為 A13_NursingRecords.xml
授權方式：OAuth2 Implicit Flow，只用 client_id，不在前端使用 client_secret（安全）
重複儲存：若檔案已存在則更新覆蓋，不重複建立


⚠️ 請注意：建議您到 Google Cloud Console 重新產生 client_secret，因為剛才分享的密鑰已外露。client_id 是公開的沒問題，但 client_secret 應妥善保管。

