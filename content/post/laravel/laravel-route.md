+++
author = "Duofilm"
title = "Laravel Route"
description = "Laravel Route Basic Usage"
date = 2020-05-17T00:13:22+08:00
draft = false
tags = ["laravel","route"]
categories = ["laravel",]
+++
### 修改route
```PHP
// web.php

Route::get('/tom', function () {
    return "媽我在這裡";
});
// return plan text

Route::get('/', function () {
    return view('welcome');
});
// return view方法的welcom頁面
```
