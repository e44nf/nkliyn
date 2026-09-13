百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
栈乱曳耪乱制脑恼惶僖智灼腋暇锌

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

https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/351=584
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/817=816
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/583=461
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/351=465
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/430=680
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/795=028
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/243=701
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/462=355
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/361=039
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/402=818
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/629=362
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/628=204
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/951=071
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/517=295
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/083=861
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/394=284
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/317=183
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/517=630
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/964=647
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/731=858
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/950=860
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/851=616
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/859=407
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/737=071
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/072=953
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/938=631
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/314=730
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/748=059
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/618=860
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/638=184
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/294=328
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/059=397
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/749=971
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/959=960
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/759=325
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/626=061
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/297=394
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/848=293
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/139=477
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/916=468
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/578=860
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651?/466=361
https://github.com/schowffer/nmghjj/commit/74af37ef50b72c0c422c78ab253dad333ccb0651
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/244=588
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/423=467
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/144=811
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/333=689
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/922=100
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/315=028
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/485=404
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/902=495
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/637=909
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/463=744
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/463=467
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/306=796
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/592=972
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/588=911
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/978=249
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/844=145
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/611=701
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/134=911
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/078=478
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/699=357
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/365=700
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/477=611
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/366=145
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/578=356
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/355=655
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/694=588
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/812=255
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/477=355
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/622=461
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/151=659
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/351=687
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/312=911
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/062=890
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/423=978
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/319=467
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/022=799
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/156=367
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/095=477
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/023=464
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/911=578
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/106=700
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/892=044
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/045=023
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/912=023
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/970=901
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/244=804
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/578=022
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/255=588
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/356=461
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E6%8C%87%E5%AF%BC%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E4%B8%8A%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E6%8E%92-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/817=033
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/900=133
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/134=812
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/155=290
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/912=588
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/800=477
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/245=466
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/645=911
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/917=178
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/734=582
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/313=125
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/612=146
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/055=700
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/033=800
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/212=468
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/104=255
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/930=701
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/144=588
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/522=167
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/588=134
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/477=700
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/463=244
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/566=966
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/790=622
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/356=588
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/587=790
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/149=147
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/130=701
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/033=029
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/401=911
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/245=795
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/689=401
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/588=240
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/271=790
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/800=795
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/533=477
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/133=689
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/845=911
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/500=685
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/578=366
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/244=467
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/801=588
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/799=366
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/701=245
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/911=819
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/912=139
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/004=666
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/890=800
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/699=351
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105?/295=368
https://github.com/schowffer/nmghjj/commit/2d2db63b4b4df21a5a768825266590a4419d0105
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/356=919
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/916=578
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/912=099
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/917=694
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/577=368
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/033=144
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/489=245
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/877=766
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/799=144
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/033=583
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/144=299
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/167=022
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/003=042
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/090=164
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/981=669
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/396=164
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/558=658
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/014=518
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/272=264
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/669=164
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/385=063
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/658=169
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/492=407
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/286=325
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/493=618
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/325=496
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/610=608
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/558=164
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/936=624
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/619=057
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/614=668
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/668=992
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/163=275
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/615=935
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/397=723
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/969=126
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/780=002
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/557=278
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/669=941
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/779=509
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/651=882
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/626=739
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/184=404
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/952=647
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/958=493
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/193=407
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/859=103
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/071=193
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/739=301
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/145=355
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/922=368
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/477=022
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/756=099
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/800=022
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/388=467
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/831=477
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/801=267
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/860=866
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/766=688
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/790=688
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/688=277
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/366=133
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/801=445
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/299=911
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/033=928
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/688=246
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/790=548
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/240=278
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/280=801
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/134=866
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/801=395
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/790=976
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/979=144
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/033=015
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/890=138
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/472=478
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/290=684
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/623=588
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/145=088
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/335=238
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/729=568
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/880=004
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/620=557
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/826=830
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/668=557
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/669=503
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/052=569
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/387=496
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/832=177
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/881=831
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/803=320
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/614=446
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/114=831
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/166=226
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/003=829
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/625=369
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/173=404
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/181=958
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e?/283=162
https://github.com/schowffer/nmghjj/commit/329413834fa6bf5225846f28152ab155f0cd965e
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/839=194
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/084=294
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/304=837
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/183=237
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/393=993
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/659=397
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/724=748
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/173=071
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/104=970
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/406=493
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/171=637
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/225=406
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/647=494
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/284=283
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/293=404
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/640=730
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/182=637
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/733=282
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/843=865
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/270=428
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/859=950
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/351=912
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/669=731
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/003=537
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/982=496
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/003=116
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/931=052
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/447=779
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/611=002
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/832=386
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/335=153
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/074=160
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/448=042
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/103=447
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/941=053
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/264=058
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/992=135
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/769=971
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/829=980
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/496=448
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/729=719
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/666=830
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/724=102
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/274=833
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/508=770
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/076=830
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/244=232
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/360=400
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md?/661=421
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E9%A6%96%E9%A1%B5%E6%8E%A5%E5%8D%95%E4%BB%A3%E5%81%9A-%E5%8D%B3%E5%88%BB%E6%97%A5%E6%8A%A5.md
https://github.com/schowffer/nmghjj/commit/818816ac7bedc74e87641a3b99171e69d2855797?/022=485
https://github.com/schowffer/nmghjj/commit/818816ac7bedc74e87641a3b99171e69d2855797?/589=257
https://github.com/schowffer/nmghjj/commit/818816ac7bedc74e87641a3b99171e69d2855797?/866=199
https://github.com/schowffer/nmghjj/commit/818816ac7bedc74e87641a3b99171e69d2855797?/645=423
