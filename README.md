本專案為大三《系統分析與設計》課程之期末報告與競賽成果，專案報告詳見檔案 「系統分析與設計期末報告-資管三甲第九組.pdf」。獎狀請見 award/ 資料夾。

桌面/
├── car/                               # 違規事件後端系統
│   ├── app.py                         # Flask 後端服務主程式，負責處理違規事件資料
│   └── Dump20250108.sql              # MySQL 匯入檔，包含違規事件資料庫 schema 與樣本資料

├── Taipei-City-Dashboard-main/       # 改裝自臺北城市儀表板，使用 Docker 運行
│                                     # 用於顯示違規事件地理資訊圖層（GeoJSON）

├── run_process_board_data.bat        # 批次處理腳本，自動將地點 GeoJSON 檔案放入 Dashboard 的地圖資料夾中

├── camera.csv                        # 預放之超速相機資料（CSV），需匯入 PostgreSQL 的 `speeding` 資料表

├── 期末說明.pptx.pdf                  # 專案簡報檔（PDF 格式）

D:/
└── pon/                              # JSP 系統，提供開立罰單功能之前端介面

C:/
└── 使用者/mray3/process_board_data.py # 實際由 run_process_board_data.bat 呼叫的資料處理 Python 腳本
