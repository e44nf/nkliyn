百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
静移泼逞弛跃遗毁冻梦姆悠悍杖然

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

https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%9F%A5%E9%81%93%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/972=747
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%9F%A5%E9%81%93%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/951=860
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%9F%A5%E9%81%93%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/395=386
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%9F%A5%E9%81%93%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/525=940
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%9F%A5%E9%81%93%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/273=214
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%9F%A5%E9%81%93%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/758=073
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%9F%A5%E9%81%93%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/618=186
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%9F%A5%E9%81%93%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/067=841
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%9F%A5%E9%81%93%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/749=383
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%9F%A5%E9%81%93%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/658=626
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%9F%A5%E9%81%93%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/062=405
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%9F%A5%E9%81%93%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/974=516
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%9F%A5%E9%81%93%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/971=959
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%9F%A5%E9%81%93%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/115=415
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%9F%A5%E9%81%93%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/173=395
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%9F%A5%E9%81%93%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/528=315
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%9F%A5%E9%81%93%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/394=171
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%9F%A5%E9%81%93%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/519=428
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%9F%A5%E9%81%93%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/969=493
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%9F%A5%E9%81%93%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/740=318
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%9F%A5%E9%81%93%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/748=062
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%9F%A5%E9%81%93%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/061=517
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%9F%A5%E9%81%93%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/253=406
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%9F%A5%E9%81%93%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/618=335
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/518=836
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/104=569
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/931=547
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/770=003
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/275=237
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/286=931
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/647=395
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/971=959
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/659=860
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/061=737
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/840=648
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/626=848
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/860=062
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/627=951
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/515=436
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/404=658
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/405=094
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/394=392
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/840=173
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/817=162
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/293=437
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/760=972
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/859=860
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/537=203
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/527=738
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/950=869
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/306=060
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/282=098
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/951=282
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/282=841
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/404=494
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/516=869
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/840=759
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/382=093
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/082=103
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/648=749
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/283=540
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/071=941
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/283=493
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/174=971
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/062=403
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/106=170
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/292=316
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/840=171
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/859=436
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/785=969
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/161=648
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/315=284
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19?/688=912
https://github.com/schowffer/nmghjj/commit/c1525d32f9f256cb60bfc803e94126e19da8fa19
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/790=589
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/648=244
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/133=366
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/301=067
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/921=027
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/292=947
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/418=610
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/859=204
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/045=251
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/931=447
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/144=375
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/601=700
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/466=912
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/355=790
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/466=871
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/790=788
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/033=923
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/366=735
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/029=734
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/573=811
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/245=766
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/255=923
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/467=734
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/248=805
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/134=363
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/419=793
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/689=811
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/039=357
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/477=466
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/145=890
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/022=023
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/188=801
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/025=849
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/877=134
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/135=860
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/088=974
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/190=311
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/366=427
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/922=033
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/906=801
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/677=140
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/790=033
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/106=069
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/802=366
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/320=688
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/133=942
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/583=823
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/801=128
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md?/855=134
https://github.com/schowffer/nmghjj/blob/main/2026%E4%B8%93%E6%A0%8F%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E6%8E%92%E5%90%8D-%E8%B0%B7%E6%AD%8C%E5%A4%B4%E6%9D%A1.md
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/125=215
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/659=521
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/247=732
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/483=272
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/215=727
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/382=162
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/976=983
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/994=003
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/527=504
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/516=660
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/276=771
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/143=440
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/115=504
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/449=883
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/618=007
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/055=449
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/981=660
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/350=277
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/438=493
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/506=437
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/504=944
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/216=115
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/337=551
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/438=882
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/280=650
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/214=842
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/394=083
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/617=903
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/951=627
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/205=537
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/061=174
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/306=062
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/273=973
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/171=953
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/395=205
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/538=172
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/517=173
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/284=303
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/397=516
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/861=738
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/950=505
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/031=342
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/590=506
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/475=729
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/736=404
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/428=531
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/082=869
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/062=081
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/628=959
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257?/406=148
https://github.com/schowffer/nmghjj/commit/083b63f1494340f98943a1aff67b968e4d5b5257
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/325=615
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/557=597
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/270=385
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/615=526
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/281=617
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/526=172
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/407=515
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/082=479
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/720=549
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/705=393
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/109=224
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/941=597
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/720=508
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/003=980
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/164=880
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/092=385
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/075=608
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/751=007
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/942=164
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/558=992
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/113=710
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/457=992
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/163=464
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/995=802
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/461=368
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/887=235
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/945=064
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/547=820
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/035=825
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/586=941
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/153=002
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/438=499
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/051=002
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/002=558
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/447=947
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/557=609
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/557=720
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/668=436
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/964=381
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/193=618
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/226=283
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/448=058
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/053=396
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/669=386
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/803=163
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/448=717
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/178=944
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/841=159
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md?/447=963
https://github.com/schowffer/nmghjj/blob/main/2027%E7%9B%98%E7%82%B9%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%A4%96%E6%8E%A8%E4%BB%A3%E5%8F%91-%E6%BE%8E%E6%B9%83%E8%AE%BA%E5%9D%9B.md
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/582=961
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/527=304
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/304=682
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/849=073
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/104=183
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/060=104
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/411=137
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/061=950
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/861=637
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/749=849
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/748=526
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/627=633
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/182=416
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/637=183
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/270=183
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/061=474
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/983=959
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/970=062
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/103=739
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/951=628
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/410=973
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/093=322
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/972=593
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/416=502
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/971=794
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/831=392
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/903=102
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/892=769
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/492=057
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/770=618
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/183=334
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/283=072
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/304=960
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/963=403
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/294=850
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/428=549
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/564=541
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/233=836
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/216=640
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/823=557
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/546=610
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/285=003
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/151=313
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/336=015
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/002=918
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/485=819
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/992=103
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/307=446
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/265=375
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716?/114=931
https://github.com/schowffer/nmghjj/commit/4c6058755c9b2b9dedb5cf2cd4e493efdf1f2716
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-360%E8%A7%86%E9%A2%91.md?/728=747
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-360%E8%A7%86%E9%A2%91.md?/742=951
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-360%E8%A7%86%E9%A2%91.md?/970=043
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-360%E8%A7%86%E9%A2%91.md?/481=275
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-360%E8%A7%86%E9%A2%91.md?/074=820
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-360%E8%A7%86%E9%A2%91.md?/153=163
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-360%E8%A7%86%E9%A2%91.md?/992=558
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-360%E8%A7%86%E9%A2%91.md?/053=270
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-360%E8%A7%86%E9%A2%91.md?/224=214
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-360%E8%A7%86%E9%A2%91.md?/520=720
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-360%E8%A7%86%E9%A2%91.md?/550=165
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-360%E8%A7%86%E9%A2%91.md?/374=830
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-360%E8%A7%86%E9%A2%91.md?/202=497
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-360%E8%A7%86%E9%A2%91.md?/103=942
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-360%E8%A7%86%E9%A2%91.md?/153=447
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-360%E8%A7%86%E9%A2%91.md?/044=485
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-360%E8%A7%86%E9%A2%91.md?/385=491
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-360%E8%A7%86%E9%A2%91.md?/275=992
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-360%E8%A7%86%E9%A2%91.md?/114=507
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-360%E8%A7%86%E9%A2%91.md?/163=385
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-360%E8%A7%86%E9%A2%91.md?/711=509
https://github.com/schowffer/nmghjj/blob/main/2026%E7%A7%91%E6%99%AE%E9%80%9A%E6%8A%A5%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E4%BB%A3%E5%8F%91%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D-360%E8%A7%86%E9%A2%91.md?/164=660
