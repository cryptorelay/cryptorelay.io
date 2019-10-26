# Next generation crypto exchange system

## It's time to upgrade your crypto exchange now!

* **Highly scalable** architecture, Support **100k TPS** per trading pair, less than **10 ms latency**, very impressive data collected on commodity server hardware. It can save a lot of hardware costs for you.
* High throughput low latency system is key to trading bots. With this abundant TPS you have, you can expand more **quantitative trading** customers.
* Support **perpetual** future contract trading, embrace the future of crypto trading.
* **High availability**. With the advanced architecture we engineered, we can provide high availability guarantees, it means no more service disruption and greater user experience.

## Features

| 币币内存撮合集群                   | 币币数据库清算系统       | 永续合约处理集群                                     |
| ---------------------------------- | ------------------------ | ---------------------------------------------------- |
| c++实现内存撮合，单币对10w TPS     | 与撮合引擎协议对接       | rust实现全内存高性能计算 5w TPS                      |
| 分布式架构，币对横向扩展           | 全内存实时行情计算和推送 | 撮合清算爆仓统一处理，优先处理爆仓单，最小化系统风险 |
| 数据持久化和主从复制               | 自动分表，资产对账       | 数据持久化和主从复制                                 |
| 成交回报由下游pull，确保数据不丢失 | 管理后台                 | 成交回报由下游pull，确保数据不丢失                   |
| 支持限价/市价/止盈止损             | restful/websocket API    | 支持限价/市价                                        |
| redis协议的API，接入简单           | 容器化编排部署，自动扩容 |                                                      |

## Why It's performance is so great

* We develop the core part of system with highly optimized c++/rust code.
* We exploited top-notch open source solutions.
  * By customising redis internals, we made it a secret weapon for crypto exchange system, and a very core part of our architecture.
* With the deep understanding of trading logic underlies exchange, we designed a highly scalable, at the same time highly available architecture.

## Read more:

* [Technical Architecture](architecture.md)
* [Restful API Docs](rest-api.html)
* [WebSockets API Docs](ws.md)
* [GraphQL API Docs](graphql.md)
* [Benchmarks](benchmarks.md)

## Contact

<form action="https://formspree.io/yi.codeplayer@gmail.com" method="POST">
    <input type="text" name="name" placeholder="Your Message">
    <input type="email" name="_replyto" placeholder="Your Email">
    <input type="submit" value="Send">
</form>

