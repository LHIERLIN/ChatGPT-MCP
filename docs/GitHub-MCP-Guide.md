# GitHub MCP 功能指南

> 本文檔整理了 GitHub MCP (Model Context Protocol) 的所有功能，方便日後查閱與複習。

---

## 📁 存儲庫管理

| 功能 | 說明 | 範例指令 |
|------|------|----------|
| 創建存儲庫 | 在個人帳號或組織中創建新 repo | "創建一個新的私有存儲庫叫 my-project" |
| Fork 存儲庫 | 複製他人的存儲庫到您的帳號 | "Fork facebook/react 到我的帳號" |
| 搜索存儲庫 | 按名稱、描述、主題等搜索 | "搜索有關 machine learning 的熱門存儲庫" |

---

## 📄 文件操作

| 功能 | 說明 | 範例指令 |
|------|------|----------|
| 讀取文件 | 獲取文件或目錄內容 | "讀取 README.md 的內容" |
| 創建/更新文件 | 直接在 GitHub 上編輯文件 | "在 src 目錄下創建 index.js 文件" |
| 刪除文件 | 從存儲庫中移除文件 | "刪除 temp.txt 文件" |
| 批量推送 | 一次提交多個文件 | "同時創建 config.js 和 utils.js" |

---

## 🌿 分支管理

| 功能 | 說明 | 範例指令 |
|------|------|----------|
| 列出分支 | 查看所有分支 | "列出所有分支" |
| 創建分支 | 從指定分支創建新分支 | "從 main 創建 feature/login 分支" |
| 查看提交記錄 | 獲取 commit 歷史和詳情 | "顯示最近 10 個 commit" |
| 查看標籤 | 列出 git tags | "列出所有版本標籤" |

---

## 🔀 Pull Request

| 功能 | 說明 | 範例指令 |
|------|------|----------|
| 創建 PR | 發起新的 Pull Request | "創建 PR 從 feature 分支合併到 main" |
| 列出 PR | 查看存儲庫的所有 PR | "列出所有開放的 PR" |
| 搜索 PR | 按作者、狀態等篩選 | "搜索我創建的 PR" |
| 更新 PR | 修改標題、描述、狀態 | "更新 PR #5 的標題" |
| 合併 PR | 支持 merge、squash、rebase | "使用 squash 合併 PR #10" |
| 獲取 diff | 查看 PR 的代碼變更 | "查看 PR #42 的代碼變更" |
| 獲取文件列表 | 查看 PR 修改了哪些文件 | "PR #3 修改了哪些文件" |
| 獲取狀態 | 查看 CI/CD 構建狀態 | "PR #7 的構建狀態如何" |

### PR 代碼審查

| 功能 | 說明 | 範例指令 |
|------|------|----------|
| 創建審查 | 開始審查 PR | "審查 PR #15 並批准" |
| 添加評論 | 在特定代碼行添加評論 | "在 PR #15 的第 42 行添加評論" |
| 請求更改 | 要求作者修改代碼 | "請求 PR #8 進行更改" |
| 批准 PR | 通過代碼審查 | "批准 PR #20" |

---

## 🐛 Issue 管理

| 功能 | 說明 | 範例指令 |
|------|------|----------|
| 創建 Issue | 報告 bug 或提出功能請求 | "創建一個 Issue 報告登入問題" |
| 列出 Issue | 查看存儲庫的所有 Issue | "列出所有開放的 Issue" |
| 搜索 Issue | 按標籤、狀態、關鍵字篩選 | "搜索帶有 bug 標籤的 Issue" |
| 獲取 Issue 詳情 | 查看特定 Issue 的內容 | "查看 Issue #25 的詳情" |
| 更新 Issue | 修改內容、狀態、指派人 | "關閉 Issue #30" |
| 添加評論 | 在 Issue 中發表評論 | "在 Issue #10 添加評論說明進度" |
| 獲取評論 | 查看 Issue 的所有評論 | "顯示 Issue #5 的所有評論" |
| 管理標籤 | 獲取或設置 Issue 標籤 | "給 Issue #12 添加 enhancement 標籤" |
| 子 Issue | 管理 Issue 的層級關係 | "將 Issue #8 設為 Issue #3 的子任務" |

