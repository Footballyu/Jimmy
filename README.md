# 寰圖｜全球地理快速查詢

互動式世界地圖網站，使用繁體中文介面。

## 第一版功能

- 可點選世界地圖上的國家
- 全球國家搜尋
- 世界 → 國家平滑縮放定位
- 國家基本資訊：首都、人口、面積、貨幣、語言、時區、電話碼、國家代碼
- 洲別 / 次區域麵包屑導覽
- 足球 FIFA、籃球 FIBA、棒球 WBSC、軍力 GFP 世界排名區塊
- 最近探索紀錄保存在瀏覽器 localStorage
- 桌機 / 平板 / 手機響應式版面
- 深色 Dashboard 視覺

## 排名資料

`rankings.json` 獨立保存四類世界排名，以 ISO Alpha-3 國家代碼為索引。排名資料會隨官方公布而改變，因此目前先保留資料結構，後續再加入可驗證的最新資料。

## GitHub Pages

此專案是純靜態網站，可直接使用 GitHub Pages 發布。

GitHub Repository：`Footballyu/Jimmy`

預期 Pages 網址：`https://footballyu.github.io/Jimmy/`

第一次需要在 GitHub Repository 的 `Settings → Pages` 將發布來源設為 `Deploy from a branch`，Branch 選 `main`、Folder 選 `/ (root)`，之後更新 main 分支即可自動重新發布。
