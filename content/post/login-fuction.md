+++
author = "Duofilm"
title = "Rails Login Fuction Implement"
description = "Rails login function Implement"
date = 2020-05-14T11:55:52+08:00
draft = false
tags = ["login","Rails",""]
categories = ["Rails",]
+++
### 前言
controller跟view跟model要分開建立反而會節省時間。
### 1. make user model
create user model with `name` and `email`
```js
rails g model User name email
rails db:migrate
```
