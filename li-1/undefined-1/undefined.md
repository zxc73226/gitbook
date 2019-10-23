# 擾動點圖

### 圖片預覽

![&#x25B2;  &#x64FE;&#x52D5;&#x9EDE;&#x5716;](../../.gitbook/assets/rao-dong-dian-tu.png)



### 資料源

```javascript
https://antv.alipay.com/assets/data/dv-grades.json
（ 資料來源：AntV ）

格式：
[
{Class: "Summer 2013",Grade: "C",Score: 72.5,},
{Class: "Summer 2013",Grade: "C",Score: 77.5,},
......
]
```



### 內距

```javascript
40, 40, 60, 60
```



### 比例尺 Scale

#### Class（ x軸 ）

| 列表 | 設定值 |
| :--- | :--- |
| 欄位 | Class |
| 類型 | cat |
| 刻度數量 | 5 |
| 優化數據範圍 | 開啟 |



### 軸座標 Axis

#### Score（ X軸 ）

| 列表 | 設定值 |
| :--- | :--- |
| 欄位 | Score |
| 啟用 |  開啟 |
| 位置 | left |

#### Class（ Y軸 ）

| 列表 | 設定值 |
| :--- | :--- |
| 欄位 | Class |
| 啟用 | 開啟 |
| 刻度線 - 顏色 | \#A14242 |
| 次要刻度 - 數量 | 2 |
| 次要刻度 - 顏色 | \#A14242 |



### 圖 Geom

#### 點圖（ point ）

| 列表 | 設定值 |
| :--- | :--- |
| 欄位 | Class\*Score |
| 類型 | 點圖 |
| 顏色欄位 | Grade |
| 形狀 | circle |
| 大小 | 4 |
| 調整欄位 | 擾動 \| jitter |



### 圖示 Legend

| 列表 | 設定值 |
| :--- | :--- |
| 啟用 | 開啟 |
| 欄位 | Class |
| 位置 | 下 |
| 排版 | 水平 |



{% page-ref page="./" %}



