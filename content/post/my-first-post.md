+++
title = "我的第一篇文章"
description = "A brief description of Hugo Shortcodes"
date = 2020-05-14T07:40:47+08:00
draft = false
tags = ["爽",]
categories = ["爽",]
+++
我的第一篇文章
```ruby
	<%=@user.name%>
```
#### bash
```Bash
echo "hello"
```
```ruby
db/migrate/20xxxxx_create_members.rb

def create
t.string :name, unique: true,
	t.string :email, unique: true,
	t.string :password,
	+ t.string :session_token, unique: true, index: true
	t.timestamps
	end
end
```
