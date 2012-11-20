智慧社区API  

[新闻列表](/jinwanlin/wisdom-api/blob/master/news/list.md)  
[新闻详细](jinwanlin/wisdom-api/blob/master/news/show.md)  
------------------------
## rails请求
* [GET]		models			列表
* [GET]		models/{id} 		详细
* [POST]	models.json		添加
* [PUT]		models/{id}.json	更新
* [DELETE]	models/{id}.json	删除

-------------------------
## 分页请求参数和返回参数
* 请求参数
<pre>
page=1 第几页  
per_page=50 每页数量
</pre>


* 返回结果字段说明
<pre>
page：当前页码  
per_page:本页最多查询多少条  
total：总数
</pre>
---------------------------------------



