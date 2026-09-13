百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
灼直伊洗袒嵌准拇啡裁卸帘傲惶肚

状态代码

成功
200 正常;请求已完成。
201 正常;紧接POST命令。
202 正常;已接受用于处理，但处理尚未完成。
203 正常;部分信息 — 返回的信息只是一部分。
204 正常;无响应 — 已接收请求，但不存在要回送的信息。
重定向
301 永久重定向 — 请求的数据具有新的位置且更改是永久的。
302 暂时重定向 — 请求的数据临时具有不同URI。
303 请参阅其它 — 可在另一URI下找到对请求的响应，且应使用 GET方法检索此响应。
304 未修改 — 未按预期修改文档。
305 使用代理 — 必须通过位置字段中提供的代理来访问请求的资源。
306 未使用 — 不再使用;保留此代码以便将来使用。
代码中的错误
400 错误请求 — 请求中有语法问题，或不能满足请求。
401 未授权 — 未授权客户机访问数据。
402 需要付款 — 表示计费系统已有效。
403 禁止— 即使有授权也不需要访问。
404 找不到—服务器找不到给予的资源;文档不存在。
406 不可接受 — 根据此请求中所发送的“接受”标题，此请求所标识的资源只能生成内容特征为“不可接受”的响应实体。
407 代理认证请求 — 客户机首先必须使用代理认证自身。
410 请求的网页不存在(永久);
415 介质类型不受支持 —服务器拒绝服务请求，因为不支持请求实体的格式。
500 内部错误 — 因为意外情况，服务器不能完成请求。
501 未执行 —服务器不支持请求的工具。
502 错误网关—服务器接收到来自上游服务器的无效响应。
503 无法获得服务 — 由于临时过载或维护，服务器无法处理请求。

问题解答

Baiduspider对一个网站服务器造成的访问压力如何？
答：Baiduspider会自动根据服务器的负载能力调节访问密度。在连续访问一段时间后，Baiduspider会暂停一会，以防止增大服务器的访问压力。所以在一般情况下，Baiduspider对您网站的服务器不会造成过大的压力。
为什么Baiduspider不停的抓取我的网站？
答：或许您的网站权重高或者对于您网站上新产生的或者持续、有规律更新的页面，Baiduspider会持续抓取。此外，您也可以检查网站访问日志中Baiduspider的访问是否正常，以防止有人恶意冒充Baiduspider来频繁抓取您的网站。 如果您发现Baiduspider非正常抓取您的网站，请反馈至，并请尽量给出Baiduspider对贵站的访问日志，以便于我们跟踪处理。
我不想我的网站被Baiduspider访问，我该怎么做？
答：Baiduspider遵守互联网robots协议。您可以利用robots.txt文件完全禁止Baiduspider访问您的网站，或者禁止Baiduspider访问您网站上的部分文件。 注意：禁止Baiduspider访问您的网站，将使您的网站上的网页，在百度搜索引擎以及所有百度提供搜索引擎服务的搜索引擎中无法被搜索到。
ps:关于robots.txt的写作方法，请参看我们的介绍：robots.txt写作方法
为什么我的网站已经加了robots.txt，还能在百度搜索出来？
答：因为搜索引擎索引数据库的更新需要时间。虽然Baiduspider已经停止访问您网站上的网页，但百度搜索引擎数据库中已经建立的网页索引信息，可能需要二至四周才会清除。 另外也请检查您的robots配置是否正确。
我希望我的网站内容被百度索引但不被保存快照，我该怎么做？
答：Baiduspider遵守互联网metarobots协议。您可以利用网页meta的设置，使百度显示只对该网页建索引，但并不在搜索结果中显示该网页的快照。
和robots的更新一样，因为搜索引擎索引数据库的更新需要时间，所以虽然您已经在网页中通过meta禁止了百度在搜索结果中显示该网页的快照，但百度搜索引擎数据库中如果已经建立了网页索引信息，可能需要二至四周才会在线上生效。
百度蜘蛛在robots.txt中的名字是什么？
答：“Baiduspider” 首字母B大写，其余为小写。
Baiduspider多长时间之后会重新抓取我的网页？
答：百度搜索引擎每周更新，网页视重要性有不同的更新率，频率在几天至一月之间，Baiduspider会重新访问和更新一个网页。
Baiduspider抓取造成的带宽堵塞？
答：Baiduspider的正常抓取并不会造成您网站的带宽堵塞，造成此现象可能是由于有人冒充baidu的spider恶意抓取。如果您发现有名为Baiduspider的agent抓取并且造成带宽堵塞，请尽快和我们联系。您可以将信息反馈至百度网页投诉中心，如果能够提供您网站该时段的访问日志将更加有利于我们的分析。

群发外链
对应名称
产品名称 对应user-agent
网页搜索 Baiduspider
无线搜索 Baiduspider
图片搜索 Baiduspider-image
视频搜索 Baiduspider-video
新闻搜索 Baiduspider-news
百度搜藏 Baiduspider-favo
百度联盟Baiduspider-cpro
竞价蜘蛛Baiduspider-sfkr