---

## 🏷️ 版本發布 (Release)

| 功能 | 說明 | 範例指令 |
|------|------|----------|
| 列出 Release | 查看所有發布版本 | "列出所有發布版本" |
| 獲取最新版本 | 取得最新的 release 資訊 | "最新版本是什麼" |
| 按標籤獲取 | 獲取特定版本的詳情 | "查看 v2.0.0 版本的資訊" |
| 管理 Tags | 列出和查看 git 標籤 | "列出所有 tags" |

---

## 🔍 搜索功能

| 功能 | 說明 | 範例指令 |
|------|------|----------|
| 搜索代碼 | 在所有 GitHub 存儲庫中搜索代碼 | "搜索所有包含 authentication 的 Python 代碼" |
| 搜索存儲庫 | 按關鍵字搜索 repo | "搜索 stars > 1000 的 React 項目" |
| 搜索用戶 | 查找 GitHub 用戶 | "搜索位於台灣的開發者" |
| 搜索 Issue | 跨存儲庫搜索 Issue | "搜索提到 memory leak 的 Issue" |
| 搜索 PR | 跨存儲庫搜索 PR | "搜索我在所有 repo 中的 PR" |

---

## 👥 協作功能

| 功能 | 說明 | 範例指令 |
|------|------|----------|
| 獲取用戶資訊 | 查看當前登入用戶 | "我的 GitHub 帳號資訊" |
| 團隊成員 | 獲取組織團隊成員列表 | "列出 dev-team 的所有成員" |
| 指派 Copilot | 讓 GitHub Copilot 處理 Issue | "讓 Copilot 處理 Issue #50" |
| 請求 Copilot 審查 | 讓 Copilot 審查 PR | "請求 Copilot 審查 PR #12" |

---

## 💡 實用範例總整理

### 存儲庫操作
```
"創建一個新的私有存儲庫叫 my-project"
"Fork tensorflow/tensorflow 到我的帳號"
"搜索有關 vue.js 的存儲庫，按 stars 排序"
```

### 文件操作
```
"讀取 src/index.js 的內容"
"創建 .gitignore 文件，忽略 node_modules"
"更新 package.json 的版本號為 2.0.0"
```

### 分支與提交
```
"列出所有分支"
"從 main 創建 hotfix/bug-123 分支"
"顯示最近 5 個 commit 的詳情"
```

### Pull Request
```
"創建 PR 從 develop 合併到 main"
"列出所有待審查的 PR"
"查看 PR #42 的代碼變更"
"使用 squash 方式合併 PR #15"
"批准 PR #20 並添加評論"
```

### Issue 管理
```
"創建一個 bug Issue，標題是「登入頁面無法顯示」"
"列出所有帶有 high-priority 標籤的 Issue"
"關閉 Issue #30，原因是已完成"
"在 Issue #10 添加評論說明目前進度"
```

### 搜索
```
"搜索包含 useState 的 TypeScript 代碼"
"搜索 facebook 組織中的所有存儲庫"
"搜索 followers > 1000 的用戶"
```

---

## 📝 注意事項

1. **權限要求**：某些操作需要對應的 Token 權限
   - 創建/刪除存儲庫需要 `repo` 或 `Administration` 權限
   - 讀取私有存儲庫需要 `repo` 權限
   
2. **速率限制**：GitHub API 有請求頻率限制
   - 認證用戶：每小時 5000 次請求
   - 搜索 API：每分鐘 30 次請求

3. **最佳實踐**
   - 使用分頁避免一次獲取過多數據
   - 搜索時使用精確的查詢條件
   - 創建 PR 前先搜索是否有模板文件

---

## 🔗 相關資源

- [GitHub REST API 文檔](https://docs.github.com/en/rest)
- [GitHub MCP Server](https://github.com/github/github-mcp-server)
- [Model Context Protocol](https://modelcontextprotocol.io/)

---

*最後更新：2026-01-13*
