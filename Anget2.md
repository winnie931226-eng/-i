# 泥日・小陶器製所｜一頁式廣告銷售頁

以 Bootstrap 5 製作的響應式陶藝體驗銷售頁，依照暖色、留白與手作感的設計稿切版完成。

## 使用技術

- HTML5
- Bootstrap 5.3.3（CDN）
- 自訂 CSS（`style.css`）
- Google Fonts：Noto Serif TC、Zen Maru Gothic

## 網頁區塊

1. 固定導覽列與首屏主視覺
2. 品牌起源
3. 痛點／解決方案
4. 微型器皿亮點
5. 職人製作堅持
6. 課程與預約行動呼籲
7. 頁尾與回到頂端按鈕

## 專案結構

```text
website/
├── index.html          # 頁面結構與 Bootstrap 元件
├── style.css           # 視覺樣式與響應式規則
├── image/
│   ├── banner1.png
│   ├── banner2.png
│   └── banner3.png
└── README.md
```

## 本機預覽

可直接用瀏覽器開啟 `index.html`。也可在專案根目錄執行：

```bash
python3 -m http.server 8000
```

再於瀏覽器開啟 `http://localhost:8000`。

## 上線前需替換的內容

- `index.html` 中的預約連結目前是範例信箱 `hello@niriri-pottery.example`，請改成正式信箱、表單或預約系統網址。
- 課程日期、價格與社群帳號目前是展示文案，請依實際活動更新。
- Bootstrap、Google Fonts 目前由 CDN 提供；正式網站須可連網載入這些資源。

## Github推送地址
Git user.name：<winnie931226-eng>
專案名稱：-i
HTTPS:https://github.com/winnie931226-eng/-i.git
SSH:git@github.com:winnie931226-eng/-i.git
Repository URL：https://github.com/<innie931226-eng>/<-i>.git
Git user.email：<winnie931226@gmail.com>
