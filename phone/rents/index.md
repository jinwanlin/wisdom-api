### rents
<pre>
条件查询租房信息列表
</pre>

* URL
<pre>
<a href="http://61.128.122.51/rents.json" target="_blank">http://61.128.122.51/rents.json</a>
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
[可选] rent_type : 出租/求租
[可选] page=1 默认第1页  
[可选] per_page=50 默认每页50条
</pre>

* 返回结果
```json
{ "list" : [ { "area" : 82,
        "build_time" : "2011",
        "community_id" : 1,
        "contact" : "13709960066",
        "contact_people" : "韩先生",
        "cover" : "http://61.128.122.51/system/attachments/sources/000/000/282/medium/wKhzR1BRrh-2sO27AABf7vA1SQY714_600-0_6-0.jpg?1353053380",
        "created_at" : "2012-11-16 16:09:42",
        "decoration" : "简单装修",
        "desc" : "租房 就如同自己的家。",
        "fitment" : "床   热水器   电视   暖气  ",
        "floor" : "第3层/总6层",
        "id" : 8,
        "images" : [ { "url" : "http://61.128.122.51/system/attachments/sources/000/000/282/large/wKhzR1BRrh-2sO27AABf7vA1SQY714_600-0_6-0.jpg?1353053380",
              "url_thumb" : "http://61.128.122.51/system/attachments/sources/000/000/282/thumb/wKhzR1BRrh-2sO27AABf7vA1SQY714_600-0_6-0.jpg?1353053380"
            },
            { "url" : "http://61.128.122.51/system/attachments/sources/000/000/283/large/wKhxwVBRrjTAsfHIAABghkOE2Oc090_600-0_6-0.jpg?1353053381",
              "url_thumb" : "http://61.128.122.51/system/attachments/sources/000/000/283/thumb/wKhxwVBRrjTAsfHIAABghkOE2Oc090_600-0_6-0.jpg?1353053381"
            },
            { "url" : "http://61.128.122.51/system/attachments/sources/000/000/284/large/wKhzRlClqjiDCtVVAAA08cUVr6U958_600-0_6-0.jpg?1353053381",
              "url_thumb" : "http://61.128.122.51/system/attachments/sources/000/000/284/thumb/wKhzRlClqjiDCtVVAAA08cUVr6U958_600-0_6-0.jpg?1353053381"
            }
          ],
        "live_time" : "随时",
        "live_type" : "合租",
        "location" : "水利大厦",
        "near" : "小区 右旁有家满福 超市 ,左旁是 新市 政府,前面有大型 公园 ",
        "orientation" : "南北",
        "people_type" : "个人",
        "price" : 700,
        "rent_type" : "出租",
        "shape" : "2室2厅1卫",
        "show_time" : "随时",
        "title" : "整体出租有意者随时看房",
        "traffic" : "要求单身女性爱干净，不吵闹",
        "updated_at" : "2012-11-16 16:09:42"
      },
      { "area" : 100,
        "build_time" : "2011",
        "community_id" : 1,
        "contact" : "13709960099",
        "contact_people" : "赵女士",
        "cover" : "http://61.128.122.51/system/attachments/sources/000/000/280/medium/wKhzRlClqjPeOldCAABVtq6r0Hg997_600-0_6-0.jpg?1353053026",
        "created_at" : "2012-11-16 16:03:47",
        "decoration" : "中等装修",
        "desc" : "要求单身女性爱干净，不吵闹",
        "fitment" : "冰箱   床   热水器   电视   暖气   宽带 ",
        "floor" : "第6层/总6层",
        "id" : 7,
        "images" : [ { "url" : "http://61.128.122.51/system/attachments/sources/000/000/280/large/wKhzRlClqjPeOldCAABVtq6r0Hg997_600-0_6-0.jpg?1353053026",
              "url_thumb" : "http://61.128.122.51/system/attachments/sources/000/000/280/thumb/wKhzRlClqjPeOldCAABVtq6r0Hg997_600-0_6-0.jpg?1353053026"
            },
            { "url" : "http://61.128.122.51/system/attachments/sources/000/000/281/large/wKhzRlCXn6arTeiVAAB8kV-DcoA525_600-0_6-0.jpg?1353053026",
              "url_thumb" : "http://61.128.122.51/system/attachments/sources/000/000/281/thumb/wKhzRlCXn6arTeiVAAB8kV-DcoA525_600-0_6-0.jpg?1353053026"
            }
          ],
        "live_time" : "随时",
        "live_type" : "合租",
        "location" : "水利大厦",
        "near" : "小区 右旁有家满福 超市 ,左旁是 新市 政府,前面有大型 公园 ",
        "orientation" : "南北",
        "people_type" : "个人",
        "price" : 350,
        "rent_type" : "出租",
        "shape" : " 3室2厅1卫",
        "show_time" : "随时",
        "title" : "交通西路天山医院旁单卧出租",
        "traffic" : "要求单身女性爱干净，不吵闹",
        "updated_at" : "2012-11-16 16:03:47"
      },
      { "area" : 100,
        "build_time" : "2011",
        "community_id" : 1,
        "contact" : "13709960099",
        "contact_people" : "赵女士",
        "cover" : "http://61.128.122.51/system/attachments/sources/000/000/278/medium/wKhzR1ClqjSDyTDeAAC4sCFz2V8767_600-0_6-0.jpg?1353052951",
        "created_at" : "2012-11-16 16:02:31",
        "decoration" : "精装",
        "desc" : "小区 右旁有家满福 超市 ,左旁是 新市 政府,前面有大型 公园 ,有1路,9路,4路,28路通过, 交通便利",
        "fitment" : "床   家具   煤气   暖气   宽带   电视   洗衣机   热水器  ",
        "floor" : "第5层/总6层",
        "id" : 6,
        "images" : [ { "url" : "http://61.128.122.51/system/attachments/sources/000/000/278/large/wKhzR1ClqjSDyTDeAAC4sCFz2V8767_600-0_6-0.jpg?1353052951",
              "url_thumb" : "http://61.128.122.51/system/attachments/sources/000/000/278/thumb/wKhzR1ClqjSDyTDeAAC4sCFz2V8767_600-0_6-0.jpg?1353052951"
            },
            { "url" : "http://61.128.122.51/system/attachments/sources/000/000/279/large/wKhzRlClqjiDCtVVAAA08cUVr6U958_600-0_6-0.jpg?1353052951",
              "url_thumb" : "http://61.128.122.51/system/attachments/sources/000/000/279/thumb/wKhzRlClqjiDCtVVAAA08cUVr6U958_600-0_6-0.jpg?1353052951"
            }
          ],
        "live_time" : "随时",
        "live_type" : "整租",
        "location" : "水利大厦",
        "near" : "小区 右旁有家满福 超市 ,左旁是 新市 政府,前面有大型 公园 ",
        "orientation" : "南北",
        "people_type" : "个人",
        "price" : 1000,
        "rent_type" : "出租",
        "shape" : "3室2厅1卫",
        "show_time" : "随时",
        "title" : "拎包可入住,日照非常好。",
        "traffic" : ",有1路,9路,4路,28路通过, 交通便利",
        "updated_at" : "2012-11-16 16:02:31"
      },
      { "area" : 33,
        "build_time" : "2010",
        "community_id" : 1,
        "contact" : "13119963028",
        "contact_people" : "刘女士",
        "cover" : "http://61.128.122.51/system/attachments/sources/000/000/274/medium/n_23234618944272.jpg?1353052601",
        "created_at" : "2012-11-16 15:56:43",
        "decoration" : "豪华装修",
        "desc" : "本房位于市中心的人民东路华誉商务大厦对面，交通方便；新装修,家俱厨卫全新,采光好,房屋干净整洁，租住一年者可优惠15000元,租期最少半年以上，非诚勿扰！本人另外在铁门关路（二七三医院下面）南陶对面龙祥五队三楼三室二厅单卧出租，450元/月，只限上正常班女性。",
        "fitment" : "床 / 热水器 / 电视 / 宽带 / 衣柜 / 桌子 / 电梯 / 门禁",
        "floor" : "12",
        "id" : 5,
        "images" : [ { "url" : "http://61.128.122.51/system/attachments/sources/000/000/274/large/n_23234618944272.jpg?1353052601",
              "url_thumb" : "http://61.128.122.51/system/attachments/sources/000/000/274/thumb/n_23234618944272.jpg?1353052601"
            },
            { "url" : "http://61.128.122.51/system/attachments/sources/000/000/275/large/n_23234622146322.jpg?1353052601",
              "url_thumb" : "http://61.128.122.51/system/attachments/sources/000/000/275/thumb/n_23234622146322.jpg?1353052601"
            },
            { "url" : "http://61.128.122.51/system/attachments/sources/000/000/276/large/n_23234623150093.jpg?1353052602",
              "url_thumb" : "http://61.128.122.51/system/attachments/sources/000/000/276/thumb/n_23234623150093.jpg?1353052602"
            },
            { "url" : "http://61.128.122.51/system/attachments/sources/000/000/277/large/n_23234625736209.jpg?1353052602",
              "url_thumb" : "http://61.128.122.51/system/attachments/sources/000/000/277/thumb/n_23234625736209.jpg?1353052602"
            }
          ],
        "live_time" : "随时入住",
        "live_type" : "整租",
        "location" : "人民东路万景苑",
        "near" : "医院：巴州人民医院，巴州地质医院，库尔勒市妇幼保健院，滨河社区卫生站\r\n银行：中国工商银行百乐支行，库尔勒市商业银行，中国邮政储蓄银行人民东路支行\r\n",
        "orientation" : "朝向东西",
        "people_type" : "个人",
        "price" : 1300,
        "rent_type" : "出租",
        "shape" : "1室1卫",
        "show_time" : "随时",
        "title" : "(新房装修)人民东路万景苑单身公寓",
        "traffic" : "公交站：3路，33路，121路",
        "updated_at" : "2012-11-16 15:56:43"
      },
      { "area" : 87,
        "build_time" : "2011",
        "community_id" : 1,
        "contact" : "13709960099",
        "contact_people" : "赵女士",
        "cover" : "http://61.128.122.51/system/attachments/sources/000/000/272/medium/wKhzRlCXn6ezAUaaAABwdgCOT9A301_600-0_6-0.jpg?1353052571",
        "created_at" : "2012-11-16 15:56:11",
        "decoration" : "精装",
        "desc" : "房间干净整洁",
        "fitment" : "床   电视   暖气",
        "floor" : "第2层/总5层",
        "id" : 4,
        "images" : [ { "url" : "http://61.128.122.51/system/attachments/sources/000/000/272/large/wKhzRlCXn6ezAUaaAABwdgCOT9A301_600-0_6-0.jpg?1353052571",
              "url_thumb" : "http://61.128.122.51/system/attachments/sources/000/000/272/thumb/wKhzRlCXn6ezAUaaAABwdgCOT9A301_600-0_6-0.jpg?1353052571"
            },
            { "url" : "http://61.128.122.51/system/attachments/sources/000/000/273/large/wKhzRlCXn6ieC5zuAAB83u3tYUY986_600-0_6-0.jpg?1353052571",
              "url_thumb" : "http://61.128.122.51/system/attachments/sources/000/000/273/thumb/wKhzRlCXn6ieC5zuAAB83u3tYUY986_600-0_6-0.jpg?1353052571"
            }
          ],
        "live_time" : "随时",
        "live_type" : "整租",
        "location" : "水利大厦",
        "near" : "附近有人民公园、市中医院、可以进行晨练",
        "orientation" : "南北",
        "people_type" : "个人",
        "price" : 1000,
        "rent_type" : "出租",
        "shape" : " 2室2厅1卫",
        "show_time" : "随时",
        "title" : "水利大厦两室两厅出租",
        "traffic" : "附近交通便利，走路即可到达购物中心",
        "updated_at" : "2012-11-16 15:56:11"
      },
      { "area" : 107,
        "build_time" : "2011",
        "community_id" : 1,
        "contact" : "13579946503",
        "contact_people" : "赵女士",
        "cover" : "http://61.128.122.51/system/attachments/sources/000/000/269/medium/wKhzR1CXn6ek2AqSAABvao2vDAY542_600-0_6-0.jpg?1353052369",
        "created_at" : "2012-11-16 15:52:51",
        "decoration" : "精装",
        "desc" : "离 华山 中学走路5分钟的路程",
        "fitment" : "床 热水器 暖气",
        "floor" : "第8层总11层",
        "id" : 3,
        "images" : [ { "url" : "http://61.128.122.51/system/attachments/sources/000/000/269/large/wKhzR1CXn6ek2AqSAABvao2vDAY542_600-0_6-0.jpg?1353052369",
              "url_thumb" : "http://61.128.122.51/system/attachments/sources/000/000/269/thumb/wKhzR1CXn6ek2AqSAABvao2vDAY542_600-0_6-0.jpg?1353052369"
            },
            { "url" : "http://61.128.122.51/system/attachments/sources/000/000/270/large/wKhzR1CXn6j88Uf0AABD9eyKuyQ526_600-0_6-0.jpg?1353052370",
              "url_thumb" : "http://61.128.122.51/system/attachments/sources/000/000/270/thumb/wKhzR1CXn6j88Uf0AABD9eyKuyQ526_600-0_6-0.jpg?1353052370"
            },
            { "url" : "http://61.128.122.51/system/attachments/sources/000/000/271/large/wKhzR1CXn6jnNLnMAABK9wZeFeg539_600-0_6-0.jpg?1353052370",
              "url_thumb" : "http://61.128.122.51/system/attachments/sources/000/000/271/thumb/wKhzR1CXn6jnNLnMAABK9wZeFeg539_600-0_6-0.jpg?1353052370"
            }
          ],
        "live_time" : "随时",
        "live_type" : "整租",
        "location" : "水利大厦",
        "near" : "附近有人民公园、市中医院、离华山中学很近",
        "orientation" : "南北",
        "people_type" : "个人",
        "price" : 1000,
        "rent_type" : "出租",
        "shape" : "3室1厅1卫",
        "show_time" : "随时",
        "title" : "一路车站终点,华山中学附近",
        "traffic" : "走路5分钟就可以到华山中学，多路公交车经过该小区",
        "updated_at" : "2012-11-16 15:52:51"
      },
      { "area" : 120,
        "build_time" : "2010年",
        "community_id" : 1,
        "contact" : "18782680361",
        "contact_people" : "张小姐",
        "cover" : "http://61.128.122.51/system/attachments/sources/000/000/263/medium/n_23166670087186.jpg?1353051948",
        "created_at" : "2012-11-16 15:45:51",
        "decoration" : "精装",
        "desc" : "此为个人发布信息，所有图片都是房主亲自拍摄，信息真实可信",
        "fitment" : "床 热水器 洗衣机 空调 冰箱 电视 宽带 沙发 衣柜 桌子 暖气 电梯 门禁",
        "floor" : "23",
        "id" : 2,
        "images" : [ { "url" : "http://61.128.122.51/system/attachments/sources/000/000/263/large/n_23166670087186.jpg?1353051948",
              "url_thumb" : "http://61.128.122.51/system/attachments/sources/000/000/263/thumb/n_23166670087186.jpg?1353051948"
            },
            { "url" : "http://61.128.122.51/system/attachments/sources/000/000/264/large/n_23166674078220.jpg?1353051948",
              "url_thumb" : "http://61.128.122.51/system/attachments/sources/000/000/264/thumb/n_23166674078220.jpg?1353051948"
            },
            { "url" : "http://61.128.122.51/system/attachments/sources/000/000/265/large/n_23166680195345.jpg?1353051949",
              "url_thumb" : "http://61.128.122.51/system/attachments/sources/000/000/265/thumb/n_23166680195345.jpg?1353051949"
            },
            { "url" : "http://61.128.122.51/system/attachments/sources/000/000/266/large/n_23166696809996.jpg?1353051949",
              "url_thumb" : "http://61.128.122.51/system/attachments/sources/000/000/266/thumb/n_23166696809996.jpg?1353051949"
            },
            { "url" : "http://61.128.122.51/system/attachments/sources/000/000/267/large/n_23166711195661.jpg?1353051950",
              "url_thumb" : "http://61.128.122.51/system/attachments/sources/000/000/267/thumb/n_23166711195661.jpg?1353051950"
            },
            { "url" : "http://61.128.122.51/system/attachments/sources/000/000/268/large/n_23166755855887.jpg?1353051950",
              "url_thumb" : "http://61.128.122.51/system/attachments/sources/000/000/268/thumb/n_23166755855887.jpg?1353051950"
            }
          ],
        "live_time" : "现在即可入住",
        "live_type" : "整租",
        "location" : "后河七星商场附近",
        "near" : "乐福、百安居、翠微百货、华联、万意、国美，麦当劳、肯德基、必胜客，影院、冰场、健身中心，银行、学校、医院、派出所，室内或夜市菜市场 等等等等，都在步行三到五分钟范围了。 ",
        "orientation" : "朝南",
        "people_type" : "个人",
        "price" : 3000,
        "rent_type" : "出租",
        "shape" : "三居",
        "show_time" : "全天",
        "title" : "林肯公寓 复式 豪华装修 全新进口家电品牌家具(个人)  ",
        "traffic" : "附近有1路， 2路， 13路公交车",
        "updated_at" : "2012-11-16 15:54:26"
      },
      { "area" : 25,
        "build_time" : "2008年",
        "community_id" : 1,
        "contact" : "18782680361",
        "contact_people" : "李先生",
        "cover" : "http://61.128.122.51/system/attachments/sources/000/000/261/medium/0ccd968cda3d4ceea8a734798cce67940001.jpg?1353051783",
        "created_at" : "2012-11-16 15:43:04",
        "decoration" : "普通装修",
        "desc" : "家具家电全齐   拎包即住  交通方便  小区房  可以停车  二十四小时保安巡逻。有绿化，",
        "fitment" : "床/桌子/衣柜/椅子",
        "floor" : "3",
        "id" : 1,
        "images" : [ { "url" : "http://61.128.122.51/system/attachments/sources/000/000/261/large/0ccd968cda3d4ceea8a734798cce67940001.jpg?1353051783",
              "url_thumb" : "http://61.128.122.51/system/attachments/sources/000/000/261/thumb/0ccd968cda3d4ceea8a734798cce67940001.jpg?1353051783"
            },
            { "url" : "http://61.128.122.51/system/attachments/sources/000/000/262/large/n_22839197739026.jpg?1353051783",
              "url_thumb" : "http://61.128.122.51/system/attachments/sources/000/000/262/thumb/n_22839197739026.jpg?1353051783"
            }
          ],
        "live_time" : "现在即可入住",
        "live_type" : "整租",
        "location" : "后河七星商场附近",
        "near" : "乐福、百安居、翠微百货、华联、万意、国美，麦当劳、肯德基、必胜客，影院、冰场、健身中心，银行、学校、医院、派出所，室内或夜市菜市场，还有几十条线路的公交车站，等等等等，都在步行三到五分钟范围了。 ",
        "orientation" : "朝南",
        "people_type" : "个人",
        "price" : 200,
        "rent_type" : "出租",
        "shape" : "独立单间",
        "show_time" : "全天",
        "title" : "阳光公寓超低出租",
        "traffic" : " 附近有1路， 2路， 13路公交车",
        "updated_at" : "2012-11-16 15:54:10"
      }
    ],
  "page" : 1,
  "per_page" : 30,
  "total" : 8
}
```

* 返回结果字段说明
<pre>
略
</pre>



