# 圖像編輯器篇

## 進入圖像編輯器

### 1. 開啟選單列表

![&#x9996;&#x9801;](../../.gitbook/assets/gosu_bar.png)

### 2. 進入圖像編輯器

![&#x9078;&#x55AE;&#x5217;&#x8868;](../../.gitbook/assets/gosu-xuan-dan-lie-biao-tu.png)

### 3. 新增卡片

![&#x9EDE;&#x64CA;&#x65B0;&#x589E;&#x5361;&#x7247;&#x6309;&#x9215;](../../.gitbook/assets/ka-pian-tu-02.png)



### 4. 進入卡片

![&#x9EDE;&#x64CA;&#x9032;&#x5165;](../../.gitbook/assets/tu-xiang-jin-ru-ka-pian.png)

![](../../.gitbook/assets/tu-xiang-ka-pian.png)

## 卡片設定

### 卡片標題

| 列表 | 設定值 |
| :--- | :--- |
| 標題 | 性向測驗 |

### 卡片內文

| 列表 | 設定值 |
| :--- | :--- |
| 內文 | `現實型：8 | 研究型：8 藝術型：5 | 社會型：3 企業型：9 | 傳統型：6` |

{% hint style="info" %}
此處設定值是依照資料設定
{% endhint %}

### 替代文字

| 列表 | 設定值 |
| :--- | :--- |
| 替代文字 | 性向測驗 |

## 按鈕設定

### 按鈕1

| 列表 | 設定值 |
| :--- | :--- |
| 類型 | 連結 |
| 按鈕文字 | 測驗來源 |
| 訊息內容 | [`https://www.arealme.com/career/zh/`](https://www.arealme.com/career/zh/) |

![](../../.gitbook/assets/xing-xiang-ce-yan-ka-pian-nei-rong.png)

## 圖表

### 新增圖表

![](../../.gitbook/assets/tu-biao%20%281%29.png)

#### 拖曳出一個圖表區塊

![](../../.gitbook/assets/xing-xiang-ce-yan-tu-biao.png)

## 圖表區塊 - 設定值

### 資料設定

![&#x9EDE;&#x64CA;&#x53F3;&#x5074; &amp;lt;&amp;gt;&#xFF0C;&#x53EF;&#x4EE5;&#x5C55;&#x958B;](../../.gitbook/assets/tu-biao-zi-liao.png)

```javascript
[
{project: '現實',fraction: 8},
{project: '研究',fraction: 8},
{project: '藝術',fraction: 5},
{project: '社會',fraction: 3},
{project: '企業',fraction: 9},
{project: '傳統',fraction: 6}
]

/* 
[
{project: '項目',fraction:'分數'}
]
*/
```

### 內距 - 說明

![](../../.gitbook/assets/tu-biao-nei-ju.png)

![&#x53C3;&#x8003;&#x5716;&#x4F8B;](../../.gitbook/assets/tu-bi-li-nei-ju.png)

### 內距 - 設定值

{% hint style="info" %}
### 上 , 右 , 下 , 左 40, 40, 40, 40

#### 或

### 上右下左 40
{% endhint %}

## 圖 Geom

![&#x53C3;&#x8003;&#x5716;&#x4F8B;](../../.gitbook/assets/tu-bi-li-xin-zeng-geom.png)

### 1. 區域圖 （area）

| 列表 | 設定值 |
| :--- | :--- |
| 欄位 | project\*fraction |
| 類型 | 區域圖（area） |

![](../../.gitbook/assets/xing-xiang-ce-yan-qu-yu-tu.png)

## 比例尺 Scale

![&#x53C3;&#x8003;&#x5716;&#x4F8B;](../../.gitbook/assets/tu-bi-li-bi-li-chi.png)

### 比例尺 - 設定值

| 列表 | 設定值 |
| :--- | :--- |
| 欄位 | fraction |
| 類型 | linear |
| 最小值 | 0 |
| 最大值 | 10 |

![](../../.gitbook/assets/xing-xiang-ce-yan-bi-li-chi.png)

## 設定極坐標

![](../../.gitbook/assets/xing-xiang-ce-yan-she-ding-ji-zuo-biao.png)

![](../../.gitbook/assets/xing-xiang-ce-yan-ji-zuo-biao-she-ding.png)

### 設定極坐標 - 設定值

| 列表 | 設定值 |
| :--- | :--- |
| 類型 | 極坐標系 \(polar\) |

![&#x6975;&#x5EA7;&#x6A19;&#x8A2D;&#x5B9A;&#x503C;](../../.gitbook/assets/xing-xiang-ce-yan-she-ding-ji-zuo-biao-tu.png)

## 基本屬性

![](../../.gitbook/assets/ji-ben-shu-xing.png)

### 基本屬性 - 設定值

| 列表 | 設定值 |
| :--- | :--- |
| X座標 | 0 |
| Y座標 | 0 |
| 寬度 | 450 |
| 高度 | 300 |

![](../../.gitbook/assets/xing-xiang-ce-yan-jian-yi-ban.png)

## 儲存圖片

![&#x9EDE;&#x64CA;&#x5132;&#x5B58;](../../.gitbook/assets/xuan-dan-lie-biao-chu-cun%20%281%29.png)

## [優化說明](https://imaging.gitbook.io/imaging/~/edit/drafts/-LOLfCUlIrxhacuo0_Mg/cheng-jiao/zuo-yi-lei-xing-xiang#hua-biao)

{% page-ref page="./" %}

### [點我](https://imaging.gitbook.io/imaging/~/edit/drafts/-LOLfCUlIrxhacuo0_Mg/cheng-jiao/zuo-yi-lei-xing-xiang#hua-biao) 進入優化說明

