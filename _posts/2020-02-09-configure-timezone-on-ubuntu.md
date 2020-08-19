---
title: Configure timezone on Ubuntu
layout: post  #文章的版型
category: Ubuntu  #文章的資料夾
tagline: Hello world  #文章的標語
author: Sam
tags: #文章的tag
  - Ubuntu
published: true #是否發佈
---

1. 檢查現時設定

timedatectl

2. 找尋時區代碼

timedatectl list-timezones |grep Hong_Kong

3. 設定時區

sudo timedatectl set-timezone Asia/Hong_Kong

4. 檢查設定

timedatectl