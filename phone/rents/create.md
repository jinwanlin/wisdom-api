### rents/{id}
<pre>
发表租房信息
</pre>

* URL
<pre>
<a href="http://61.128.122.51/rents.json" target="_blank">http://61.128.122.51/rents.json</a>
</pre>

* HTTP请求方式：
<pre>
POST
</pre>

* 是否需要登录
<pre>
是
</pre>

* 注意事项
<pre>
无
</pre>

* 请求参数
<pre>
[必须] authenticity_token: 用户唯一标识
[必须] rent[title]: 标题
[必须] rent[people_type]: 发布者类型(个人/中介)
[必须] rent[rent_type]: 类型(求租/出租)
[必须] rent[price]: 租金
[可选] rent[live_type]: 居住方式(整租/合租)
[必须] rent[community_id]: 所属社区
[可选] rent[area]: 面积
[可选] rent[shape]: 户型
[可选] rent[floor]: 楼层
[可选] rent[decoration]: 装修程度
[可选] rent[fitment]: 配套设施
[可选] rent[orientation]: 朝向
[可选] rent[show_time]: 看房时间
[可选] rent[live_time]: 入住时间
[可选] rent[build_time]: 房屋年代
[可选] rent[location]: 地址
[必须] rent[contact_people]: 联系人
[可选] rent[contact]: 联系电话
[可选] rent[near]: 附近设施
[可选] rent[traffic]: 交通配套
[可选] attachments[]: 附件图片1
[可选] attachments[]: 附件图片2
</pre>

* 返回结果
```json
{ "area" : 0,
  "build_time" : "房屋年代",
  "community_id" : 1,
  "contact" : "联系电话",
  "contact_people" : "联系人",
  "cover" : "http://61.128.122.51/system/attachments/sources/000/000/292/medium/n_23166670087186.jpg?1353642856",
  "created_at" : "2012-11-23 11:54:17",
  "decoration" : "装修程度",
  "desc" : "房屋介绍\r\n",
  "fitment" : "配套设施",
  "floor" : "楼层",
  "id" : 11,
  "images" : [ { "url" : "http://61.128.122.51/system/attachments/sources/000/000/292/large/n_23166670087186.jpg?1353642856",
        "url_thumb" : "http://61.128.122.51/system/attachments/sources/000/000/292/thumb/n_23166670087186.jpg?1353642856"
      } ],
  "live_time" : "入住时间",
  "live_type" : "整租",
  "location" : "地址",
  "near" : "附近设施",
  "orientation" : "朝向",
  "people_type" : "个人",
  "price" : 0,
  "rent_type" : "出租",
  "shape" : "户型",
  "show_time" : "看房时间",
  "title" : "标题",
  "traffic" : "交通配套",
  "updated_at" : "2012-11-23 11:54:17"
}
```

* 返回结果字段说明
<pre>
略
</pre>

