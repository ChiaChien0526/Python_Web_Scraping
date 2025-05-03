# Project Gutenberg

本專案旨在從 Project Gutenberg 爬取中文書籍，共計 **363 本**，並整理為可閱讀與後續處理的格式。

---

## 安裝套件

以下為本專案所需安裝的套件與建議版本：

- `requests`（版本號：2.32.3）
- `beautifulsoup4`（版本號：4.9.1）
- `regex`（版本號：2020.6.8）

可使用以下指令安裝：

```bash
pip install requests==2.32.3
pip install beautifulsoup4==4.9.1
pip install regex==2020.6.8
```

---

## 使用方式

1. 安裝上述套件。
2. 執行主程式（例如 `ProjectGutenberg.ipynb`）。
3. 爬取結果將儲存至指定資料夾（`project_gutenberg/`）。

---

## 成果展示

📽 [爬蟲執行成果影片](https://youtu.be/ewJCDOyd7gI)

---

## 資料來源

- [Project Gutenberg](https://www.gutenberg.org/)
- [中文書籍語言分類頁](https://www.gutenberg.org/browse/languages/zh)
- 本專案專注於爬取語言為「中文」的電子書
- 透過篩選 metadata 與自動下載處理

---

## ⚠ 注意事項

- 部分書籍因格式或編碼問題可能無法正常解析，已進行排除處理
- 若爬取速度過快可能導致封鎖，建議加入延遲

---

## 專案結構

```
WEB_SCRAPING/
├── project_gutenberg/
├── ProjectGutenberg.ipynb
└── README.md
```

---
