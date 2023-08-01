---
title: Live2D 建置
abbrlink: 1306
tags:
---

## 前因
想要擁有一個在 Blog 的搖頭晃腦的小寵物，摸索建置方式。

## 步驟
1. 終端機上輸入
```
npm install --save hexo-helper-live2d
```

2. 安裝自己要的模板，例如我要的是貓咪模組，在終端機上輸入
```
npm install live2d-widget-model-hijiki
```

3. 在根目錄的 _config.yml 添加配置
```
live2d:
  enable: true
  scriptFrom: local
  pluginRootPath: live2dw/
  pluginJsPath: lib/
  pluginModelPath: assets/
  tagMode: false
  debug: false
  model:
    use: live2d-widget-model-hijiki  # 這串寫入要使用的live2D模組
  display:
    #  設置模組的位置
    position: right
    width: 150
    height: 300
  mobile:
    show: true
  react:
    opacity: 0.7
```

4. 重啟 Hexo 伺服器，畫面出現剛安裝的模組代表設置成功。

## 資料來源
[hexo-helper-live2d](https://github.com/EYHN/hexo-helper-live2d)
