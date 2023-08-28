---
title: 关于httpClient的httpGet和HttpPost
tags: test测试
abbrlink: 32947
date: 2023-07-28 11:11:00
---

无论是使用HttpGet，还是使用HttpPost，都必须通过如下3步来访问HTTP资源。

1.创建HttpGet或HttpPost对象，将要请求的URL通过构造方法传入HttpGet或HttpPost对象。

2.使用DefaultHttpClient类的execute方法发送HTTP GET或HTTP POST请求，并返回HttpResponse对象。

3.通过HttpResponse接口的getEntity方法返回响应信息，并进行相应的处理