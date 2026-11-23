# llm-casebook

Local LLM test casebook: every test question, each model's answers and the grading result, as a static
site for GitHub Pages.

**Site:** https://mtk-openwrt.github.io/llm-casebook/

本地 LLM 測試題庫：16 個場域（智慧家庭小家庭／大家庭＋14 個產業場域）的全部題目、各受測模型的作答與評分結果。
每一題都有自己的連結（`#<場域>-<題號>`，例如 `#agri-AGR-L3-04`），可產生 QR code 分享。

- 題目中的人物、公司、病歷、設備與數據皆為虛構，供測試使用。
- 受測模型皆在本地以 llama.cpp 執行（GGUF 量化）；評分＝自動檢查＋AI 裁判（依各題評分標準）。
- 本 repo 只放產生好的網站檔案（`index.html`、`index.json`、`answers/`），由測試專案的匯出工具產生。
