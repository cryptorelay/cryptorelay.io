## WebSockets API Docs

### WebSockets流订阅接口

`/stream?name=stream1&name=stream2`

通过stream，可以订阅一个或多个流，流以名称标识，命名规则如下（`$symbol`替换成币对标示）：

* 深度变化： `depth@$symbol`
* 最新成交：`trade@$symbol`
* K线变化：`kline_1m@$symbol`，其中`1m`可以替换成：`3m`,`5m`,`15m`,`30m`,`1h`,`2h`,`4h`,`6h`,`12h`,`1d`,`1w`,`1mo`
* 个人信息变化：`$token`，包括下单撤单和订单更新，以及资产余额变化。登陆用户先通过Restful接口``/user_stream``获取自己的流Token。

Demo测试地址： ws://demoexchange.cryptorelay.io/stream
