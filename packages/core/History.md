1.1.22 / 2019-07-15
===================

  * 开放接口 `/api-v2/jwt/sso`单点登录,`/api-v2/jwt/getToken`获取`{userId:'xx', authToken: 'xx'}` 
1.1.21 / 2019-07-12
===================

  * OData接口速度优化，EXCEL接入偏慢

1.1.20 / 2019-06-17
===================

  * odata接口获取到$set, $unset 后， 将set与unset合并为一个doc ，交给driver。 合并完的doc中，unset字段部分字段值均为null
  * fix OData接口问题，EXCEL接入时，expand字段出不来

1.1.19 / 2019-06-13
===================

  * loadStandardObjects加载方式优化及加载object_webhooks.object.yml

1.1.18 / 2019-06-04
===================

  * 列表接口不返回已假删除(is_deleted:true)的数据

1.1.17 / 2019-06-04
===================

  * meteormongodriver中update 的data参数格式不要带$set 与mongodriver保持一致 #82