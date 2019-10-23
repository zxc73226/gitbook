# 圖像編輯器篇

## 進入圖像編輯器

### 1. 開啟選單列表

![&#x9996;&#x9801;](../../.gitbook/assets/gosu_bar.png)

### 2. 進入圖像編輯器

![&#x9078;&#x55AE;&#x5217;&#x8868;](../../.gitbook/assets/gosu-xuan-dan-lie-biao-tu.png)

### 3. 新增海報

![&#x9EDE;&#x64CA;&#x65B0;&#x589E;&#x6D77;&#x5831;&#x6309;&#x9215;](../../.gitbook/assets/hai-bao-tu-02.png)

### 4. 進入海報

![&#x9032;&#x5165;&#x6D77;&#x5831;](../../.gitbook/assets/tu-xiang-jin-ru-ka-pian.png)

## 調整圖片高度

![&#x5BEC;x&#x9AD8;&#x53C3;&#x8003;&#x5716;](../../.gitbook/assets/xuan-dan-lie-biao-kuanxgao.png)

![](../../.gitbook/assets/man-xing-bing-diao-zheng-gao-du.png)

{% hint style="info" %}
### 1. 點擊 修改高度 （海報寬度固定1040無法變更）

### 2. 高度設定 800 
{% endhint %}

## 資料來源文字設定

### 新增文字

![&#x5DE5;&#x5177;&#x5217;&#x8868; - &#x6587;&#x5B57;](../../.gitbook/assets/wen-zi-qu-kuai.png)

#### 拖曳出一個文字區塊

![](../../.gitbook/assets/man-xing-bing-wen-zi-qu-kuai.png)

### 文字區塊 - 設定值

#### 文字相關

| 列表 | 設定值 |
| :--- | :--- |
| 文字內容 | 資料來源:政府資料開放平臺 |
| 是否自動調整字體大小 | ☐ 自訂字體大小 |
| 字體大小 | 18 |
| 粗細 | 粗體 |
| 水平對齊 | 置中對齊 |
| 垂直對齊 | 置中對齊 |

#### 基本屬性

| 列表 | 設定值 |
| :--- | :--- |
| X座標 | 740 |
| Y座標 | 0 |
| 寬度 | 300 |
| 高度 | 50 |

#### 點擊行為

| 列表 | 設定值 |
| :--- | :--- |
| 點擊行為 | 連結 |
| 連結網址 | [https://data.gov.tw/dataset/8838](https://data.gov.tw/dataset/8838) |

![](../../.gitbook/assets/man-xing-bing-wen-zi-she-ding-zhi.png)

## 圖表

### 新增圖表

![&#x5DE5;&#x5177;&#x5217;&#x8868; - &#x5716;&#x8868;](../../.gitbook/assets/tu-biao%20%281%29.png)

#### 拖曳出一個圖表區塊

![](../../.gitbook/assets/man-xing-bing-tu-biao-qu-kuai.png)

## 圖表 - 設定值

### 資料設定

![&#x9EDE;&#x64CA;&#x53F3;&#x5074; &amp;lt;&amp;gt;&#xFF0C;&#x53EF;&#x4EE5;&#x5C55;&#x958B;](../../.gitbook/assets/tu-biao-zi-liao.png)

```javascript
[
{project:'高血壓', prevalenceRate: 23.0},
{project:'高血糖', prevalenceRate: 7.6},
{project:'高血脂', prevalenceRate: 17.9},
{project:'代謝症候群', prevalenceRate: 19.0},
{project:'慢性腎臟病', prevalenceRate: 9.5}
]

/*
96年20歲以上慢性病盛行率
[{project: 項目, prevalenceRate: 盛行率(%)}]
*/
資料來源:政府資料開放平台
https://data.gov.tw/dataset/8838
```



### 內距 - 說明

![](../../.gitbook/assets/tu-biao-nei-ju.png)

![&#x5167;&#x8DDD;&#x8AAA;&#x660E;](../../.gitbook/assets/tu-bi-li-nei-ju.png)

### 內距 - 設定值

{% hint style="info" %}
## 上, 右 , 下, 左 60, 20, 95, 70
{% endhint %}

## 圖 Geom

### 1. 柱狀圖（interval）

#### 新增 Geom

![](../../.gitbook/assets/man-xing-bing-xin-zeng-geom.png)

![](../../.gitbook/assets/tu-bi-li-she-ding.png)

#### 設定值

| 列表 | 設定值 |
| :--- | :--- |
| 欄位 | project\*prevalenceRate |
| 類型 | 柱狀圖 \(interval\) |
| 顏色欄位 | project |

#### 重繪

![](../../.gitbook/assets/man-xing-bing-zhong-hui.png)

![](../../.gitbook/assets/man-xing-bing-zhu-zhuang-tu-hui-zhi.png)

## 基本屬性

![](../../.gitbook/assets/ji-ben-shu-xing.png)

### 基本屬性 - 設定值

| 列表 | 設定值 |
| :--- | :--- |
| X座標 | 0 |
| Y座標 | 0 |
| 寬度 | 1040 |
| 高度 | 800 |

## 圖層順序（注意圖層）

![&#x53C3;&#x8003;&#x5716;&#x4F8B; - &#x62D6;&#x66F3;&#x5C0D;&#x8ABF;&#x9806;&#x5E8F;](../../.gitbook/assets/tu-xiang-tu-ceng-shun-xu.png)

![](../../.gitbook/assets/man-xing-bing-jian-yi-ban.png)

## 儲存變更

![&#x9EDE;&#x64CA;&#x5132;&#x5B58;](../../.gitbook/assets/xuan-dan-lie-biao-chu-cun.png)

## [優化說明](https://imaging.gitbook.io/imaging/~/edit/drafts/-LOGQpUpTGO13MPSLT9f/cheng-jiao/zuo-yi-zhu-man-xing-bing-sheng-hang-lv#hua-biao)

{% page-ref page="./" %}

#### [點我](https://imaging.gitbook.io/imaging/~/edit/drafts/-LOGQpUpTGO13MPSLT9f/cheng-jiao/zuo-yi-zhu-man-xing-bing-sheng-hang-lv#hua-biao) 進入優化說明

