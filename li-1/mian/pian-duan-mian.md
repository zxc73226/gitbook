# 片段面積圖

### 圖片預覽

![&#x25B2;  &#x7247;&#x6BB5;&#x9762;&#x7A4D;&#x5716;](../../.gitbook/assets/pian-duan-mian-ji-tu.png)

### 資料源

```javascript
[{
  "year": "1986",
  "ACME": 162,
  "Compitor": 42
}, {
  "year": "1987",
  "ACME": 134,
  "Compitor": 54
}, {
  "year": "1988",
  "ACME": 116,
  "Compitor": 26
}, {
  "year": "1989",
  "ACME": 122,
  "Compitor": 32
}, {
  "year": "1990",
  "ACME": 178,
  "Compitor": 68
}, {
  "year": "1991",
  "ACME": 144,
  "Compitor": 54
}, {
  "year": "1992",
  "ACME": 125,
  "Compitor": 35
}, {
  "year": "1993",
  "ACME": 176,
  "Compitor": 66
}, {
  "year": "1994",
  "ACME": 156
}, {
  "year": "1995",
  "ACME": 195
}, {
  "year": "1996",
  "ACME": 215
}, {
  "year": "1997",
  "ACME": 176,
  "Compitor": 36
}, {
  "year": "1998",
  "ACME": 167,
  "Compitor": 47
}, {
  "year": "1999",
  "ACME": 142
}, {
  "year": "2000",
  "ACME": 117
}, {
  "year": "2001",
  "ACME": 113,
  "Compitor": 23
}, {
  "year": "2002",
  "ACME": 132
}, {
  "year": "2003",
  "ACME": 146,
  "Compitor": 46
}, {
  "year": "2004",
  "ACME": 169,
  "Compitor": 59
}, {
  "year": "2005",
  "ACME": 184,
  "Compitor": 44
}]
```



### 內距

```javascript
40, 40, 80, 60
```



### 前置處理函數 Transform

#### 字串展開（ fold ）

| 列表 | 設定值 |
| :--- | :--- |
| 類型 | 字串展開 |
| 要展開的欄位 | ACME,Compitor |
| 保留欄位 | year |
| Key | type |
| Value | value |



### 比例尺 Scale

#### year（ X軸 ）

| 列表 | 設定值 |
| :--- | :--- |
| 欄位 | year |
| 類型 | linear |
| 刻度間距 | 1 |
| 優化數據範圍 | 開啟 |



### 圖 Geom

#### 區域圖（ area ）

| 列表 | 設定值 |
| :--- | :--- |
| 欄位 | year\*value |
| 類型 | 區域圖 |
| 顏色欄位 | type |
| 形狀 | smooth |

#### 線圖（ line ）

| 列表 | 設定值 |
| :--- | :--- |
| 欄位 | year\*value |
| 類型 | 線圖 |
| 顏色欄位 | type |
| 形狀 | smooth |
| 大小 | 2 |



### 圖示 Legend

| 列表 | 設定值 |
| :--- | :--- |
| 啟用 | 開啟 |
| 欄位 | type |
| 位置 | 下 |
| 排版 | 水平 |



{% page-ref page="./" %}

