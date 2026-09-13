百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
蛊刻廖忌朴浩乌匕习释匮访聊痪凸

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

https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/795=695
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/962=960
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/085=546
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/106=696
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/078=851
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/534=262
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/306=634
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/284=030
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/695=817
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/749=583
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/759=993
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/072=171
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/738=685
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/172=859
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/526=316
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/294=415
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/645=071
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/859=994
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/183=361
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/245=950
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/496=173
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/992=114
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/525=617
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/249=396
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/426=099
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/772=493
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/550=721
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/605=516
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/993=326
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/994=835
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/103=458
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/725=275
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md?/517=669
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E5%A4%96%E6%B1%87%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/180=635
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/406=746
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/527=745
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/068=317
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/206=302
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/073=335
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/179=395
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/073=539
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/060=362
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/208=630
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/519=870
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/083=738
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/995=405
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/959=751
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/627=962
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/537=383
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/103=954
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/060=437
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/072=165
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/406=273
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/173=861
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/630=397
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/072=635
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/316=635
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/856=067
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/910=295
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/289=540
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/523=139
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/392=539
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/879=746
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/252=407
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/417=079
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/184=292
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/078=956
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/439=202
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/297=073
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/083=185
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/973=084
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/864=362
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/539=413
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/413=295
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/817=739
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/551=295
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/852=795
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/963=076
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/751=585
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/646=447
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/807=070
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/746=851
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3?/836=506
https://github.com/schowffer/nmghjj/commit/03826acc47f457c80b511bb9b3ac126a3b045aa3
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/963=845
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/919=524
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/851=303
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/639=474
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/962=351
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/302=957
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/795=807
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/528=141
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/313=741
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/403=740
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/306=290
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/413=412
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/524=195
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/534=131
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/306=874
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/305=963
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/307=806
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/745=747
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/807=748
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/413=743
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/106=873
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/524=740
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/072=639
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/293=415
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/305=185
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/090=815
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/460=737
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/594=548
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/628=880
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/701=631
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/245=022
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/658=326
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/860=205
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/951=193
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/407=873
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/362=950
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/416=961
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/200=070
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/173=171
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/961=959
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/749=527
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/293=183
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/185=627
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/582=037
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/759=850
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/204=748
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/526=182
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/694=416
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/960=185
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%3A%E4%BB%A3%E5%BC%95%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/730=526
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/960=793
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/194=570
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/326=188
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/647=317
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/961=748
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/805=148
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/737=527
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/372=072
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/148=685
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/292=805
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/416=072
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/293=461
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/304=294
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/859=526
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/184=182
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/637=182
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/849=963
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/871=415
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/637=960
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/560=748
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/315=637
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/026=850
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/859=648
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/249=988
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/638=204
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/516=972
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/523=967
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/959=638
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/515=304
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/193=305
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/182=194
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/182=761
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/916=121
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/695=900
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/918=241
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/416=392
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/538=305
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/193=282
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/872=184
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/960=204
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/437=850
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/032=948
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/182=416
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/320=307
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/293=072
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/705=426
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/711=693
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/360=073
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453?/626=415
https://github.com/schowffer/nmghjj/commit/ed6609039f4b7dd7fdc55afa7df87838f6871453
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/183=077
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/529=071
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/527=303
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/471=294
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/037=214
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/121=417
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/749=637
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/305=748
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/971=526
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/298=183
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/849=627
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/393=305
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/359=938
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/645=362
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/951=307
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/852=637
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/830=072
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/951=840
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/962=639
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/573=419
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/243=529
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/796=174
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/423=650
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/413=208
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/295=295
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/850=073
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/727=410
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/073=735
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/859=540
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/968=529
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/529=474
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/416=735
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/295=284
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/031=685
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/073=535
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/762=290
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/528=518
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/641=862
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/523=573
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/958=762
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/396=745
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/772=638
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/293=315
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/968=183
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/394=527
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/637=417
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/178=293
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/185=071
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/505=960
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/992=514
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/980=055
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/033=901
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/318=123
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/467=355
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/467=689
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/694=478
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/249=799
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/698=790
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/801=025
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/173=947
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/033=139
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/477=422
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/790=896
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/878=028
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/700=358
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/917=357
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/689=355
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/476=468
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/134=581
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/022=577
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/456=355
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/577=801
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/911=868
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/689=806
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/801=244
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/134=939
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/437=106
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/940=968
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/060=171
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/525=626
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/959=204
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/273=537
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/493=737
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/272=315
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/737=206
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/737=515
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/404=969
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/058=959
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/285=626
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/536=973
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/728=669
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/538=215
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/840=282
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/083=526
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/286=839
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/282=414
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/657=758
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/204=227
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2?/627=635
https://github.com/schowffer/nmghjj/commit/ff1aa942217401e1c9dae6cf7684a7d3e236fbb2
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A.md?/382=860
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A.md?/404=403
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A.md?/316=082
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A.md?/349=407
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A.md?/805=355
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A.md?/700=588
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A.md?/802=689
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A.md?/255=405
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A.md?/736=471
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A.md?/385=457
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A.md?/818=527
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E4%BB%A3%E5%BC%95%E8%9C%98%E8%9B%9B-%E5%B0%8F%E7%BA%A2%E4%B9%A6%E6%97%B6%E5%B0%9A.md?/757=871
