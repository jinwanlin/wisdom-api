### community_health_stations
<pre>
条件查询社区卫生服务站列表
</pre>

* URL
<pre>
<a href="http://61.128.122.51/community_health_stations.json" target="_blank">http://61.128.122.51/community_health_stations.json</a>
</pre>

* HTTP请求方式：
<pre>
GET
</pre>

* 是否需要登录
<pre>
否
</pre>

* 注意事项
<pre>
无
</pre>

* 请求参数
<pre>
[可选] page=1 默认第1页  
[可选] per_page=50 默认每页50条
</pre>

* 返回结果
```json
{ "list" : [ { "community_name" : "滨河社区",
        "contact" : "0996-2619993 ",
        "cover" : "http://61.128.122.51/system/attachments/sources/000/000/083/thumb/%E7%A4%BE%E5%8C%BA%E5%8D%AB%E7%94%9F%E6%9C%8D%E5%8A%A1%E7%AB%99Logo.jpg?1352780900",
        "created_at" : "2012-11-13 12:28:21",
        "desc" : "滨河社区所属卫生服务站",
        "essence" : "卫生服务站",
        "id" : 1,
        "images" : [ { "url" : "http://61.128.122.51/system/attachments/sources/000/000/083/large/%E7%A4%BE%E5%8C%BA%E5%8D%AB%E7%94%9F%E6%9C%8D%E5%8A%A1%E7%AB%99Logo.jpg?1352780900",
              "url_thumb" : "http://61.128.122.51/system/attachments/sources/000/000/083/thumb/%E7%A4%BE%E5%8C%BA%E5%8D%AB%E7%94%9F%E6%9C%8D%E5%8A%A1%E7%AB%99Logo.jpg?1352780900"
            } ],
        "location" : "库尔勒市人民东路州建筑公司2号楼1单元102",
        "name" : "滨河社区卫生服务站",
        "openoffice" : "全科",
        "updated_at" : "2012-11-13 12:28:21",
        "workingtime" : "10:00-21:30"
      } ],
  "page" : 1,
  "per_page" : 30,
  "total" : 1
}
```

* 返回结果字段说明
<pre>
略
</pre>



