百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
漳蔡卤讯偃掠庸酝劫牙举胖佬灯美

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

https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E6%9C%89%E5%90%97-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/061=404
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E6%9C%89%E5%90%97-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/071=404
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E6%9C%89%E5%90%97-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/952=560
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E6%9C%89%E5%90%97-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/104=215
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E6%9C%89%E5%90%97-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/417=971
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E6%9C%89%E5%90%97-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/315=405
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E6%9C%89%E5%90%97-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/079=617
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E6%9C%89%E5%90%97-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/549=769
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E6%9C%89%E5%90%97-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/768=284
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E6%9C%89%E5%90%97-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/304=679
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E6%9C%89%E5%90%97-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/086=394
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E6%9C%89%E5%90%97-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/283=405
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E6%9C%89%E5%90%97-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/438=739
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E6%9C%89%E5%90%97-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/773=648
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E6%9C%89%E5%90%97-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/397=285
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E6%9C%89%E5%90%97-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/092=951
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E6%9C%89%E5%90%97-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/473=346
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E6%9C%89%E5%90%97-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/426=966
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E6%9C%89%E5%90%97-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/105=411
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E6%9C%89%E5%90%97-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/245=134
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E6%9C%89%E5%90%97-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/611=311
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E6%9C%89%E5%90%97-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/467=910
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E6%9C%89%E5%90%97-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/203=352
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E6%9C%89%E5%90%97-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/945=790
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E6%9C%89%E5%90%97-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/246=200
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E6%9C%89%E5%90%97-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/114=805
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E6%9C%89%E5%90%97-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/811=134
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E6%9C%89%E5%90%97-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/253=716
https://github.com/schowffer/nmghjj/blob/main/2026%E5%AE%98%E6%96%B9%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E6%9C%89%E5%90%97-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/338=970
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/951=194
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/314=951
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/515=953
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/517=539
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/396=306
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/837=951
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/394=281
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/395=448
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/240=772
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/190=699
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/926=812
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/024=466
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/303=134
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/271=847
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/991=072
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/820=968
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/001=959
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/801=693
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/822=033
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/701=258
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/341=356
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/144=467
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/355=469
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/022=134
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/599=536
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/355=244
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/083=866
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/244=465
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/695=067
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/799=321
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/790=355
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/444=705
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/466=741
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/588=699
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/689=535
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/277=130
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/467=355
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/956=799
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/914=412
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/700=468
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/577=316
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/028=034
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/881=011
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/588=700
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/400=912
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/644=089
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/599=683
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/796=033
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d?/366=577
https://github.com/schowffer/nmghjj/commit/3755fe4fac443cdb21ca9488a4e2fdfa62113f9d
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/577=705
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/601=796
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/589=412
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/240=790
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/245=134
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/712=098
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/477=570
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/977=923
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/310=546
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/495=315
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/691=250
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/685=038
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/806=866
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/138=793
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/219=629
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/917=794
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/791=462
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/170=802
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/466=256
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/828=295
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/396=927
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/683=356
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/039=605
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/802=352
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/678=772
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/699=922
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/134=982
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/467=570
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/818=916
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/573=801
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/688=366
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/290=145
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/755=027
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/861=804
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/689=145
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/027=801
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/790=799
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/800=245
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/053=345
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/923=689
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/492=270
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/771=836
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/982=505
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/549=309
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/782=409
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/559=883
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/616=770
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/991=460
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md?/406=779
https://github.com/schowffer/nmghjj/blob/main/2026%E7%B2%BE%E9%80%89%E4%BA%86%E8%A7%A3%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84-%E4%BC%98%E9%85%B7%E7%A4%BE%E8%AE%BA.md
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/584=957
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/695=361
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/807=694
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/686=919
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/699=574
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/240=351
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/133=095
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/950=919
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/917=020
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/144=477
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/811=368
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/911=795
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/801=911
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/909=355
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/698=366
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/744=433
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/247=367
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/811=811
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/699=917
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/477=477
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/022=697
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/351=363
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/144=801
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/601=467
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/678=356
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/688=789
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/588=684
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/790=237
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/534=245
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/466=578
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/467=566
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/134=133
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/133=573
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/396=917
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/922=301
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/356=466
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/810=139
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/801=244
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/922=215
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/022=134
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/133=978
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/688=796
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/924=801
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/544=795
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/145=915
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/367=467
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/023=648
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/356=577
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/917=145
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba?/245=577
https://github.com/schowffer/nmghjj/commit/3e42d20ba817a32b418173e0e53c082cf2b2d8ba
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/792=299
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/366=477
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/801=690
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/533=143
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/245=467
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/950=573
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/255=243
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/353=023
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/712=813
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/467=790
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/366=819
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/179=466
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/139=466
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/033=202
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/796=471
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/367=577
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/489=533
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/579=362
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/033=977
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/355=760
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/912=879
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/690=194
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/311=367
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/498=100
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/806=355
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/760=312
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/469=100
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/711=695
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/790=689
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/144=933
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/254=144
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/840=636
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/751=840
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/951=236
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/848=062
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/547=526
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/958=428
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/973=093
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/173=404
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/061=437
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/528=382
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/726=849
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/959=404
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/739=630
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/282=315
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/840=104
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/392=061
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/951=271
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md?/848=071
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E5%8F%AF%E6%B5%8B%E8%AF%95%E7%9A%84%E8%AF%8D%E8%AF%AD-%E4%BA%AC%E4%B8%9C%E8%AF%BB%E6%8A%A5.md
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/199=356
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/201=912
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/756=025
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/244=484
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/688=690
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/684=922
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/362=199
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/899=699
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/577=147
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/533=255
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/818=755
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/700=466
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/355=377
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/795=255
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/695=360
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/511=255
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/477=198
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/926=353
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/912=099
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/688=700
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/805=463
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/800=799
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/582=021
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/865=324
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/927=688
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/184=799
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/791=462
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/061=077
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/082=848
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/104=638
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/071=951
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/417=292
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/659=408
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/974=051
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/173=051
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/424=395
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/404=405
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/517=407
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/384=295
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/640=105
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/214=858
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/437=537
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/283=535
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/173=626
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/060=172
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/061=636
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/517=981
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/737=303
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/959=759
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33?/626=646
https://github.com/schowffer/nmghjj/commit/97082cb10eace86958a7f3b3797cdf0b1780ec33
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%8F%91%E5%85%B3%E9%94%AE%E8%AF%8D-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md?/870=539
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%8F%91%E5%85%B3%E9%94%AE%E8%AF%8D-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md?/840=495
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%8F%91%E5%85%B3%E9%94%AE%E8%AF%8D-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md?/771=485
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%8F%91%E5%85%B3%E9%94%AE%E8%AF%8D-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md?/284=060
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%8F%91%E5%85%B3%E9%94%AE%E8%AF%8D-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md?/328=759
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%8F%91%E5%85%B3%E9%94%AE%E8%AF%8D-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md?/203=103
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%8F%91%E5%85%B3%E9%94%AE%E8%AF%8D-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md?/648=282
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%8F%91%E5%85%B3%E9%94%AE%E8%AF%8D-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md?/170=436
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%8F%91%E5%85%B3%E9%94%AE%E8%AF%8D-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md?/114=769
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%8F%91%E5%85%B3%E9%94%AE%E8%AF%8D-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md?/265=492
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%8F%91%E5%85%B3%E9%94%AE%E8%AF%8D-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md?/164=492
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%8F%91%E5%85%B3%E9%94%AE%E8%AF%8D-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md?/820=387
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%8F%91%E5%85%B3%E9%94%AE%E8%AF%8D-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md?/720=626
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%8F%91%E5%85%B3%E9%94%AE%E8%AF%8D-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md?/779=729
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%8F%91%E5%85%B3%E9%94%AE%E8%AF%8D-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md?/114=608
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%8F%91%E5%85%B3%E9%94%AE%E8%AF%8D-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md?/729=557
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%8F%91%E5%85%B3%E9%94%AE%E8%AF%8D-%E8%8D%89%E8%8E%93%E6%97%B6%E5%B0%9A.md?/337=114