https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/549=095
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/628=426
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/639=405
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/282=517
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/759=661
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/282=530
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/861=960
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/073=962
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/627=728
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/103=294
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/517=284
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/972=549
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/527=006
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/061=951
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/183=073
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/061=983
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/739=061
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/748=848
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/072=306
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/942=880
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/731=164
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/058=163
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/726=608
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/325=880
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/264=594
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/992=608
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/669=669
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/748=523
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/324=150
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/274=931
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md?/383=164
https://github.com/schowffer/nmghjj/blob/main/2026%E7%9B%98%E7%82%B9%E7%99%BE%E7%A7%91%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E5%87%BA%E7%A7%9F-%E8%B0%B7%E6%AD%8C%E8%AE%BA%E5%9D%9B.md
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/588=815
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/807=588
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/644=476
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/206=577
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/325=282
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/760=626
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/859=982
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/861=628
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/949=314
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/182=769
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/648=517
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/658=739
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/303=514
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/082=393
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/107=404
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/730=959
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/606=396
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/436=973
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/172=281
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/293=971
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/517=315
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/181=840
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/397=625
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/871=306
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/518=537
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/381=940
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/194=839
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/505=195
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/950=658
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/273=081
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/395=283
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/816=970
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/243=199
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/526=406
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/950=658
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/060=294
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/208=171
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/173=404
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/062=495
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/083=427
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/872=750
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/325=840
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/961=294
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/172=627
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/627=748
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/069=983
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/214=842
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/738=404
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/972=847
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b?/628=062
https://github.com/schowffer/nmghjj/commit/0561416035d2ba13901da8e3d2cd814fc99ecc2b
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/749=659
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/284=394
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/769=537
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/214=658
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/062=549
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/527=192
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/526=993
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/559=628
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/066=077
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/494=059
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/413=879
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/950=727
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/493=882
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/155=151
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/050=261
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/337=716
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/165=104
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/277=438
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/771=733
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/826=326
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/282=116
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/383=726
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/504=309
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/004=832
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/460=993
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/114=832
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/742=558
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/213=224
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/164=658
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/486=619
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/881=013
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/263=720
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/992=508
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/881=376
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/608=619
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/608=508
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/320=942
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/336=944
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/779=670
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/508=113
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/820=488
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/971=600
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/150=283
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/537=315
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/315=539
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/526=626
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/737=363
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/840=226
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/619=289
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E6%94%BB%E7%95%A5%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E7%A7%91%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%A3%E5%81%9A%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/659=361
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/750=134
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/912=000
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/922=466
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/477=072
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/959=648
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/385=970
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/869=171
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/282=739
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/526=174
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/842=620
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/515=395
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/516=515
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/859=515
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/393=082
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/214=639
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/615=125
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/849=425
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/181=314
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/404=173
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/448=953
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/428=094
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/182=176
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/860=514
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/059=337
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/272=084
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/425=172
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/849=737
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/726=832
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/628=337
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/739=848
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/404=648
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/215=160
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/517=406
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/061=951
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/325=315
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/060=326
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/384=526
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/739=193
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/426=225
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/195=386
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/838=065
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/848=940
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/761=069
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/403=737
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/514=415
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/226=626
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/282=404
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/296=516
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5?/756=061
https://github.com/schowffer/nmghjj/commit/e8cb2a5369e44619a33806ec43d6e300098bcca5
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/800=589
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/103=840
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/130=548
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/190=025
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/799=462
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/888=201
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/625=823
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/466=805
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/709=316
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/402=022
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/944=246
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/700=254
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/422=044
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/578=188
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/533=433
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/479=077
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/799=467
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/982=863
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/799=688
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/144=694
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/133=695
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/076=255
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/160=801
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/803=623
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/588=200
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/732=741
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/688=148
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/244=912
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/867=255
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/926=356
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/577=692
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/466=811
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/680=025
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/360=578
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/939=919
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/795=727
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/707=817
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/688=356
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/701=901
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/451=467
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/811=912
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/973=241
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/140=583
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/473=362
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/685=361
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/583=805
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/272=694
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/354=684
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/134=795
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A2%84%E6%B5%8B%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E6%96%B9%E6%B3%95-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/637=425
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/081=537
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/060=648
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/840=082
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/473=515
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/658=547
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/082=182
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/404=081
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/182=082
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/507=971
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/146=699
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/234=006
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/678=135
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/867=688
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/093=199
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/577=799
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/024=099
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/462=133
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/467=801
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/992=133
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/058=274
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/724=497
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/028=396
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/790=071
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/356=147
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/064=034
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/876=518
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/913=552
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/801=689
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/911=025
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/366=578
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/578=467
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/376=300
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/588=136
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/249=476
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/023=312
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/356=134
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/688=588
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/977=144
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/933=760
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/766=422
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/577=469
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/354=351
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/687=356
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/189=022
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/659=911
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/799=190
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/388=134
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/038=467
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda?/899=793
https://github.com/schowffer/nmghjj/commit/5364d8b7543b545c6ee5c13a164d1be44a803eda
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E5%B7%A5%E5%85%B7-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md?/574=701
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E5%B7%A5%E5%85%B7-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md?/540=078
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E5%B7%A5%E5%85%B7-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md?/245=299
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E5%B7%A5%E5%85%B7-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md?/356=300
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E5%B7%A5%E5%85%B7-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md?/055=689
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E5%B7%A5%E5%85%B7-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md?/133=796
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E5%B7%A5%E5%85%B7-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md?/462=311
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E5%B7%A5%E5%85%B7-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md?/377=794
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E5%B7%A5%E5%85%B7-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md?/467=203
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E5%B7%A5%E5%85%B7-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md?/657=916
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E5%B7%A5%E5%85%B7-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md?/988=911
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E5%B7%A5%E5%85%B7-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md?/201=655
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E5%B7%A5%E5%85%B7-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md?/145=411
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E5%BF%AB%E9%80%9F%E4%BC%98%E5%8C%96%E5%B7%A5%E5%85%B7-%E5%80%BA%E5%88%B8%E8%B4%A2%E7%BB%8F.md?/811=105
