# 📦 Gumroad 產品上傳包

> 三個數位商品的完整檔案，直接上傳到 Gumroad 即可。包含產品檔、封面圖、完整上架文案。

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Last Updated](https://img.shields.io/badge/Last_Updated-2026--07-green.svg)]()
[![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)]()

## 📋 目錄

- [快速開始](#快速開始)
- [產品目錄](#產品目錄)
- [專案結構](#專案結構)
- [上架指南](#上架指南)
- [注意事項](#注意事項)
- [關鍵功能](#關鍵功能)
- [適用場景](#適用場景)
- [相關專案](#相關專案)
- [授權條款](#授權條款)

## 🚀 快速開始

```bash
# 1. 克隆此倉庫
git clone https://github.com/ckw19810413/gumroad-products.git
cd gumroad-products

# 2. 查看上架指南
cat gumroad-upload-guide.md

# 3. 選擇對應產品上傳
# 上傳 ZIP 檔案到 Gumroad → 設定價格 → 點擊 Publish
```

## 📦 產品目錄

| 產品 | ZIP 檔案 | 內容 | 價格 |
|------|---------|------|------|
| 💬 繁體 AI Prompt 庫 | [prompt-library.zip](prompt-library.zip) | 4 個 prompt 文件（100 個 prompt） | $49 |
| 🎓 AI 實戰課程 | [ai-course.zip](ai-course.zip) | 課程目錄 + 4 堂課程內容 | $297 |
| 🚀 飛書模板市集 | [feishu-templates.zip](feishu-templates.zip) | 模板目錄 + 銷售儀表板範本 | $29-$69 |

## 📁 專案結構

```
gumroad-products/
├── products/                 # 產品原始檔
│   ├── prompt-library/      # 提示詞庫
│   │   ├── business.md      # 商務應用 prompt
│   │   ├── content.md       # 內容創作 prompt
│   │   ├── efficiency.md    # 效率工具 prompt
│   │   ├── advanced.md      # 進階應用 prompt
│   │   └── cover.png        # 產品封面圖
│   ├── ai-course/           # AI 實戰課程
│   │   ├── COURSE_CATALOG.md # 課程目錄
│   │   ├── cover.png        # 產品封面圖
│   │   └── unit1/           # 第一單元
│   └── feishu-templates/    # 飛書模板市集
│       ├── README.md
│       ├── sales-dashboard.md
│       └── cover.png
├── images/                  # 產品封面圖
│   ├── prompt-library.png
│   ├── ai-course.png
│   └── feishu-template.webp
├── *.zip                    # 上傳用壓縮檔
├── gumroad-upload-guide.md  # 完整上架文案
├── .github/                 # GitHub 設定檔
├── CODE_OF_CONDUCT.md
├── SUPPORT.md
├── LICENSE
└── README.md
```

## 📝 上架指南

1. 參考 `gumroad-upload-guide.md` 中的完整文案（標題、描述、標籤）
2. 選擇對應產品的 ZIP 檔案
3. 上傳到 Gumroad → 設定價格 → 點擊 Publish
4. 上傳對應的產品封面圖
5. 加入相關標籤以提升搜尋能見度

## ⚠️ 注意事項

- 課程目前包含第 1-2 單元部分內容（session 1-2 + session 4）
- 第 3-4 單元內容尚在開發中，上架時可選擇：
  - 先上架現有內容（第 1-2 單元）
  - 或等全部 4 單元完成後再上架

## ⭐ 關鍵功能

- 📦 **即用即用**：ZIP 檔案準備好，直接上傳
- 📝 **完整文案**：標題、描述、標籤都已撰寫
- 🎨 **專業封面圖**：每個產品都有專屬封面圖
- 🔄 **持續更新**：產品內容會持續更新

## 🎯 適用場景

- 想在 Gumroad 銷售數位商品創作者
- 想要快速上架產品的數位產品開發者
- 想測試市場需求的產品驗證
- 需要產品上架模板的初創者

## 🔗 相關專案

- [🎓 AI 實戰課程](https://github.com/ckw19810413/ai-practical-course-tw) — 繁體中文 AI 實戰課程原始檔
- [💬 繁體 AI Prompt 庫](https://github.com/ckw19810413/traditional-ai-prompt-library) — 100 個高品質 prompt
- [🚀 飛書模板市集](https://github.com/ckw19810413/feishu-template-marketplace) — 飛書/釘釘工作模板
- [📈 Product Tracking](https://github.com/ckw19810413/product-tracking) — 銷售追蹤工具

## 📜 授權條款

本專案採用 [MIT License](LICENSE) 授權。