# Ai Doctor Api Ai Medical Chatbot Healthcare Ai Assistant MCP Server

[English](./README_EN.md) | [简体中文](./README.md) | 繁體中文

## 🚀 使用 EMCP 平台快速體驗

**[EMCP](https://sit-emcp.kaleido.guru)** 是一個強大的 MCP 伺服器管理平台，讓您無需手動配置即可快速使用各種 MCP 伺服器！

### 快速開始：

1. 🌐 造訪 **[EMCP 平台](https://sit-emcp.kaleido.guru)**
2. 📝 註冊並登入帳號
3. 🎯 進入 **MCP 廣場**，瀏覽所有可用的 MCP 伺服器
4. 🔍 搜尋或找到本伺服器（`bach-ai_doctor_api_ai_medical_chatbot_healthcare_ai_assistant`）
5. 🎉 點擊 **「安裝 MCP」** 按鈕
6. ✅ 完成！即可在您的應用中使用

### EMCP 平台優勢：

- ✨ **零配置**：無需手動編輯配置檔案
- 🎨 **視覺化管理**：圖形介面輕鬆管理所有 MCP 伺服器
- 🔐 **安全可靠**：統一管理 API 金鑰和認證資訊
- 🚀 **一鍵安裝**：MCP 廣場提供豐富的伺服器選擇
- 📊 **使用統計**：即時查看服務調用情況

立即造訪 **[EMCP 平台](https://sit-emcp.kaleido.guru)** 開始您的 MCP 之旅！


---

## 簡介

這是一個 MCP 伺服器，用於存取 Ai Doctor Api Ai Medical Chatbot Healthcare Ai Assistant API。

- **PyPI 套件名**: `bach-ai_doctor_api_ai_medical_chatbot_healthcare_ai_assistant`
- **版本**: 2.0.0
- **傳輸協定**: stdio


## 安装

### 从 PyPI 安装:

```bash
pip install bach-ai_doctor_api_ai_medical_chatbot_healthcare_ai_assistant
```

### 从源码安装:

```bash
pip install -e .
```

## 运行

### 方式 1: 使用 uvx（推荐，无需安装）

```bash
# 运行（uvx 会自动安装并运行）
uvx --from bach-ai_doctor_api_ai_medical_chatbot_healthcare_ai_assistant bach_ai_doctor_api_ai_medical_chatbot_healthcare_ai_assistant

# 或指定版本
uvx --from bach-ai_doctor_api_ai_medical_chatbot_healthcare_ai_assistant@latest bach_ai_doctor_api_ai_medical_chatbot_healthcare_ai_assistant
```

### 方式 2: 直接运行（开发模式）

```bash
python server.py
```

### 方式 3: 安装后作为命令运行

```bash
# 安装
pip install bach-ai_doctor_api_ai_medical_chatbot_healthcare_ai_assistant

# 运行（命令名使用下划线）
bach_ai_doctor_api_ai_medical_chatbot_healthcare_ai_assistant
```

## 配置

### API 認證

此 API 需要認證。請設定環境變數:

```bash
export API_KEY="your_api_key_here"
```

### 環境變數

| 變數名 | 說明 | 必需 |
|--------|------|------|
| `API_KEY` | API 金鑰 | 是 |
| `PORT` | 不適用 | 否 |
| `HOST` | 不適用 | 否 |



### 在 Claude Desktop 中使用

编辑 Claude Desktop 配置文件 `claude_desktop_config.json`:


```json
{
  "mcpServers": {
    "ai_doctor_api_ai_medical_chatbot_healthcare_ai_assistant": {
      "command": "uvx",
      "args": ["--from", "bach-ai_doctor_api_ai_medical_chatbot_healthcare_ai_assistant", "bach_ai_doctor_api_ai_medical_chatbot_healthcare_ai_assistant"],
      "env": {
        "API_KEY": "your_api_key_here"
      }
    }
  }
}
```

**注意**: 請將 `E:\path\to\ai_doctor_api_ai_medical_chatbot_healthcare_ai_assistant\server.py` 替換為實際的伺服器檔案路徑。


## 可用工具

此服务器提供以下工具:


### `neurosurgery`

Neurosurgery

**端点**: `POST /chat`


**参数**:

- `noqueue` (string): Example value: 1



---



## 技术栈

- **传输协议**: stdio
- **HTTP 客户端**: httpx

## 开发

此伺服器由 [API-to-MCP](https://github.com/BACH-AI-Tools/api-to-mcp) 工具自動生成。

版本: 2.0.0
