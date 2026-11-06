# Travel 旅遊行程

> 🌐 **線上總覽：[https://jzx0930.github.io/Travel/](https://jzx0930.github.io/Travel/)**

每一趟旅程一個 HTML 檔，首頁 `index.html` 是卡片總表。推上 GitHub 後由 GitHub Pages 自動發布。

## 行程列表

| 日期 | 行程 | 線上頁面 |
|---|---|---|
| 2026/10/17–10/20 | 胡志明市 4 天 3 夜自由行 | [開啟](https://jzx0930.github.io/Travel/2026-10-17_hochiminh_4d3n.html) |
| 2026/10/24–10/25 | 玖壹壹演唱會 ＋ 萬里沐舍溫泉 2 天 1 夜 | [開啟](https://jzx0930.github.io/Travel/2026-10-24_hotspring_911concert.html) |
| 2026/11/08 | 基隆一日遊：正濱漁港・信二防空洞・基隆塔・廟口夜市 | [開啟](https://jzx0930.github.io/Travel/2026-11-08_keelung_daytrip.html) |

## 檔案結構

```
index.html                           首頁（行程卡片總表）
README.md                            本檔
2026-10-17_hochiminh_4d3n.html       胡志明市
2026-10-24_hotspring_911concert.html 玖壹壹＋溫泉
2026-11-08_keelung_daytrip.html      基隆一日遊
images/                              本機圖片（店家縮圖、購物清單照片）
```

## 新增行程

1. 複製任一行程 HTML，檔名用 `YYYY-MM-DD_地點_天數.html`。
2. 在 `index.html` 的 `.grid` 內加一張 `.card`（複製現有卡片改標題、日期、連結）。
3. 在上面的「行程列表」補一列。
4. GitHub Desktop 推上去，約 1 分鐘後 Pages 更新。

## 頁面慣例

- 每頁上方導覽列 `#catnav`：分類區塊（景點／餐廳／甜點／咖啡／停車…）在前、每日時間軸在後，最後是出發前清單。
- 卡片 `.fcard`：縮圖 ＋ 名稱 ＋ 說明 ＋ 連結（📍 Maps／📷 IG／📖 介紹）。縮圖優先用店家官網或 Wikimedia Commons（卡片下方標圖源），IG 的圖片網址會過期不直接用。
- 右下角「☰ 回到分類」浮動按鈕，捲離導覽列時出現。
- 時間軸 `.event`：時間 ＋ 標題 ＋ 說明 ＋ 按鈕列；已訂位／指定店家會標 ✅。
