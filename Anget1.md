# Website 專案紀錄

## 專案概要

這是一個單頁式靜態網站原型。頁面使用 Bootstrap 的 Carousel 元件，輪播顯示三張橫幅圖片，並在輪播下方保留一個標題區塊。

## 技術與相依性

- HTML5
- [Bootstrap 5.1.1](https://getbootstrap.com/)（透過 jsDelivr CDN 載入 CSS 與 Bundle JavaScript）
- 本地圖片素材：PNG

目前沒有套件管理、建置流程、後端服務或本地 CSS／JavaScript 檔案。

## 專案結構

```text
website/
├── index.html          # 首頁與 Bootstrap 輪播設定
├── image/
│   ├── banner1.png     # 輪播第一張圖片（1408 × 768）
│   ├── banner2.png     # 輪播第二張圖片（1408 × 768）
│   └── banner3.png     # 輪播第三張圖片（1408 × 768）
└── README.md           # 本文件
```

## 頁面功能

`index.html` 目前包含：

1. 響應式 viewport 設定。
2. Bootstrap `carousel-fade` 輪播元件。
3. 三張輪播圖片，第一張預設為啟用狀態。
4. 上一張／下一張導覽按鈕。
5. 一個暫用標題：`Hello, world!`。

## 本機預覽

可直接以瀏覽器開啟 `index.html`。若需較接近部署環境的方式，可在專案根目錄啟動任一靜態檔案伺服器，再瀏覽其提供的網址。

例如已安裝 Python 時：

```bash
python3 -m http.server 8000
```

然後開啟 `http://localhost:8000`。

## 目前可改善項目

- 將文件的 `lang="en"`、頁面標題與按鈕輔助文字改為實際網站語系與內容。
- 將圖片的 `alt="..."` 改成具描述性的替代文字，提升無障礙性。
- 視設計需求補上導覽列、內容區塊與頁尾。
- 建立本地樣式檔，統一調整輪播高度、文字與版面。
- 若網站需離線使用或避免 CDN 相依，可改為本地管理 Bootstrap 資源。

## 維護備註

- 輪播的目標 ID 為 `carouselExampleFade`；若更改 ID，前後控制按鈕的 `data-bs-target` 也必須同步更新。
- 圖片路徑採相對路徑 `image/banner*.png`；移動檔案時請一併更新 `index.html`。
- Bootstrap 的 JavaScript 使用 bundle 版本，已包含 Carousel 運作所需的相依套件。

---

文件建立日期：2026-08-07
## Github推送地址
User Name:winnie931226-eng
專案名稱： -i
HTTPS:https://github.com/winnie931226-eng/-i.git
SSH:git@github.com:winnie931226-eng/-i.git