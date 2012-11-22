### users
<pre>
条件查询社区用户列表
</pre>

* URL
<pre>
<a href="http://61.128.122.51/accounts.json" target="_blank">http://61.128.122.51/accounts.json</a>
</pre>

* HTTP请求方式：
<pre>
GET
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
[必须] authenticity_token: 登录验证token
[可选] page=1 默认第1页  
[可选] per_page=50 默认每页50条  
[可选] community_id: 社区ID, 必须
[可选] timestamp: 当传入此时间, 则返回在这个时间后更新的用户列表
</pre>

* 返回结果
```json
{ "list" : [ { "avatar" : "http://tp2.sinaimg.cn/3020392461/180/0/1",
        "community_id" : 1,
        "name" : "a伊稀52088"
      },
      { "avatar" : "http://tp2.sinaimg.cn/1778510485/180/1281144592/1",
        "community_id" : 9,
        "name" : "哎哟我的兄弟也"
      },
      { "avatar" : "http://tp2.sinaimg.cn/1866213785/180/40004716623/1",
        "community_id" : 1,
        "name" : "_毛绒熊熊_"
      },
      { "avatar" : "http://tp2.sinaimg.cn/2100822957/180/0/1",
        "community_id" : 1,
        "name" : "随风_流浪的人"
      },
      { "avatar" : null,
        "community_id" : null,
        "name" : "admin"
      },
      { "avatar" : "http://tp2.sinaimg.cn/3072785841/180/0/1",
        "community_id" : 1,
        "name" : "新疆公众北京"
      },
      { "avatar" : "http://tp1.sinaimg.cn/1703066284/180/5625119501/1",
        "community_id" : null,
        "name" : "刘齐1024"
      }
    ],
  "page" : 1,
  "per_page" : 30,
  "total" : 7
}
```

* 返回结果字段说明
<pre>
略
</pre>


