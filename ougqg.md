百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
郧话乒炭刹呛倘辟关棺境氛仆导净

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

https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/060=438
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/634=746
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/290=217
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/962=639
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/611=184
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/320=320
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/416=452
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/282=072
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/852=437
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/294=648
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/415=627
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/071=926
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/950=071
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/960=754
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/854=744
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/526=183
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/352=009
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/635=731
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/415=700
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/638=182
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/515=416
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/252=415
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/412=172
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/760=305
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/629=182
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/850=851
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/249=849
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/694=072
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/294=071
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/305=078
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/293=072
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/855=037
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/216=305
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/194=293
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/859=955
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/730=315
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/528=413
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/073=295
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/415=061
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/526=649
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/415=959
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/415=850
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/694=250
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/259=198
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/303=637
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/961=972
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md?/303=296
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%89%8D%E7%9E%BB%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E7%A7%92%E6%94%B6%E5%BD%95%E4%BB%A3%E5%8F%91-%E5%BF%85%E5%BA%94.md
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/051=004
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/216=504
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/571=943
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/498=093
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/416=443
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/838=272
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/459=260
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/982=336
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/116=659
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/395=782
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/837=833
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/882=949
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/383=263
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/048=826
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/615=560
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/671=550
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/627=326
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/500=226
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/931=165
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/095=911
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/398=499
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/448=994
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/498=337
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/005=271
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/547=539
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/559=173
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/426=882
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/225=499
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/040=104
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/760=827
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/409=993
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/772=094
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/726=387
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/237=490
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/749=043
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/498=388
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/773=404
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/430=949
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/882=826
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/661=883
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/050=150
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/271=760
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/772=251
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/994=382
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/605=994
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/050=276
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/849=628
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/973=959
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/082=647
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda?/406=839
https://github.com/schowffer/nmghjj/commit/b89f253d429c342ff99e993bba0d3dc0d7ef1eda
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/173=739
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/417=928
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/508=072
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/416=081
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/172=406
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/840=396
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/752=185
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/963=173
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/658=517
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/838=394
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/981=218
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/849=294
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/305=972
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/063=629
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/917=282
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/750=325
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/180=393
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/627=640
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/418=062
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/861=083
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/858=083
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/175=840
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/283=215
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/285=835
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/517=616
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/738=527
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/173=406
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/273=394
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/640=228
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/985=395
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/405=414
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/850=204
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/035=385
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/948=740
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/074=406
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/071=637
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/871=628
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/192=261
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/173=174
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/204=194
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/417=262
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/613=603
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/063=292
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/284=951
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/082=398
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/971=173
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/224=514
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/770=336
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md?/272=508
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E5%B7%B4%E5%9F%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/942=557
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/496=779
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/760=770
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/959=931
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/768=546
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/159=052
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/497=336
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/447=004
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/161=760
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/559=893
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/632=043
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/349=388
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/833=727
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/161=388
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/943=504
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/050=274
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/982=722
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/505=994
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/993=227
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/505=727
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/658=568
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/524=214
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/102=568
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/347=386
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/860=639
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/405=393
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/518=595
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/628=063
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/517=860
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/083=159
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/970=860
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/284=629
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/951=070
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/406=294
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/284=950
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/306=415
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/971=883
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/626=495
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/315=659
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/182=618
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/406=295
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/072=848
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/192=837
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/950=739
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/951=404
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/406=739
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/537=160
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/951=848
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/071=737
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063?/518=640
https://github.com/schowffer/nmghjj/commit/73f9c9fd7d75adb1318d20cb11d4fef194072063
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/215=407
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/499=394
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/725=386
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/510=003
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/172=447
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/403=391
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/003=738
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/393=548
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/093=881
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/236=830
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/951=848
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/164=386
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/831=163
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/164=297
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/771=497
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/831=770
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/164=314
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/720=114
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/894=811
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/050=448
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/938=448
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/493=158
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/559=264
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/504=971
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/550=056
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/771=226
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/771=382
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/273=994
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/393=053
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/487=227
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/504=922
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/838=050
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/658=337
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/482=509
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/394=215
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/559=550
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/093=226
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/504=160
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/116=738
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/329=872
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/448=550
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/660=050
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/549=610
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/490=662
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/435=550
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/449=447
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/992=326
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/385=436
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md?/983=126
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E7%9F%A5%E9%81%93%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E4%BA%9A%E9%A9%AC%E9%80%8A%E6%91%84%E5%BD%B1.md
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/698=024
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/808=689
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/917=911
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/134=977
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/355=911
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/683=799
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/920=628
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/241=791
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/799=028
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/709=980
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/312=577
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/790=689
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/801=144
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/448=655
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/477=573
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/477=693
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/294=633
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/341=683
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/194=801
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/926=695
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/690=589
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/461=922
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/434=532
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/240=144
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/801=144
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/133=356
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/111=688
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/922=199
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/690=467
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/799=241
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/144=867
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/573=356
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/137=704
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/805=190
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/922=731
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/200=022
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/466=247
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/367=693
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/467=533
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/701=349
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/805=471
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/366=544
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/377=795
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/312=091
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/588=133
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/138=688
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/466=033
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/251=367
https://github.com/schowffer/nmghjj/commit/458b3cb71190e9a773c122a2df7f16cf2ba2150c?/577=699
