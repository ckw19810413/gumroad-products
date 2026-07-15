# Gumroad 產品上傳包

> 三個數位商品的完整檔案，直接上傳到 Gumroad 即可。

## 快速開始

1. 參考 `gumroad-upload-guide.md` 中的完整文案（標題、描述、標籤）
2. 選擇對應產品的 ZIP 檔案
3. 上傳到 Gumroad → 設定價格 → 點擊 Publish

---

## 產品目錄

| 產品 | ZIP 檔案 | 內容 | 價格 |
|------|---------|------|------|
| 繁體 AI Prompt 庫 | [prompt-library.zip](prompt-library.zip) | 4 個 prompt 文件（100 個 prompt） | $49 |
| AI 實戰課程 | [ai-course.zip](ai-course.zip) | 課程目錄 + 4 堂課程內容 | $297 |
| 飛書模板市集 | [feishu-templates.zip](feishu-templates.zip) | 模板目錄 + 銷售儀表板範本 | $29-$69 |

## 結構

```
gumroad-products/
├── gumroad-upload-guide.md      # 完整上架文案（標題、描述、標籤）
├── products/
│   ├── prompt-library/           # 提示詞庫（上傳用）
│   │   ├── business.md           # 商務應用 prompt
│   │   ├── content.md            # 內容創作 prompt
│   │   ├── efficiency.md         # 效率工具 prompt
│   │   └── advanced.md           # 進階應用 prompt
│   ├── ai-course/                # AI 實戰課程（上傳用）
│   │   ├── COURSE_CATALOG.md     # 完整課程目錄
│   │   └── unit1/unit2/          # 課程內容
│   └── feishu-templates/         # 飛書模板市集（上傳用）
│       ├── README.md             # 模板目錄
│       └── sales-dashboard.md    # 銷售儀表板範本
├── prompt-library.zip            # 上傳用（壓縮檔）
├── ai-course.zip                 # 上傳用（壓縮檔）
└── feishu-templates.zip          # 上傳用（壓縮檔）
```

## 注意事項

- 課程目前包含第 1-2 單元部分內容（session 1-2 + session 4）
- 第 3-4 單元內容尚在開發中，上架時可選擇：
  - 先上架現有內容（第 1-2 單元）
  - 或等全部 4 單元完成後再上架

---
建立日期：2026-07-15