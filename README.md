# Nestiee 燕窩回禮 Landing Page

為 30 歲代香港準新娘設計的婚禮回禮 Landing Page，風格定位：**Quiet Luxury · Effortless Elegance**。

## 檔案

| 檔案 | 說明 |
|---|---|
| `nestiee-wedding-landing.html` | 完整 HTML 片段，可直接貼入 WordPress |

## WordPress / X Theme / Cornerstone 使用方式

1. 在 Cornerstone 頁面編輯器中，加入 **Raw Content**（或 **HTML**）元素
2. 開啟 `nestiee-wedding-landing.html`，**全選複製**全部內容
3. 貼入 Raw Content 元素中，儲存並預覽
4. 搜尋 `REPLACE_WHATSAPP`，替換為你的 WhatsApp 號碼（例：`85212345678`，不含 `+` 或空格）
5. 將佔位圖片 URL 替換為實際產品攝影

### 相容性說明

- 所有樣式與腳本均包在 `#nestiee-landing` 容器內，並使用 `nestiee-` 前綴，避免與 X Theme / Cornerstone 預設樣式衝突
- 字體透過 Google Fonts CDN 載入（Cormorant Garamond + Noto Serif TC）
- 互動功能（Accordion、份量 Tab、見證 Carousel、進場動畫）均為原生 JavaScript，無外部依賴
- 建議在 Cornerstone 頁面設定中關閉該頁面的預設 padding，讓 Hero 全寬顯示

## 頁面結構

1. Hero — 全屏分欄，Ghost Button CTA
2. 品牌承諾 — 三欄線條插圖
3. 口味 — 橫向滑動卡片
4. 份量 — Tab 切換描述（無價格）
5. 見證 — Carousel（5 秒自動播放，hover 暫停）
6. Ingredients First — 深色 2×2 Grid
7. 品鑑禮盒 — 左右分欄，唯一填充 CTA
8. FAQ — Accordion
9. CTA Footer — 極簡收尾
