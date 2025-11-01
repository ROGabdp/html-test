所有問答和標註都用繁體中文

# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 專案概述

這是一個簡單的靜態 HTML 測試專案，展示巢狀清單結構和基本導航功能。專案包含多個 HTML 頁面及頁面間的內部連結。

## 開發方式

這是純靜態 HTML 專案，沒有建置流程或相依套件。查看頁面的方式：

1. 直接用瀏覽器開啟 HTML 檔案
2. 或使用本地開發伺服器：
   - Python: `python -m http.server 8000`
   - Node.js: `npx serve .`
   - VS Code: 使用 Live Server 擴充套件

## 程式碼規範

- **語言設定**: 繁體中文（zh-TW）- 所有 `lang` 屬性和內容都應使用 zh-TW
- **路徑慣例**: 所有相對路徑必須使用 `./` 前綴以保持一致性（例如：`./about.html`、`./images/goal1.png`）
- **頁面結構**: 每個 HTML 頁面都應包含導航連結以連接到網站中的其他頁面
- claude.md裡面的說明也用繁體中文