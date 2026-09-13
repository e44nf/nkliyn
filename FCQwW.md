百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
悍蜕残杉脊辆毁挡蚁挡透林莱鸥钢

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

https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/757=857
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/084=407
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/106=851
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/746=851
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/695=213
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/484=573
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/729=817
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/415=967
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/306=513
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/418=295
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/140=076
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/419=240
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/991=606
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/968=064
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/584=396
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/181=189
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/705=141
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/857=529
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/630=847
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/130=302
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/962=627
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/963=576
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/184=240
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/285=473
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/072=294
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/037=704
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/749=471
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/304=859
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/179=182
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/406=202
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/627=951
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/186=639
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/587=636
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/063=962
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/837=303
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/051=749
https://github.com/schowffer/nmghjj/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%93%E8%AE%BF%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/244=690
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/355=681
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/577=588
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/100=244
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/148=293
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/639=950
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/516=760
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/294=194
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/204=382
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/306=283
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/494=415
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/172=826
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/193=260
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/749=193
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/293=749
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/294=527
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/850=527
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/415=638
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/298=238
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/294=861
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/960=523
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/071=748
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/960=536
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/204=072
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/293=705
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/283=522
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/077=749
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/305=638
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/966=517
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/415=527
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/637=415
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/516=294
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/163=225
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/153=275
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/991=879
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/608=114
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/283=194
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/304=305
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/148=071
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/633=805
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/740=761
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/526=361
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/417=529
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/249=950
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/461=950
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/415=748
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/527=851
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/861=572
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/184=855
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4?/512=004
https://github.com/schowffer/nmghjj/commit/dd82c7cbb75f4d4ddc6923bbfdb5870b51d257b4
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/583=649
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/838=644
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/759=294
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/537=805
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/404=538
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/526=093
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/393=626
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/293=415
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/293=294
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/293=749
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/689=526
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/688=303
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/770=743
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/113=770
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/072=618
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/850=526
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/527=416
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/627=071
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/693=950
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/804=072
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/950=972
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/305=841
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/644=549
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/594=526
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/462=638
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/727=749
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/316=427
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/650=305
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/071=694
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/293=415
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/184=363
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/740=840
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/746=587
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/851=190
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/294=573
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/630=708
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/741=696
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/577=139
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/316=139
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/755=139
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/428=139
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/636=740
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/697=090
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/303=243
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/957=296
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/418=083
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/960=433
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/526=982
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/503=241
https://github.com/schowffer/nmghjj/blob/main/2027%E4%BB%8A%E6%97%A5%E5%AD%A6%E4%B9%A0%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/578=811
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/700=094
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/022=477
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/800=800
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/249=088
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/022=690
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/992=462
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/626=735
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/148=225
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/694=293
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/133=822
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/801=396
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/738=129
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/417=060
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/395=172
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/304=849
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/084=414
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/281=215
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/517=404
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/758=960
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/560=860
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/103=973
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/519=882
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/062=508
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/903=384
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/392=519
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/969=969
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/860=626
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/547=737
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/162=406
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/737=840
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/393=392
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/204=848
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/504=283
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/171=092
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/404=740
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/173=281
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/951=293
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/761=436
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/292=073
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/923=149
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/404=578
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/472=171
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/919=688
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/033=744
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/784=690
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/478=577
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/378=372
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/755=659
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707?/033=546
https://github.com/schowffer/nmghjj/commit/285c447fcffb116b8f8faca001565a122ed97707
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/335=356
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/831=970
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/444=023
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/799=133
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/840=801
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/700=577
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/258=322
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/145=790
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/866=134
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/601=790
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/790=365
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/799=244
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/790=467
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/350=700
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/474=467
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/916=487
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/034=104
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/211=927
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/901=011
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/102=927
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/634=095
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/871=790
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/792=133
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/534=156
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/911=791
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/574=790
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/355=027
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/688=460
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/028=489
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/701=978
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/977=088
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/466=517
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/794=466
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/790=367
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/618=529
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/074=658
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/596=446
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/091=830
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/614=881
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/719=053
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/124=519
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/486=064
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/213=031
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/214=769
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/608=597
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/481=497
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/053=435
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/927=820
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md?/847=183
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%9C%89%E5%93%AA%E4%BA%9B-%E5%BF%85%E5%BA%94%E9%97%AE%E7%AD%94.md
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/922=255
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/033=866
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/795=139
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/399=699
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/139=029
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/097=134
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/022=255
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/256=790
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/799=781
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/528=365
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/577=456
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/023=201
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/702=476
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/694=038
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/466=688
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/311=336
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/178=484
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/023=479
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/467=356
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/865=077
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/477=033
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/022=598
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/644=999
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/699=578
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/688=189
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/479=356
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/134=912
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/255=025
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/134=680
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/366=366
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/799=255
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/584=649
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/812=144
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/578=477
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/867=578
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/038=855
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/023=141
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/023=356
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/683=703
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/683=069
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/086=978
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/995=680
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/252=701
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/522=051
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/504=581
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/240=609
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/961=912
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/811=701
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/467=267
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc?/685=033
https://github.com/schowffer/nmghjj/commit/c006d6ac411df3bdc7de999916b3a54ba2eb9edc
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%98%AF%E4%BB%80%E4%B9%88-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/378=356
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%98%AF%E4%BB%80%E4%B9%88-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/588=201
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%98%AF%E4%BB%80%E4%B9%88-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/356=366
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%98%AF%E4%BB%80%E4%B9%88-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/645=255
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%98%AF%E4%BB%80%E4%B9%88-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/474=689
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%98%AF%E4%BB%80%E4%B9%88-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/683=699
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%98%AF%E4%BB%80%E4%B9%88-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/011=683
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%98%AF%E4%BB%80%E4%B9%88-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/816=911
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D%E4%BC%98%E5%8C%96%E7%9A%84%E6%96%B9%E6%B3%95%E6%98%AF%E4%BB%80%E4%B9%88-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/409=992
