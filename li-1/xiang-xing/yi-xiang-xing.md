# 一維箱型圖

### 圖片預覽

![&#x25B2;  &#x4E00;&#x7DAD;&#x7BB1;&#x578B;&#x5716;](../../.gitbook/assets/yi-wei-xiang-xing-tu.png)

### 資料源

```javascript
[{
  low: 1,
  q1: 9,
  median: 16,
  q3: 22,
  high: 24
}]
```



### 內距

```javascript
40, 40, 60
```



### 前置處理函數 Transform

數據加工（ map ）

| 列表 | 設定值 |
| :--- | :--- |
| 類型 | 數據加工 |
| 加工函數 | `function callback(obj) {  obj.range = [obj.low, obj.q1, obj.median, obj.q3, obj.high];  return obj; }` |



### 圖 Geom

#### K線圖（ schema ）

| 列表 | 設定值 |
| :--- | :--- |
| 欄位 | range\*1 |
| 類型 | K線圖 |
| 形狀 | box |
| 樣式 - 顏色 | \#545454 |



{% page-ref page="./" %}



