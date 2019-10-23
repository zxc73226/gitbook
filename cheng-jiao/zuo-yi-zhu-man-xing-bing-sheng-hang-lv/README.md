---
description: 製作一張柱狀圖
---

# 慢性病盛行率

## 海報

#### 96年 20歲以上慢性病盛行率

![](../../.gitbook/assets/man-xing-bing-jian-yi-ban.png)

## 實作步驟

### 1. 製作數據圖

{% page-ref page="xiang-qi-pian.md" %}

### 2. 設定回應流程

{% page-ref page="liu-cheng-qi-pian.md" %}

### 3. 結果

{% page-ref page="zuo-pin-cheng.md" %}

## 優化圖表

![](../../.gitbook/assets/man-xing-bing-wan-zheng-ban%20%281%29.png)

### 比例尺 Scale

#### 用來調整軸座標顯示的格式

![&#x53C3;&#x8003;&#x5716;&#x793A;](../../.gitbook/assets/tu-bi-li-bi-li-chi.png)

| 列表 | 設定值 |
| :--- | :--- |
| 欄位 | prevalenceRate |
| 類型 | linear |
| 刻度間距 | 2.5 |
| 最大值 | 25 |
| 格式化函數 | `function(row) { return row + '%'; }` |

![&#x6BD4;&#x4F8B;&#x5C3A;&#x8A2D;&#x5B9A;&#x5B8C;&#x6210;&#x7684;&#x6A23;&#x5B50;](../../.gitbook/assets/man-xing-bing-bi-li-chi-she-ding.png)

### 設定圖示

#### 用來呈現圖表內容的輔助圖示

![&#x53C3;&#x8003;&#x5716;&#x793A;](../../.gitbook/assets/man-xing-bing-she-ding-tu-shi.png)

![](../../.gitbook/assets/man-xing-bing-tu-shi-she-ding-kuang.png)

| 列表 | 設定值 |
| :--- | :--- |
| 是否啟用 | ☑ 啟用 |
| 欄位 | project |
| 位置 | 下 |
| 排版 | 水平  |
| 文字樣式 - 對齊 | 置左 |
| 文字樣式 - 大小 | 30 |
| 文字樣式 - 粗體 | 粗體 |

![&#x5716;&#x8868;&#x6210;&#x54C1;](../../.gitbook/assets/man-xing-bing-wan-zheng-ban%20%281%29.png)

### 儲存設定

![&#x9EDE;&#x64CA;&#x5132;&#x5B58;](../../.gitbook/assets/xuan-dan-lie-biao-chu-cun%20%281%29.png)

