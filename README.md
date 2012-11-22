智慧社区API
## 用户
* [用户登录](/jinwanlin/wisdom-api/blob/master/users/login.md)
* [更新用户信息](/jinwanlin/wisdom-api/blob/master/users/update.md "用于修改用户所在社区") 
* [用户详细](/jinwanlin/wisdom-api/blob/master/users/show.md)

## 新闻
* [新闻列表](/jinwanlin/wisdom-api/blob/master/news/index.md)
* [新闻详细](/jinwanlin/wisdom-api/blob/master/news/show.md)

## 社区
* [社区列表](/jinwanlin/wisdom-api/blob/master/communities/index.md)
* [社区详细](/jinwanlin/wisdom-api/blob/master/communities/show.md)
* [社区相册列表](/jinwanlin/wisdom-api/blob/master/notes/photos.md)
* [社区微博列表](/jinwanlin/wisdom-api/blob/master/notes/index.md)
* [发微博](/jinwanlin/wisdom-api/blob/master/notes/create.md)

## 政务
* [政策法规列表](/jinwanlin/wisdom-api/blob/master/knowledges/index.md)

## 便民
  该应用手机端嵌入网页, 平台提供URL, 无数据接口
* [便民](http://61.128.122.51/hotline.mobile)
* [周边](http://61.128.122.51/merchants.mobile)
* [家政](http://61.128.122.51/houses.mobile)
* [二手](http://61.128.122.51/seconds.mobile)

## 医疗
* [健康知识库列表](/jinwanlin/wisdom-api/blob/master/repositories/index.md)
* [健康知识库详细](/jinwanlin/wisdom-api/blob/master/repositories/show.md)
* [医院列表](/jinwanlin/wisdom-api/blob/master/hospitals/index.md)
* [医院详细](/jinwanlin/wisdom-api/blob/master/hospitals/show.md)
* [社区卫生站列表](/jinwanlin/wisdom-api/blob/master/community_health_stations/index.md)
* [社区卫生长详细](/jinwanlin/wisdom-api/blob/master/community_health_stations/show.md)
* [专家列表](/jinwanlin/wisdom-api/blob/master/doctors/index.md)
* [专家详细](/jinwanlin/wisdom-api/blob/master/doctors/show.md)

## 美食
* [美食家列表](/jinwanlin/wisdom-api/blob/master/authors/index.md)
* [美食文章列表](/jinwanlin/wisdom-api/blob/master/articles/index.md)
* [美食文章详细](/jinwanlin/wisdom-api/blob/master/articles/show.md)

## 优惠
* [优惠信息列表](/jinwanlin/wisdom-api/blob/master/coupons/index.md)
* [优惠详细信息](/jinwanlin/wisdom-api/blob/master/coupons/show.md)

## 租房
* [(求/出)租房屋信息列表](/jinwanlin/wisdom-api/blob/master/rents/index.md)
* [(求/出)租房屋信息详细](/jinwanlin/wisdom-api/blob/master/rents/show.md)
* [发表(求/出)租房信息](/jinwanlin/wisdom-api/blob/master/rents/create.md)

------------------------
## rails请求
* [GET]  	models			列表
* [GET]		models/{id} 		详细
* [POST]	models.json		添加
* [PUT]		models/{id}.json	更新
* [DELETE]	models/{id}.json	删除

-------------------------
## 分页请求参数和返回参数
* 请求参数
<pre>
page=1 默认第1页  
per_page=50 默认每页50条
</pre>


* 返回结果字段说明
<pre>
page：当前页码  
per_page:本页最多查询多少条  
total：总数
</pre>
---------------------------------------



