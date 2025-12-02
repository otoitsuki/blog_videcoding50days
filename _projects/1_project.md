---
layout: page
title: Jekyll 使用心得
description: 靜態網站生成器的實戰經驗
img: assets/img/12.jpg
importance: 1
category: work
---

## 為什麼選擇 Jekyll？

Jekyll 是一個基於 Ruby 的靜態網站生成器，特別適合用來建立部落格和個人網站。搭配 GitHub Pages 可以免費託管，對於開發者來說非常方便。

### 優點

- **簡單直覺**：使用 Markdown 撰寫內容，不需要資料庫
- **高度客製化**：透過 Liquid 模板引擎，可以靈活設計版面
- **效能優異**：生成的是純靜態 HTML，載入速度快
- **免費託管**：GitHub Pages 原生支援 Jekyll

### 學習曲線

剛開始接觸 Jekyll 時，需要理解幾個核心概念：

1. **Front Matter**：每個頁面開頭的 YAML 區塊，用來定義頁面屬性
2. **Layouts**：控制頁面整體結構的模板
3. **Includes**：可重複使用的元件
4. **Collections**：如 `_posts`、`_projects` 等內容集合

## 實用技巧

### 本地開發

```bash
bundle exec jekyll serve --livereload
```

加上 `--livereload` 可以在修改檔案後自動重新整理瀏覽器，開發體驗大幅提升。

### 目錄結構

```
├── _config.yml      # 網站設定
├── _layouts/        # 版面模板
├── _includes/       # 可重用元件
├── _posts/          # 部落格文章
├── _projects/       # 專案集合
└── assets/          # 靜態資源
```

## 結語

Jekyll 雖然不是最新潮的框架，但穩定可靠、社群資源豐富。對於想要快速建立個人網站或部落格的人來說，是個很好的選擇。
