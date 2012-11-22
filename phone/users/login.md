### users/login
<pre>
用户登录
</pre>

* URL
<pre>
<a href="http://61.128.122.51/login.json" target="_blank">http://61.128.122.51/login.json</a>
</pre>

* HTTP请求方式：
<pre>
POST
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
[可选] account_type: sina or qq  
[必须] account_id: 帐号  
[可选] avatar: 头像地址  
[可选] name: 昵称  
</pre>

* 返回结果
```json
{ "account_id" : 1,
  "account_type" : "sina",
  "auth_token" : "6a98c9618b221b9834f1964c0bd83716",
  "community_id" : 1
}
```

* 返回结果字段说明
<pre>
auth_token: 用户唯一标识, 登录后存本地, 当调用需要登录的接口时, 请携带此参数.
</pre>

