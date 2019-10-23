# 基礎折線圖

### 圖片預覽

![&#x25B2;  &#x57FA;&#x790E;&#x6298;&#x7DDA;&#x5716;](../../.gitbook/assets/ji-chu-zhe-xian-tu.png)



### 資料源

```javascript
[
{ year: '1991', value: 3 },
{ year: '1992', value: 4 },
{ year: '1993', value: 3.5 },
{ year: '1994', value: 5 },
{ year: '1995', value: 4.9 },
{ year: '1996', value: 6 },
{ year: '1997', value: 7 },
{ year: '1998', value: 9 },
{ year: '1999', value: 13 }
]
```



### 內距

```javascript
40,20,50,50
```



### 比例尺 Scale

#### Year 比例尺（ X軸 ）

| 列表 | 設定值 |
| :--- | :--- |
| 欄位 | year |
| 類型 | linear |
| 刻度間距 | 1 |
| 優化數據範圍 | 開啟 |

#### Value 比例尺（ Y軸 ）

| 列表 | 設定值 |
| :--- | :--- |
| 欄位 | value |
| 類型 | linear |
| 刻度間距 | 1 |
| 最小值 | 0 |
| 最大值 | 13 |
| 優化數據範圍 | 開啟 |



### 圖 Geom

#### 線圖（ Line ）

| 列表 | 設定值 |
| :--- | :--- |
| 欄位 | year\*value |
| 類型 | 線圖 |

#### 點圖（ point ）

| 列表 | 設定值 |
| :--- | :--- |
| 欄位 | year\*value |
| 類型 | 點圖 |
| 形狀 | circle |
| 大小 | 4 |
| 樣式 - 顏色 | \#ffffff |
| 樣式 - 寬度 | 1 |



{% page-ref page="./" %}

