---
title: Hexo 主題
date: 2023-05-09 23:17:28
tags: #Hexo #Next
---

# 前言
目前還在測試摸索階段，陸續記錄學習的過程。

## 選擇語言、時區

### 語言
在根目錄下的 _config.tml --> language 設置語言，預設是 **en**，台灣是 **zh-tw**。

### 時區
在根目錄下的 _config.tml --> timezone 設置時區，預設是自己電腦時間，可參考 [**時區列表**](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones) 選擇自己所在的時區，台灣是 **Asia/Taipei**。


## 更換 Hexo 主題
可以到 Hexo 官網提供的 [**themes**](https://hexo.io/themes/)，選擇感興趣的主題。
將主題下載下來後，放置在 themes 資料夾，到根目錄下的 _config.yml 更換要用的主題 

```
theme: <主題資料夾名稱>
```


## 更換 code 顯示方式

在 ``` 後面加上要寫哪種語言，code會自動顯示對應語法的顏色
``` JavaScript
// ```JavaScript
function () {
  return "Hello Hexo"
}
```

``` CSS
/* CSS */
h1 {
  margin: 10px;
  padding: 0;
}
```

## 新增影片
{% youtube 5qSswXCzW44 %}
