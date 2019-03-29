# 仙女电波  Vol. 0 创世纪
`March 18, 2019 – March 25, 2019 刊`


![图片](https://uploader.shimo.im/f/wagpH0sCBnYUyEt1.png!thumbnail)

## 数据与增量 Data & Delta

[Coin Dance](https://coin.dance/) | [Blockchair](https://blockchair.com/) | [Bitcoinvisuals](https://bitcoinvisuals.com/) | [More](https://medium.com/@chainnews/%E9%80%81%E4%BD%A0-22-%E4%B8%AA%E9%93%BE%E4%B8%8A%E6%95%B0%E6%8D%AE%E8%B5%84%E6%BA%90%E4%B8%8E%E5%8F%AF%E8%A7%86%E5%8C%96%E5%88%A9%E5%99%A8-%E6%B4%9E%E7%A9%BF%E5%8A%A0%E5%AF%86%E6%8A%95%E8%B5%84%E9%87%8D%E9%87%8D%E8%BF%B7%E9%9B%BE-b57f5b4b5727)

| | BTC | ETH | EOS |
|---:|:--:|:--:|:--:|
|Price(usd)| [3,980~3,993](https://www.coingecko.com/zh/%E6%95%B0%E5%AD%97%E8%B4%A7%E5%B8%81/%E4%BB%A5%E5%A4%AA%E5%9D%8A/historical_data/usd?end_date=2019-03-25&start_date=2019-03-18#panel) | [138~136](https://www.coingecko.com/zh/%E6%95%B0%E5%AD%97%E8%B4%A7%E5%B8%81/%E4%BB%A5%E5%A4%AA%E5%9D%8A/historical_data/usd?end_date=2019-03-25&start_date=2019-03-18#panel)|[3.74~3.63](https://www.coingecko.com/zh/%E6%95%B0%E5%AD%97%E8%B4%A7%E5%B8%81/%E6%9F%9A%E5%AD%90%E5%B8%81/historical_data/usd?end_date=2019-03-25&start_date=2019-03-18#panel)|
| HashRate | [43E~52E](https://bitcoinvisuals.com/chain-hash-rate)  | [144~150](https://etherscan.io/chart/hashrate) | |
| Fees | [17~36 BTC]((https://www.blockchain.com/charts/transaction-fees)) | [347~566 ETH](https://etherscan.io/chart/transactionfee)| |
|TPS|[2.66~3.59](https://bitcoinvisuals.com/chain-tx-second)|[6](https://etherscan.io/chart/tx)|[30~60](https://eospark.com/titan?page=transactions-summary)|
|Github Pulse|[+13/-12](https://github.com/bitcoin/bitcoin/pulse)|[+14/-16](https://github.com/ethereum/go-ethereum/pulse)|[+15/-8](https://github.com/EOSIO/eos/pulse)|


### 基建 Infra
- BTC
  - [Announcing Lightning Loop Alpha](https://blog.lightning.engineering/posts/2019/03/20/loop.html)
- ETH
  - [Sunsetting Mist](https://medium.com/@avsa/sunsetting-mist-da21c8e943d2)
  - [Who Are The Core Devs of Ethereum? (Part I)](https://medium.com/ethex-market/who-are-the-core-devs-of-ethereum-part-i-beb342aaaff0) | [(Part II)](https://medium.com/ethex-market/who-are-the-core-devs-of-ethereum-part-ii-3f64b4e5850a)
- EOS
  - [EOSIO.CDT 1.6.0 Release](https://medium.com/@eosio/eosio-cdt-version-1-6-0-building-towards-a-more-seamless-contract-development-experience-2816084a4615)


### 应用 Dapp
* [HashBaby](http://hashbaby.com)
* [CandyOnt](https://candy.ont.io)


## 行业洞察 Industry Insight 
![图片](https://uploader.shimo.im/f/emne5rAAxEMyoZRZ.png!thumbnail)

### V 神首次提出「ZK ZK Rollup」以太坊扩容方案 
以太坊创始人Vitalik于3月15日在台北的演讲上提出[「ZK ZK Rollup」](https://medium.com/@trenton.v/transcript-scalable-blockchains-as-data-layers-vitalik-buterin-11aa18b37e07)的以太坊 Layer 2 层面的扩容方案，可点击链接查阅演讲的 [PPT](https://docs.google.com/presentation/d/1EVjrZhoxw-ikzelFGGv7czxuJsIIWfl5I-CPIlnjsME/edit#slide=id.p) 和 [视频](https://www.youtube.com/watch?v=mOm47gBMfg8)。岛娘也在《[零知识证明与区块链扩容 Zero Knowledge && Blockchain Scalability》](https://hackmd.io/s/rJ5xKzeuN#%E9%9B%B6%E7%9F%A5%E8%AF%86%E8%AF%81%E6%98%8E%E4%B8%8E%E5%8C%BA%E5%9D%97%E9%93%BE%E6%89%A9%E5%AE%B9-Zero-Knowledge-ampamp-Blockchain-Scalability)一文中对区块链扩容进行了自己的解读。

>ZK ZK Rollup 的基本思想就是在 ZK Rollup 的基础上在里面嵌入一个 Mini 版本的 Zcash 机制。这样 Relayer 就无需发布 Txs，而只要发布每次的交易回执（Receipts）即可。除了和 ZK Rollup 一样可以提高 tps 之外，Vatalik 也提到了这种方法的一些潜在应用，其中最为激动人心的的应用就是可以加速跨片之间的交易。

>ZK Rollup 本质上也是一种空间换时间的策略，将每次交易的回执放在链上做验证，而把计算任务放在侧链中完成。通过 ZK ZK Rollup，我们可以更清楚的认识到为什么说 Layer 2 解决方案是不可或缺的了。 
## X-Order「货币战争」系列
《[脑洞：从 BNB 重解商品、证券、货币三位一体「超级载体」的未来意义](https://www.chainnews.com/articles/942975463413.htm)》从劳动结晶这一概念出发，跨越时空维度分析并提出了一个重要观点：“通证其实可以通过设计被任意定制化成不同形态，它是商品，证券和货币的超集，它可以集三位于一体”，并用BNB作为案例予以论证。

@小仙女解读：
文中引入了时间维度，描述了货币即单位劳动结晶、商品即过去劳动结晶、证券即未来劳动结晶。并同时增加了空间概念，认为 BNB 是商品、证券、货币三位一体的超级载体，可能会代替今天的证券以及货币。

然后我们回顾一下证券的分类：1.货币证券，可用来代替货币使用的有价证券，如汇票、支票。2.资本证券，把资本投入企业或把资本供给企业获国家的一种书面证明文件，如股票、债券。3.商品证券，对货物有提取权的证明，如提货单。对标同样的BNB用途图解：

![图片](https://uploader.shimo.im/f/qpWJKWDWXGoMJRCs.png!thumbnail)
（图片来源：《[脑洞：从 BNB 重解商品、证券、货币三位一体「超级载体」的未来意义](https://www.chainnews.com/articles/942975463413.htm)》）

与讨论时间维度相比，小仙女更看重空间维度：交换空间的大小与“劳动结晶”的数量影响了流动性从而影响价格。什么影响了价格？价值量+供给与需求。价格亦等于成本+价值，联想“劳动结晶”即“劳动成本”。因此BNB在追求的无非是更大的空间。

小仙女认为，传统的宏观经济及金融理论仍然是解析数字货币及其市场的重要工具。但对于Token 本身的特点更具有探讨价值，如可编程性及互操作性。考虑到该特性并为将其充分将其转化为流动性，扩大 Token 的空间维度，我们一直推崇 ”One Dapp One Token“，这里的Dapp可以狭义理解为 smart contract , 或广义的理解为 Everything。



![图片](https://uploader.shimo.im/f/8UuseBzpdesLq3Ok.png!thumbnail)


### HashBaby 
Hashbaby 日前的交易量不断上升，多家媒体都有报道：[《我们体验了这款最刺激的DAPP，感到浑身沸腾》](https://mp.weixin.qq.com/s/yHOFMNnIwBNnp3AJrCvtug)、[《波多野结衣的“币圈地震”续：区块链成人产业正野蛮生长》](https://mp.weixin.qq.com/s/IYw7bhmfvxkIa9mWhEamSw)。Hashbaby 用了IPFS 技术来存储图片，而发送或编辑帖子、点赞、打赏等操作则以事件的形式写入EOS区块链。从工程的角度来说，该项目的开发的完成度并不高，尚未提供复杂的功能。但由于发帖和点赞可以“挖矿”，数据一路攀升。

项目初期，有玩家把“币圈”大佬和"女神“的P图传到Hashbaby, 并在DApp圈儿流传，吸引了不少眼球。像Hashbaby这样的情色项目虽博人眼球，但不利于行业的长期发展。


![图片](https://uploader.shimo.im/f/ALeO39QoxUY7oCEi.png!thumbnail)
![图片](https://uploader.shimo.im/f/hKV2ZpUmTrgelkYf.png!thumbnail)
(数据来源：[DApp.review ](https://dapp.review/dapp/10761/#hashbaby)) 

## Candy Ont
>Ontology 最近变得比较热，可能一方面原因是 TOP Network 是 Ont 官方的合作对象，另一方面 Ont 也在进一步扩张，关于 sharding 这块落地也在预期，而合作方包括红杉、真格。不过 Ont 的总体体量已经比较大，其中 Ong 的使用也是关键。大家可以多关注一下。
>—— [Outliers' niche 另类生境 2019-3-21 第50期](https://github.com/xorder-project/Outliers-niche/blob/master/outliers_niche_issue50.md)

这里提到的 TOP Network 就是最近大热的 Huobi Prime 上线的 TOP Network 了！[TOP network](https://www.topnetwork.org/) 是第四代分布式通信网络，本质上是把原有的中心化通信系统做了一个链改，是不是有点类似隔壁 Telegram 的 TON network 呢？公司原有产品叫 [叮咚](https://itunes.apple.com/tw/app/%E5%8F%AE%E5%92%9A-%E7%B6%B2%E7%B5%A1%E9%9B%BB%E8%A9%B1-%E5%9C%8B%E5%85%A7%E5%9C%8B%E9%9A%9B%E9%95%B7%E9%80%94/id588937297)，是一款通信 APP，可以用于收发短信和语音通话。据称有一亿营收。TOP 下个月 testnet 上线，实现了分片和 7000+TPS。该项目将于 03月 26 号上线火币 Prime。关于 Huobi Prime 的更多信息，可以参阅：[火讯专访火币翁晓奇： IEO 是一个跑得快的游戏，Prime 本质是双 11](https://mp.weixin.qq.com/s/T9_ziryPyyUHsw-TKSmmpg)。

而本体的用户已经在 03 月 25 日抢先体验 TOP 的热度啦，根据糖果盒子的开发团队透露（其实就是我们），Candy Ont 上线的首个项目 TOP 第一天上线不到 0.89s 中，5000, 000 额度的 TOP 就被洗劫一空！没有抢到的你也不要拍断大腿，今晚还有一轮，同样是 5000, 000 额度！


## Upcoming 即将到来

 ![图片](https://uploader.shimo.im/f/XImnCbGFkXoJ7ii1.png!thumbnail)

### [03 月 28 日] [CryptoCTF](https://cryptoctf.org/?)，`CTF`
Are you ready to learn hacking Ethereum through realistic examples? 一场新的区块链资安比赛将于本月 28 日开始。
比赛时间为 28th March 2019 8:40~18:00 UTC+01:00。如果你是第一次参加类似比赛，可以参考之前进行的 [Security Innovation Blockchain CTF](https://blockchain-ctf.securityinnovation.com/#/)。Gotta Catch 'Em All！

### [04 月 08~10 日] [EDCON 黑客松](https://mp.weixin.qq.com/s/9h6tcjPzTzY3DrMFv39N7Q)，14500$ `Hackathon`
[EDCON 2019](https://www.edcon.io/) （全球以太坊社区发展峰会）将于 04 月 08 日至 13 日在澳大利亚悉尼举行。本届峰会持续一周，主要包含 EDCON HACK 黑客松（04 月 08 日至 10 日）、 主分会场演讲（04 月 11 日至 13 日）以及会后派对（暂定）等。EDCON HACK 是一个为期三天的黑客松，除了总计 14500 美元的奖金之外，为了鼓励开发者的参与和创新，EDCON 会务组还将为所有黑客松参赛者提供免费门票，用于参与后续的主分会场演讲。

### [04 月 15~30 日] [The Ethereal Hackathon](https://medium.com/gitcoin/the-ethereal-hackathon-4f5dc2eb56d6?fbclid=IwAR1hrGew3O67lxFSqZ16REY9Q-VJmiBMpi8cqQS7LNtHzQRBWo5RpY_eLNI)，25000$, `Hackathon`
Gitcoin 是一家旨在 [Build OSS Sustainability](https://medium.com/gitcoin/code-sponsor-gitcoin-oss-sustainability-5684c4adf4b4) 的由以太坊驱动的线上协作社区。这将会是 Gitcoin 举办的首场线上 Hackathon，除了优胜奖金之外，主办方还会给最终实现并上线的产品提供额外的资助，协办方包括但不限于 Microsoft, ConsenSys Labs, MythX。岛娘的朋友圈已经都在组队了，快来召集你的好友一起参加吧！

### [04 月 13~15 日] [EOS WORLD EXPO 2019](https://www.eosworldexpo.com/) `EXPO`
EOS World Expo 2019 将于下个中旬在三藩举行，作为一个 EOS Only 的 Event，从 [议程](https://www.eosworldexpo.com/#program-section) 上来看，这个活动会 Share 很多 EOS only 的 Insight，这些话题在其他公链上可是不多见的哦。


![图片](https://uploader.shimo.im/f/cUIvxLznh6AIuSEZ.png!thumbnail)

想要成为 Andoromeda 社区开发者？一起 Happy Hunting？
订阅仙女电波，发送邮件到 [newsletter@andoromeda.io](mailto:newsletter@andoromeda.io), 简单介绍你自己，并附上自己的Github 地址，我们将会邮件您。
