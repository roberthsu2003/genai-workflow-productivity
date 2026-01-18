# 任務 10：使用 Claude Desktop MCP 和 Skills 跨應用程式整合資料

## 🎯 工作情境
經常需要從多個應用程式中收集和整理資料（例如 Google Drive、本地檔案系統、Notion、Slack 等），手動切換 APP、複製貼上、整合資料非常耗時且容易出錯。例如：從多個來源整理週報、整合會議紀錄、統整專案文件等。

## 🤖 使用的 AI 工具
- **Claude Desktop**（包含 MCP 和 Skills 功能）
- **MCP Server/Connector**（本地檔案系統、Google Drive、Notion 等，免費版即可使用）
- **Claude Skills**（任務專屬規則、格式範本，進階方案功能更完整）
- **Canva MCP**（連接 Canva，可透過 Claude Desktop 直接生成和編輯設計）
- **Google Drive** / **Notion** / **本地檔案系統**（資料來源）

## 💻 AI 負責的工作（80%）
- 自動從多個來源（檔案系統、雲端硬碟、協作平台）收集資料
- 統整不同格式的文件內容
- 初步分析和分類資料
- 生成整合後的報告或摘要草稿
- 格式化和排版輸出

## 👤 你負責的工作（20%）
- 安裝和配置 MCP Connector（一次性設定）
- 決定哪些資料來源和內容重要
- 定義報告格式和範本需求
- 審閱和微調 AI 整合的內容
- 確認資料準確性和完整性

## 📝 實作步驟
1. **安裝 Claude Desktop**：下載並安裝 Claude Desktop（支援 Windows、Mac、Linux）
2. **配置 MCP Connector（不寫程式）**：在 Claude Desktop 設定中，開啟 MCP 功能並連接需要的 Connector
3. **啟用 Claude Skills（選用）**：在 Claude Desktop 設定 → Capabilities 中，開啟 Skills 功能
4. **測試連接**：在 Claude Desktop 中詢問，確認 Claude 可以正確存取資料來源
5. **整合資料任務**：告訴 Claude 整合需求，AI 會自動從多個來源收集和整理資料
6. **審閱和調整**：檢查 AI 生成的整合內容，微調格式和重點
7. **儲存和分享**：將整合結果匯出為文件或儲存到平台

## 📄 產出結果
- **整合後的報告**（從多個來源自動整合）
- **結構化的資料摘要**（包含關鍵資訊和統計）
- **視覺化設計**（可透過 Canva MCP 直接生成資訊圖表、海報等）
- **自動化的資料收集流程**（可重複使用）

## 💡 實際應用範例

**範例 1：週報自動生成**
- **資料來源**：Google Drive（會議紀錄）、本地檔案（專案進度）、Notion（待辦清單）
- **產出**：包含本週完成事項、待辦事項、下週計畫的完整週報

**範例 2：會議資料統整**
- **資料來源**：Google Meet 錄音文字檔、Slack 討論串、Notion 會議筆記
- **產出**：包含討論內容、決議事項、行動項目的完整會議紀錄

**範例 3：專案文件索引**
- **資料來源**：多個資料夾的專案文件（PDF、Word、Excel）
- **產出**：專案文件清單，每個文件包含摘要和關鍵資訊

**範例 4：整合資料並生成視覺化設計**
- **資料來源**：Google Drive（數據報告）、本地檔案（圖片素材）
- **產出**：整合的數據報告 + Canva 設計的資訊圖表

## ⚙️ MCP 設定說明（免程式）

**本地檔案系統 MCP**（免費，預設可用）
- 在 Claude Desktop 設定中，啟用「Filesystem」MCP
- 指定可存取的資料夾路徑

**Google Drive MCP**（免費方案可用）
- 在設定中選擇「Google Drive」Connector
- 點選授權按鈕，登入 Google 帳號

**Notion MCP**（免費方案可用）
- 在 Notion 中建立 Integration Token
- 在 Claude Desktop 設定中輸入 Token

**Canva MCP**（免費方案可用）
- 在 Claude Desktop 設定中選擇「Canva」Connector
- 點選授權按鈕，登入 Canva 帳號

## 📚 相關資源
- [Claude Desktop 官方網站](https://claude.ai/download)
- [MCP 官方文件](https://modelcontextprotocol.io/)
