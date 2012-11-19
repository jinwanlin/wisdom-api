* [news](#news) 列表
* [news/{id}](#news/{id}) 详细

---------------------------------------

<a name="news"></a>
# news
<pre>
条件查询新闻列表
</pre>

* URL
<pre>
<a href="http://61.128.122.51/news.json" target="_blank">http://61.128.122.51/news.json</a>
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
```json
page=1 第几页  
per_page=50 每页数量
```

* 返回结果
```json
{
    "list": [{
        "content": "\u842168\u9762\u5efa\u6210\u5c0f\u5eb7\u793e\u4f1a\u52aa\u529b\u594b\u6597\u3002",
        "created_at": "2012-11-13 12:13:13",
        "id": 37,
        "title": "\u68a8\u57ce\u5404\u754c\u6536\u542c\u6536\u770b\u5341\u516b\u5927\u5f00\u5e55\u76db\u51b5",
        "image": "http://61.128.122.51/system/attachments/sources/000/000/076/large/4437e6145c661207119209.jpg?1352779993"
    },
    {
        "content": "\u6628\u,\u786e\u4fdd\u65c5\u5ba2\u5b89\u5168\u987a\u5229\u8fd4\u4e61\u3002",
        "created_at": "2012-11-13 12:11:24",
        "id": 36,
        "title": "3500\u540d\u62fe\u82b1\u5de5\u6628\u4e58\u9996\u8d9f\u4e34\u5ba2",
        "image": "http://61.128.122.51/system/attachments/sources/000/000/074/large/4437e6145c661202c6e33b.jpg?1352779884"
    },
    {
        "content": "11\u67088\u65e5\\u96ea\u5e94\u6025\u65b9\u6848\u3002\u201d\r\n",
        "created_at": "2012-11-13 12:07:24",
        "id": 35,
        "title": "\u96ea\u5929\u8f66\u96be\u7b49 \u4e4c\u9c81\u6728\u9f50\u5e02\u6c11\u5fae\u535a\u5410\u69fd\u201c\u4f24\u4e0d\u8d77\u201d",
        "image": "http://61.128.122.51/system/attachments/sources/000/000/073/large/113647798_21n.jpg?1352779644"
    },
    {
        "content": "\u65b0\u7586\u90fd\u5e3b\u7ad9\u7533\u8bf7\u89e3\u6790\u3002",
        "created_at": "2012-11-13 11:57:05",
        "id": 33,
        "title": "\u65b0\u7586\u5c06\u5efa\u7acb\u5168\u7586\u4e2d\u5c0f\u5b66\u7f51\u7edc\u5e73\u53f0",
        "image": null
    },
    {
        "content": "2010\u5e745\u67c55\u6ce8\u5165\u4e86\u52aa\u529b\u3001\u5f00\u653e\u3001\u8fdb\u53d6\u7684\u884c\u52a8\u51c6\u5219\u3002",
        "created_at": "2012-11-13 11:56:05",
        "id": 32,
        "title": "\u65b0\u7586\u7cbe\u795e\uff1a\u5f15\u9886\u5168\u7586\u5927\u8de8\u8d8a",
        "image": "http://61.128.122.51/system/attachments/sources/000/000/061/large/bcaec5ad228f120b4b4750.jpg?1352778964"
    },
    {
        "content": "\u7ee7\u8fde\u7eed3\uf0c\u540c\u6bd4\u589e\u957f9.7%\u3002",
        "created_at": "2012-11-13 11:53:16",
        "id": 31,
        "title": "\u56fd\u5bb6\u518d\u629514\u4ebf\u5efa\u65b0\u7586\u4f18\u8d28\u68c9\u57fa\u5730",
        "image": "http://61.128.122.51/system/attachments/sources/000/000/053/large/0016eca451e8120c082801.jpg?1352778796"
    }],
    "page": 1,
    "per_page": 6,
    "total": 36
}
```

* 返回结果字段说明
<pre>
略
</pre>

---------------------------------------



<a name="news/{id}"></a>
# news/{id}
<pre>
查看新闻详细信息
</pre>

* URL
<pre>
<a href="http://61.128.122.51/news/1.json" target="_blank">http://61.128.122.51/news/1.json</a>
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
无
</pre>

* 返回结果
```json
{
    "content": "11\u67085\u65e5\u4e0a\u5348\ufu4eec\u62b5\u8fbe\u9996\u90fd\u673a\u573a\u8d70\u4e0b\u98de\u673a\u3002",
    "created_at": "2012-11-13 07:46:38",
    "id": 1,
    "title": "\u65b0\u7586\u51fa\u5e2d\u515a\u7684\u5341\u516b\u5927\u4ee3\u8868\u62b5\u8fbe\u5317\u4eac",
    "image": "http://61.128.122.51/system/attachments/sources/000/000/001/large/d4bed9e6027f1201dcff24.JPG?1352763997"
}
```

* 返回结果字段说明
<pre>
略
</pre>

