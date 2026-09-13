百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
日诓言仁睹敢诨俗弦挛门忱娇叛习

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

https://github.com/schowffer/nmghjj/blob/main/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E4%BB%A3%E5%8F%91%E6%8E%A5%E5%8D%95-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/322=597
https://github.com/schowffer/nmghjj/blob/main/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E4%BB%A3%E5%8F%91%E6%8E%A5%E5%8D%95-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/507=598
https://github.com/schowffer/nmghjj/blob/main/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E4%BB%A3%E5%8F%91%E6%8E%A5%E5%8D%95-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/414=658
https://github.com/schowffer/nmghjj/blob/main/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E4%BB%A3%E5%8F%91%E6%8E%A5%E5%8D%95-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/668=103
https://github.com/schowffer/nmghjj/blob/main/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E4%BB%A3%E5%8F%91%E6%8E%A5%E5%8D%95-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/618=777
https://github.com/schowffer/nmghjj/blob/main/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E4%BB%A3%E5%8F%91%E6%8E%A5%E5%8D%95-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/447=991
https://github.com/schowffer/nmghjj/blob/main/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E4%BB%A3%E5%8F%91%E6%8E%A5%E5%8D%95-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md?/180=610
https://github.com/schowffer/nmghjj/blob/main/2026%E6%99%AE%E5%8F%8A%E7%8E%8B%E7%89%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E4%BB%A3%E5%8F%91%E6%8E%A5%E5%8D%95-%E7%9F%A5%E4%B9%8E%E5%AE%89%E9%98%B2.md
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/769=840
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/626=960
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/739=174
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/417=069
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/071=406
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/425=281
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/517=628
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/756=315
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/114=548
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/182=060
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/860=860
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/417=061
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/955=073
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/081=837
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/870=960
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/650=739
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/384=737
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/658=625
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/629=504
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/947=627
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/912=134
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/026=172
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/335=103
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/125=931
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/071=293
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/321=912
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/498=918
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/356=226
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/277=749
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/368=688
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/207=131
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/423=033
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/355=588
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/134=533
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/477=188
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/807=133
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/982=022
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/467=866
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/467=911
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/912=689
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/579=021
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/921=194
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/577=259
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/690=578
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/923=366
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/359=467
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/541=295
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/917=023
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/464=139
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd?/462=151
https://github.com/schowffer/nmghjj/commit/1f1d8245de0965bb3fff7b0f934d4748d53fbcdd
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/580=973
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/917=327
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/028=039
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/417=694
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/473=816
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/462=151
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/684=795
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/540=928
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/244=463
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/249=584
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/538=917
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/140=462
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/789=640
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/429=728
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/798=680
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/130=808
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/306=251
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/461=028
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/684=240
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/866=419
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/195=361
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/817=694
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/705=579
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/017=640
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/462=361
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/166=205
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/400=982
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/723=365
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/290=246
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/680=784
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/073=138
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/462=791
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/488=366
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/316=988
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/547=558
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/226=053
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/668=042
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/163=335
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/770=859
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/041=052
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/721=941
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/338=549
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/832=716
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/116=912
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/716=223
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/045=619
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/052=870
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/025=003
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md?/616=882
https://github.com/schowffer/nmghjj/blob/main/2027%E4%B8%93%E6%A0%8F%E6%8E%A8%E8%8D%90%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%94%B6%E5%BD%95-%E5%87%A4%E5%87%B0%E4%BC%97%E6%B5%8B.md
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/203=071
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/517=749
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/193=292
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/970=971
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/728=515
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/737=038
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/969=648
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/871=950
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/425=173
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/274=624
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/192=759
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/606=606
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/170=195
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/063=315
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/060=759
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/628=648
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/162=393
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/940=314
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/953=958
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/737=951
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/171=951
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/840=192
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/504=951
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/625=893
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/245=367
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/800=867
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/811=255
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/979=567
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/911=705
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/023=250
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/144=577
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/138=199
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/689=142
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/790=362
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/356=683
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/578=022
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/880=881
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/305=003
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/785=064
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/155=712
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/249=801
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/099=378
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/755=571
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/245=689
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/577=099
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/661=688
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/023=155
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/189=574
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/684=139
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa?/474=717
https://github.com/schowffer/nmghjj/commit/57a06f174952b5c1f6efa23002cb6732e627ecfa
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/584=139
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/272=094
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/684=806
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/462=708
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/023=708
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/846=728
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/699=722
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/084=640
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/927=240
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/841=868
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/973=852
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/537=316
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/206=515
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/951=626
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/395=759
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/060=959
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/062=960
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/972=062
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/314=739
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/105=062
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/983=283
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/740=627
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/383=506
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/903=950
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/627=417
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/759=420
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/250=981
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/394=183
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/172=406
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/830=349
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/315=394
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/283=173
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/028=193
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/039=130
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/667=682
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/161=860
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/939=710
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/641=005
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/902=070
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/483=506
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/284=130
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/295=140
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/906=373
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/240=706
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/684=495
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/684=962
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/573=912
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/316=699
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/790=689
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E5%A4%A7%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%80%8E%E4%B9%88%E6%8E%92-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/685=459
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/973=918
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/362=706
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/584=818
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/695=462
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/916=139
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/279=806
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/705=028
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/089=457
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/589=135
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/463=791
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/650=240
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/802=139
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/917=139
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/922=862
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/706=796
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/038=888
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/816=430
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/988=705
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/917=132
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/587=413
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/578=338
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/132=139
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/151=577
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/039=239
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/684=249
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/472=977
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/494=629
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/917=039
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/284=478
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/175=284
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/527=537
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/728=983
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/394=627
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/195=626
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/270=941
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/516=516
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/739=740
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/549=539
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/284=205
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/193=082
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/395=438
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/517=405
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/626=081
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/849=316
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/283=316
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/060=405
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/728=083
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/172=638
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6?/839=162
https://github.com/schowffer/nmghjj/commit/3ae83459bd916204eb2886d15ab34f2e1fd440a6
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/060=938
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/648=638
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/406=073
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/192=940
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/060=528
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/953=325
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/949=361
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/710=050
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/004=627
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/115=271
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/226=005
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/437=549
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/737=827
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/883=627
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/722=338
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/494=337
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/993=377
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/993=284
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/406=093
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/108=748
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/656=740
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/828=866
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/004=642
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/772=160
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/806=683
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/462=862
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/088=306
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/685=584
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/740=151
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/252=351
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/084=028
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/139=467
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/916=928
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/272=151
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/802=367
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/862=928
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/573=806
https://github.com/schowffer/nmghjj/blob/main/2027%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E6%8E%92%E5%90%8D%E6%95%99%E7%A8%8B-%E8%84%89%E8%84%89%E6%9C%AD%E8%AE%B0.md?/350=161
