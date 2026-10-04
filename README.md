# Tabview-Youtube Slim

精簡版 YouTube Tabview userscript。

這個 fork 的正式安裝版本只保留 Tabview 相關功能，並預設在影片頁顯示「留言」分頁。

## 保留功能

- YouTube 影片頁 Tabview 介面
- 資訊 / 留言 / 推薦影片 / 播放清單等 Tabview 功能
- 預設自動切換到留言分頁
- 原本 Tabview 的版面與必要相容處理

## 已移除

- 影片下載與第三方下載網站
- 截圖
- 播放速度控制
- Picture-in-Picture / Loop 工具箱
- 主題切換
- 彩色進度條
- 廣告標記
- 與上述功能相關的多餘 userscript 權限

## 安裝

需要 Tampermonkey、Violentmonkey 或其他相容 userscript 管理器。

[安裝 Tabview-Youtube Slim](https://github.com/crytropy/Tabview-Youtube/raw/generated-files/generated/Tabview-Youtube.user.js)

## 預設分頁

在 `userscript/Tabview-Youtube.user.js` 頂部可以找到：

```js
const DEFAULT_TAB = "comments";
```

- `"comments"`：影片載入後預設顯示留言
- `"none"`：不強制指定預設分頁

## 原始碼

精簡版來源：

`userscript/Tabview-Youtube.user.js`

可安裝版本：

`generated/Tabview-Youtube.user.js`

原 fork 中其他上游 Tabview-Youtube 檔案仍保留作為參考。
