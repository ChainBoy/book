
# 目录

<br\>
## 第一部分 入门指南


## 第1章 HTTP概述
* ### 1.1 理解 HTTP
    * #### 1.1.1 HTTP 是什么
    * #### 1.1.2 HTTP 结构
    
* ### 1.2 HTTP请求
    
    * #### 1.2.1 Web 客户端
    * #### 1.2.2 请求地址: 域名/IP/端口
    * #### 1.2.3 请求类型: GET/POST/...
    * #### 1.2.4 客户端器发送了什么
    * #### 1.2.5 客户端器接收了什么
    * #### 1.2.5 我们看到了什么
    
* ### 1.3 HTTP响应
    
    * #### 1.3.1 Web 服务端
    * #### 1.3.2 解析HTTP请求
    * #### 1.3.3 构建响应报文
    * #### 1.3.4 发送响应至客户端
    * #### 1.3.5 响应正文类型
    * #### 1.3.6 响应状态

* ### 1.4 小结
    * #### 1.4.1 小结
    * #### 1.4.2 参考
    
---

## 第2章 网络爬虫概述
* ### 2.1 理解爬虫
    
    * #### 2.1.1 网络爬虫究竟是什么
    * #### 2.1.2 如何更好的理解爬虫
    * #### 2.1.3 爬虫可以用来做什么

* ### 2.2 爬虫搜索策略
    
    * #### 2.2.1 深度优先搜索策略
    * #### 2.2.2 广度优先搜索策略
    * #### 2.2.3 最佳优先搜索策略
    * #### 2.2.4 对比搜索策略(查水表)
    
* ### 2.3 爬虫类型
    
    * #### 2.3.1 通用爬虫
    * #### 2.3.2 聚焦爬虫
    * #### 2.3.3 定向爬虫
    
* ### 2.4 小结
    
    * #### 2.4.1 小结-你真的需要通用爬虫吗
    * #### 2.4.2 参考
    
---

## 第3章 小试牛刀，写一个小爬虫
* ### 3.1 如何写一个爬虫
    
    * #### 3.1.1 你需要什么数据
    * #### 3.1.2 分析网站-不要相信你看到的
    * #### 3.1.3 数据抽取-如何拿到你想要的数据
    * #### 3.1.4 数据存储-选择合适的方式存储你"拿"到的数据
    

* ### 3.2 实战分析：把《花千骨》都"爬"下来
    
    * #### 3.2.1 分析搜索页面
    * #### 3.2.2 分析播放列表页
    * #### 3.2.3 分析播放页
    * #### 3.2.4 完整示例
    
* ### 3.3 小结
    
    * #### 3.3.1 数据格式 - html/json/...
    * #### 3.3.2 小结
    * #### 3.3.3 参考

<br\>

---


## 第二部分 进阶爬虫


## 第4章 调试工具
* ### 4.1 下载 抓包 调试
    
    * #### 4.1.1 Chrome/插件
    * #### 4.1.2 Python
    * #### 4.1.3 wget/curl
    * #### 4.1.4 Fiddler
    
* ### 4.2 
    
    * #### 4.2.1
    * #### 4.2.2
    * #### 4.2.3
    * #### 4.2.4
    
* ### 4.3
    
    * #### 4.3.1
    * #### 4.3.2 小结
    * #### 4.3.3 参考

---

## 第5章 Python库介绍
* ### 5.1 内置库
    
    * #### 5.1.1 下载：urllib/urllib2/httplib
    * #### 5.1.2 解析、存储：json/re/HtmlParser/lxml/pickle
    * #### 5.1.3 时间日期：time/datetime/random
    * #### 5.1.4 其他：os/sys/logging/copy/ConfigParser/xml2dict
    
* ### 5.2 第三方库
    
    * #### 5.2.1 下载：requests/(python-goose)
    * #### 5.2.2 解析、存储：simplejson
    * #### 5.2.3 解析抽取：BeautifulSoup4/bs4
    * #### 5.2.4 解析抽取：pyquery
    * #### 5.2.5 存储：MySQLdb/mysql-connector/sqlite/redis/...
    * #### 5.2.6 其他
    
* ### 5.3 小结
    
    * #### 5.3.2 小结
    * #### 5.3.3 参考

---

## 第6章 高级爬虫
* ### 6.1 模拟请求之Header处理
    
    * #### 6.1.1 User-Agent
    * #### 6.1.2 Host
    * #### 6.1.3 Referer
    * #### 6.1.4 Cookies
    
* ### 6.2 各种反爬虫策略导致403/404/...
    
    * #### 6.2.1 IP限制：代理
    * #### 6.2.2 不知道从哪多出来的参数：ajax
    * #### 6.2.3 看不到更多内容，各种权限限制：登录
    * #### 6.2.4 反人类验证码：验证码识别
    
* ### 6.3 小结
    
    * #### 6.3.2 小结
    * #### 6.3.3 参考

---

## 第7章 爬虫实战/豆瓣发帖

<br\> 
## 第三部分 打开框架的大门


## 第8章 爬虫框架 (scrapy-redis/python-rq/webscraping)

## 第9章 打造属于你自己的框架

## 第10章 多线程、多进程、分布式


<br\> 
## 第四部分 总结整理

## 第11章 大大小小的爬虫

## 第12章 环境搭建

## 附录 防坑必备