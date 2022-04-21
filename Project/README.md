# 廖洧杰老師課堂筆記_Hexschool

### VS code 小撇步
* 內建Emmet套件
* 輸入 ! (enter or tab) 自動產出架構
```html
  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```
* 輸入 p * 2 (tab) 直接產出兩個段落
```html
<p></p>
<p></p>
```
  
### HTML

* img 標籤 (source 圖片來源，可以是本地或者是網上)
```html
<img src="doggie.png" alt="dog">
```
```html
<img src="img/doggie.png" alt="dog">
```
```html
<img src="https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/dog-puppy-on-garden-royalty-free-image-1586966191.jpg?crop=1.00xw:0.669xh;0,0.190xh&resize=1200:*" alt="dog">
```

* a 標籤
```html
<a target="_blank" href="https://google.com" title="連到Google">連到Google</a>
```

* ul ol li 標籤 (List)
```html
<ul>
    <li>項目一</li>
    <li>項目二</li>
    <li>項目三</li>
</ul>       
```
```html
<ol>
    <li>項目一</li>
    <li>項目二</li>
    <li>項目三</li>
</ol>
```
## CSS (需在head標籤連結CSS以套用樣式)
```html
<head>
    <link rel="stylesheet" href="style.css">
</head>
```

選擇器{<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
    屬性: 設定值;   
}


* list-style-type
* line-height
