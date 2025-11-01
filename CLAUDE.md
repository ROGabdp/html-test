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

## 架構原則

**關注點分離 (Separation of Concerns)**：
- 網頁結構只在 HTML 中定義
- 樣式只在 CSS 中定義
- 互動功能只在 JavaScript 中實作

## 程式碼規範

- **語言設定**: 繁體中文（zh-TW）- 所有 `lang` 屬性和內容都應使用 zh-TW
- **路徑慣例**: 所有相對路徑必須使用 `./` 前綴以保持一致性（例如：`./about.html`、`./style.css`、`./images/goal1.png`）
- **頁面結構**: 每個 HTML 頁面都應包含導航連結以連接到網站中的其他頁面
- **樣式管理**: 使用 `style.css` 作為共用樣式表，所有 HTML 頁面都應連結此檔案
- **字體設定**: CSS 中使用 Arial 搭配「微軟正黑體」(Microsoft JhengHei) 以支援繁體中文顯示
- claude.md 裡面的說明也用繁體中文