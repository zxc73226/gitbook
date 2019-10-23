# 環狀箱型圖

圖片預覽

![&#x25B2;  &#x74B0;&#x72C0;&#x7BB1;&#x5F62;&#x5716;](../../.gitbook/assets/ji-zuo-biao-xiang-xing-tu.png)



### 資料源

```javascript
[{
  x: 'Oceania',
  low: 1,
  q1: 9,
  median: 16,
  q3: 22,
  high: 24
}, {
  x: 'East Europe',
  low: 1,
  q1: 5,
  median: 8,
  q3: 12,
  high: 16
}, {
  x: 'Australia',
  low: 1,
  q1: 8,
  median: 12,
  q3: 19,
  high: 26
}, {
  x: 'South America',
  low: 2,
  q1: 8,
  median: 12,
  q3: 21,
  high: 28
}, {
  x: 'North Africa',
  low: 1,
  q1: 8,
  median: 14,
  q3: 18,
  high: 24
}, {
  x: 'North America',
  low: 3,
  q1: 10,
  median: 17,
  q3: 28,
  high: 30
}, {
  x: 'West Europe',
  low: 1,
  q1: 7,
  median: 10,
  q3: 17,
  high: 22
}, {
  x: 'West Africa',
  low: 1,
  q1: 6,
  median: 8,
  q3: 13,
  high: 16
}]
```



### 內距

```javascript
50, 50, 100
```



### 前置處理函數 Transform

數據加工（ map ）

| 列表 | 設定值 |
| :--- | :--- |
| 類型 | 數據加工 |
| 加工函數 | `function callback(obj) {  obj.range = [obj.low, obj.q1, obj.median, obj.q3, obj.high];  return obj; }` |



### 比例尺 Scale

#### range（ Y軸 ）

| 列表 | 設定值 |
| :--- | :--- |
| 欄位 | range |
| 類型 | linear |
| 優化數據範圍 | 開啟 |
| 最大值 | 35 |



### 圖 Geom

#### K線圖（ schema ）

| 列表 | 設定值 |
| :--- | :--- |
| 欄位 | x\*range |
| 類型 | K線圖 |
| 顏色欄位 | x |
| 形狀 | box |
| 大小 | 60 |



### 圖示 Legend

| 列表 | 設定值 |
| :--- | :--- |
| 啟用 | 開啟 |
| 欄位 | x |
| 位置 | 下 |
| 排版 | 水平 |
| 自動換行 | 開啟 |



### 極座標 Coord

| 列表 | 設定值 |
| :--- | :--- |
| 類型 | 極座標系 |
| 空心圓半徑 | 0.4 |



{% page-ref page="./" %}

