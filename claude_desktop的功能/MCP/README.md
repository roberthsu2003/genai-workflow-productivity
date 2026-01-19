# MCP (Model Context Protocol)

Claude Desktop 的 **Extension** 主要指的是 **MCP (Model Context Protocol) 伺服器**。

## MCP 伺服器的功能

MCP 伺服器讓 Claude Desktop 能夠：

1. **連接外部工具和服務**
   - Google Drive、Slack、GitHub 等
   - 本地檔案系統
   - 資料庫和 API

2. **擴展 Claude 的能力**
   - 讀取和搜尋您的文件
   - 執行程式碼
   - 查詢資料庫
   - 自動化工作流程

## 管理 MCP 伺服器

您可以在 Claude Desktop 的設定檔中管理這些擴充功能：
- **Mac**：`~/Library/Application Support/Claude/claude_desktop_config.json`
- **Windows**：`%APPDATA%\Claude\claude_desktop_config.json`

## 常見的 MCP 伺服器

- **檔案系統存取**：讀取本地檔案
- **Google Drive**：存取雲端文件
- **Git**：程式碼版本控制
- **資料庫連接**：查詢 SQL 資料

## 與 Connectors 的差異

- **Connectors**：主要用於連接第三方服務（如 Notion、Linear），通常透過 UI 介面設定
- **MCP 伺服器**：更底層的擴展機制，需要手動配置設定檔，適合開發者和進階用戶