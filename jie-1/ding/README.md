# 進階設定說明（規劃中）

### 圖片預覽

![&#x8CC7;&#x6599;&#x6E90;&#x8A2D;&#x5B9A;](../../.gitbook/assets/zi-yuan.png)

### 宣告參數

#### 新增參數

1. key（ 識別碼，由英文或數字組成，開頭必須英文 ） 例如：Example1 
2. 中文（ 中文說明 ） 例如：例子1 
3. 預設值（ 若沒有給值，則套用預設值 ） 例如： 我是預設值

#### 引入參數

```javascript
${prop.key}
```

#### 範例

```javascript
${prop.Example1}
```



![&#x6587;&#x5B57;&#x5340;&#x584A;&#x5167;&#x5BB9;&#xFF1A;${prop.Example1}](../../.gitbook/assets/yin-ru-can-shu.png)

#### function用法

```javascript
${
function(){
let text = prop.Example1;
text += '1';
return text;
}()
}
```

![function&#x7528;&#x6CD5;&#x9810;&#x89BD;](../../.gitbook/assets/function-fan-li.png)



### API 資料源設定

可跟著資料源數據變更自動來做調整

{% page-ref page="api-liao-yuan-ding/" %}



### 範例說明

以股票來呈現

{% page-ref page="li-ming.md" %}

