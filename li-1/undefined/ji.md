# 基礎圓餅圖

### 圖片預覽

![&#x25B2;  &#x57FA;&#x790E;&#x5713;&#x9905;&#x5716;](../../.gitbook/assets/ji-chu-yuan-bing-tu.png)

### 資料源

```javascript
[{
  item: '事例一',
  count: 40,
  percent: 0.4
}, {
  item: '事例二',
  count: 21,
  percent: 0.21
}, {
  item: '事例三',
  count: 17,
  percent: 0.17
}, {
  item: '事例四',
  count: 13,
  percent: 0.13
}, {
  item: '事例五',
  count: 9,
  percent: 0.09
}]
```



### 內距

```javascript
20, 20, 50,20
```



### 圖 Geom

#### 柱狀圖（ interval ）

| 列表 | 設定值 |
| :--- | :--- |
| 欄位 | count |
| 類型 | 柱狀圖 |
| 顏色欄位 | item |
| 調整欄位 | 堆疊 \| stack |
| 樣式 - 顏色 | \#ffffff |
| 樣式 - 寬度 | 2 |



### 圖示 Legend

| 列表 | 設定值 |
| :--- | :--- |
| 啟用 | 開啟 |
| 欄位 | count |
| 位置 | 下 |
| 排版 | 水平 |
| 垂直偏移量 | -40 |



### 極坐標 Coord

| 列表 | 設定值 |
| :--- | :--- |
| 類型 | 圓餅圖 |



{% page-ref page="./" %}

