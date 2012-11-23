智慧社区API
## 用户
* [用户登录](/jinwanlin/wisdom-api/blob/master/phone/users/login.md)
* [更新用户信息](/jinwanlin/wisdom-api/blob/master/phone/users/update.md "用于修改用户所在社区") 
* [用户详细](/jinwanlin/wisdom-api/blob/master/phone/users/show.md)

## 新闻
* [新闻列表](/jinwanlin/wisdom-api/blob/master/phone/news/index.md)
* [新闻详细](/jinwanlin/wisdom-api/blob/master/phone/news/show.md)

## 社区
* [社区列表](/jinwanlin/wisdom-api/blob/master/phone/communities/index.md)
* [社区详细](/jinwanlin/wisdom-api/blob/master/phone/communities/show.md)
* [社区相册列表](/jinwanlin/wisdom-api/blob/master/phone/notes/photos.md)
* [社区微博列表](/jinwanlin/wisdom-api/blob/master/phone/notes/index.md)
* [发微博](/jinwanlin/wisdom-api/blob/master/phone/notes/create.md)

## 政务
* [政策法规列表](/jinwanlin/wisdom-api/blob/master/phone/repositories/index.md)

## 便民
  该应用手机端嵌入网页, 平台提供URL, 无数据接口
* [便民](http://61.128.122.51/hotline.mobile)
* [周边](http://61.128.122.51/merchants.mobile)
* [家政](http://61.128.122.51/houses.mobile)
* [二手](http://61.128.122.51/seconds.mobile)

## 医疗
* [健康知识库列表](/jinwanlin/wisdom-api/blob/master/phone/repositories/index.md)
* [健康知识库详细](/jinwanlin/wisdom-api/blob/master/phone/repositories/show.md)
* [医院列表](/jinwanlin/wisdom-api/blob/master/phone/hospitals/index.md)
* [医院详细](/jinwanlin/wisdom-api/blob/master/phone/hospitals/show.md)
* [社区卫生站列表](/jinwanlin/wisdom-api/blob/master/phone/community_health_stations/index.md)
* [社区卫生长详细](/jinwanlin/wisdom-api/blob/master/phone/community_health_stations/show.md)
* [专家列表](/jinwanlin/wisdom-api/blob/master/phone/doctors/index.md)
* [专家详细](/jinwanlin/wisdom-api/blob/master/phone/doctors/show.md)

## 美食
* [美食家列表](/jinwanlin/wisdom-api/blob/master/phone/authors/index.md)
* [美食文章列表](/jinwanlin/wisdom-api/blob/master/phone/articles/index.md)
* [美食文章详细](/jinwanlin/wisdom-api/blob/master/phone/articles/show.md)

## 优惠
* [优惠信息列表](/jinwanlin/wisdom-api/blob/master/phone/coupons/index.md)
* [优惠详细信息](/jinwanlin/wisdom-api/blob/master/phone/coupons/show.md)

## 租房
* [(求/出)租房屋信息列表](/jinwanlin/wisdom-api/blob/master/phone/rents/index.md)
* [(求/出)租房屋信息详细](/jinwanlin/wisdom-api/blob/master/phone/rents/show.md)
* [发表(求/出)租房信息](/jinwanlin/wisdom-api/blob/master/phone/rents/create.md)

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



