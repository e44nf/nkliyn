百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
劝倍魏孛忍越缓捞尤股镣拷劝蚜都

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

https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%B1%87-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md?/517=975
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%B1%87-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md?/244=139
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%B1%87-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md?/645=799
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%B1%87-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md?/911=133
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%B1%87-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md?/738=199
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%B1%87-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md?/537=182
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%B1%87-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md?/293=638
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%B1%87-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md?/750=172
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%B1%87-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md?/983=919
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%B1%87-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md?/425=416
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%B1%87-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md?/415=305
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%B1%87-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md?/082=293
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%B1%87-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md?/850=293
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%B1%87-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md?/850=962
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%B1%87-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md?/705=859
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%B1%87-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md?/307=183
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%B1%87-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md?/637=327
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%B1%87-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md?/416=738
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%B1%87-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md?/292=201
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%B1%87-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md?/138=204
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%B1%87-%E8%85%BE%E8%AE%AF%E6%B1%87%E5%B8%82.md
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/522=138
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/527=860
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/637=849
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/304=950
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/638=740
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/462=872
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/294=637
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/360=087
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/350=733
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/860=950
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/255=962
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/744=527
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/416=859
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/859=910
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/748=871
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/596=350
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/627=627
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/462=415
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/526=959
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/840=187
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/404=749
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/959=282
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/730=871
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/951=515
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/103=951
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/427=404
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/853=283
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/853=760
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/759=192
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/738=074
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/173=315
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/860=517
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/262=639
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/062=881
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/394=860
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/426=869
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/392=282
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/507=392
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/284=648
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/515=273
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/639=171
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/426=615
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/873=648
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/437=985
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/848=406
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/738=315
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/404=435
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/271=104
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/260=103
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7?/397=628
https://github.com/schowffer/nmghjj/commit/0885ac585c2c4a775671989990877db0de9eb5e7
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/062=759
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/283=161
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/770=258
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/628=537
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/615=739
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/973=282
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/425=629
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/971=173
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/741=840
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/836=841
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/747=758
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/726=861
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/840=859
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/769=515
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/758=727
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/959=862
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/384=326
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/848=173
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/392=739
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/770=171
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/283=739
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/060=627
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/514=959
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/337=062
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/145=317
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/343=784
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/588=396
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/497=549
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/542=626
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/769=292
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/071=215
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/537=620
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/760=404
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/647=381
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/658=970
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/204=841
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/554=627
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/383=060
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/648=548
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/960=741
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/759=183
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/627=395
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/516=418
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/425=979
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/293=739
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/624=394
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/940=193
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/404=740
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md?/273=060
https://github.com/schowffer/nmghjj/blob/main/2026%E5%BD%A9%E6%B0%91%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D-%E6%90%9C%E7%8B%90%E8%BE%9F%E8%B0%A3.md
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/318=517
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/819=581
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/356=439
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/617=623
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/840=406
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/639=750
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/970=529
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/564=579
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/464=628
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/627=081
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/217=494
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/286=183
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/306=016
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/073=125
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/749=739
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/438=971
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/539=172
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/091=306
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/740=294
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/862=872
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/538=638
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/173=516
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/305=194
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/639=628
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/505=517
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/406=395
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/325=750
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/951=950
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/317=493
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/227=769
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/938=400
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/594=337
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/152=559
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/265=327
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/484=994
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/885=731
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/309=507
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/004=616
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/440=416
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/114=500
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/726=504
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/094=448
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/291=504
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/357=155
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/578=383
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/809=432
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/660=699
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/203=403
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/830=995
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b?/849=393
https://github.com/schowffer/nmghjj/commit/1714c53dc31c4cf605837bc9f2c7b36273d88f3b
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/855=628
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/947=912
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/818=396
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/606=437
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/189=726
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/950=437
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/382=396
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/726=173
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/393=294
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/893=539
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/060=281
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/515=737
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/415=941
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/637=951
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/526=626
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/626=282
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/759=185
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/393=960
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/638=415
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/290=305
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/035=991
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/705=206
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/891=942
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/003=058
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/175=936
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/507=952
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/071=264
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/947=507
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/608=436
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/042=380
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/880=831
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/671=668
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/195=373
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/315=779
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/170=759
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/518=316
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/750=959
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/849=759
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/316=647
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/072=769
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/649=314
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/952=194
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/080=418
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/749=981
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/062=438
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/062=284
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/862=950
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/516=626
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/064=426
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/358=375
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/050=002
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/642=568
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/447=496
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/769=069
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/596=547
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/831=272
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/508=227
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/310=375
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/879=546
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/371=485
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/508=669
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/679=947
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/387=095
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/770=500
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/169=336
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/537=858
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/840=084
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/840=739
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/193=060
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/940=052
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/860=517
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/951=204
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/759=806
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/384=515
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/496=273
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/426=972
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/406=516
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/875=620
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/425=884
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/695=649
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/739=284
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/549=620
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/072=750
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/495=618
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/859=960
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/748=305
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/316=494
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/761=284
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/172=620
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/849=397
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/053=170
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/981=548
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/773=395
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/658=849
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/620=428
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/639=395
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/751=517
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/284=538
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/283=436
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/079=063
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/305=530
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/652=493
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/883=716
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/522=943
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/828=161
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/572=727
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/337=382
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/873=943
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/505=575
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/660=163
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/216=027
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/329=615
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/411=615
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/448=216
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/984=216
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/498=954
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/729=726
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/071=870
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/050=155
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/638=448
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/092=197
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/891=376
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/486=507
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/224=836
