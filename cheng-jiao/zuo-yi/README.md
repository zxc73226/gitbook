---
description: 製作一張折線圖
---

# 國中生抽菸比例

## 圖片

![](../../.gitbook/assets/chou-yan-bi-li-jian-yi-ban.png)

## 實作步驟

### 1. 製作數據圖

{% page-ref page="xiang-qi-pian-1.md" %}

### 2. 設定回應流程

{% page-ref page="liu-cheng-qi-pian.md" %}

### 3. 結果

{% page-ref page="guo-cheng.md" %}

## 優化圖表

![&#x512A;&#x5316;&#x6578;&#x64DA;&#x5716;](../../.gitbook/assets/chou-yan-bi-li-wan-zheng-ban.png)

## 比例尺 Scale 

#### 用來調整軸座標顯示的格式

![](../../.gitbook/assets/tu-bi-li-bi-li-chi.png)

![](../../.gitbook/assets/tu-bi-li-bi-li-chi-she-ding.png)

### X軸（time）- 設定值

| 列表 | 設定值 |
| :--- | :--- |
| 欄位 | date |
| 類型 | linear |
| 刻度間距 | 1 |
| 最小值 | 92 |
| 最大值 | 105 |
| 格式化函數 | `function(row) {  return row + '年'; }` |

![](../../.gitbook/assets/tu-bi-li-xzhou-bi-li-chi.png)

### Y軸（total）- 設定值

| 列表 | 設定值 |
| :--- | :--- |
| 欄位 | total |
| 類型 | linear |
| 刻度間距 | 1 |
| 最小值 | 0 |
| 最大值 | 10 |
| 格式化函數 | `function(row) {  return row + '%'; }` |

![&#x5B8C;&#x6210;](../../.gitbook/assets/chou-yan-bi-li-wan-zheng-ban.png)

### 儲存設定

![&#x9EDE;&#x64CA;&#x5132;&#x5B58;](../../.gitbook/assets/xuan-dan-lie-biao-chu-cun%20%281%29.png)

