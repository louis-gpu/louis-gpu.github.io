# 尤俊傑 Louis｜個人專業網站

根據 `doc/尤俊傑.pdf` 的真實履歷內容重構之繁體中文多頁個人網站，定位為「AI 應用整合 × MIS／企業資訊系統 × 資安維運」工程人才。

## 網站架構

- `index.html`：個人定位、專業價值、四大核心能力與求職狀態
- `experience.html`：2005—2026 真實職涯時間軸與進修背景
- `projects.html`：依履歷實務整理的 AI、企業系統、IT 資安、AIoT 四大能力
- `contact.html`：真實聯絡方式、期望職務與工作偏好
- `doc/尤俊傑.pdf`：完整履歷 PDF

## 設計重點

- 深墨綠、螢光綠與米白配色，建立兼具技術感與可靠度的個人品牌
- 全站響應式設計，支援桌機、平板與手機
- 語意化 HTML、鍵盤焦點、跳至內容連結與適當 ARIA 標示
- 遵守 `prefers-reduced-motion`，降低動態效果造成的不適
- 自動標示目前頁面、行動版導覽與捲動顯示動畫
- 電話、電子郵件與履歷 PDF 皆可直接開啟

## 本機預覽

網站沒有建置流程，可直接開啟 `index.html`，或在專案目錄執行：

```powershell
python -m http.server 8000
```

再瀏覽 `http://localhost:8000`。

## 維護提醒

1. 職涯與證照更新時，同步修改各頁內容及 `doc/尤俊傑.pdf`。
2. 若有可公開的 GitHub、LinkedIn 或作品連結，可加入 `contact.html` 與 `projects.html`。
3. 目前使用 Google Fonts；若需完全離線，可下載字型至本機並修改 `css/styles.css` 的字型來源。

## 部署

此專案為純靜態網站，可直接部署至 GitHub Pages、Cloudflare Pages 或 Netlify。
