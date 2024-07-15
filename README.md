# NessusPro-Automation-Scan
- Nessus Professional version 7 以後的版本，不支援使用 API Key 創建新的 Scan
- 本專案目標，使用程式觸發 Nessus Professional 去對目標伺服器進行弱點掃描

- 測試環境
  - Python 3.10.11 64-bit
  - Nessus Professional Version 10.7.4 

- 參數說明
  - Nessus Professional 入口網站 : 10.0.0.1:8834
  - 使用者名稱 : user01
  - 使用者密碼 : password01
  - 預計創建的掃描名稱 : API_Test_0123
  - 預計掃描的網段 : 10.0.0.0/8
