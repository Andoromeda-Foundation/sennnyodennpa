# 仙女电波  Vol. 2 卡姆斯基测试
`April 02 2019 – April 08, 2019 刊`

本期编辑：岛娘、Aaryn

[hackmd 编辑地址](https://hackmd.io/SluIRdeVQUOJelovR3H0RA)

![图片](https://uploader.shimo.im/f/0psCxWBcKnANQYeC.png!thumbnail)

## 数据与增量 Data & Delta

### 基建 Infra

- BTC

    - 比特币工具箱 [Libbitcoin]( https://libbitcoin.org/)
    - 闪电网络支付工具 [tippin.me](https://tippin.me/)，可以在 Twitter 上直接付小费


  - [《比特幣暴漲帶動一日漲勢，專家：高達 1 億美元的神秘買單引發》](https://www.blocktempo.com/us-crypto-currencies-bitcoin-jumps-20-percent-mystery-order-seen-as-catalyst/) ，“分析師指出，比特幣的飆漲，帶動了其他密碼貨幣的交易市場。而掀起市場波瀾的原因，可能是因為一位匿名的買家「自動交易的方式」買進了大量的比特幣，推升了比特幣的價格。”

  - [《「Traders 動起來了」：芝商所（CME）的比特幣期貨交易量再創新高》](https://www.blocktempo.com/cme-bitocin-futures-new-high/) ，上周比特币迎来几日的大涨，由于行情波动较大，合约交易也创新高。

- ETH

    上周，宝博士在智能签名发表了他回顾 [激进市场](https://smartsignature.io/article/Qmdd61fhUoQQBABde1tfF6qaXVgqL7yv8dQLkkiyLF8cW1) 的文章，正好 Vitalik 前几天的 [新作](https://vitalik.ca/general/2019/04/03/collusion.html)，再次在这个方向展开了探讨。文章讨论使用通证激励来维系社群合作时，所产生的合谋问题。当然 V 神也不忘黑一把 EOS，可从这里查看这篇文章的 [中文翻译。](https://smartsignature.io/article/QmdpS5jXtNzpytjGQozqScA9ZtQUNjyHHc5mJndRSh1nyu) 

    
- EOS
    - [BlockOne 发布 EOSIO Labs](https://medium.com/eosio/introducing-eosio-labs-a-place-for-open-innovation-55bd939eb53a)，其中发布的通用授权库（Universal Authenticator Library）中包含 4 种登录授权方式: TokenPocket, Scatter, Lynx 和 硬件钱包Ledger。 意味着Dapp 开发者 使用EOSIO Labs的通用库，即可实现与TokenPocket 等各个钱包的交互。大大减少开发者的开发成本。
     - [Block.one 发布 EOSIO v1.7.1 版本更新](https://github.com/EOSIO/eos/releases)
    
       

### DAPP
   
  - [《论一个单日 7.2 亿流水 Dapp 的倒下》](https://mp.weixin.qq.com/s/4qm6_etwlVgufFET00QDCQ) 
  DappReview 本周发表了一篇长文，讲述了波场上两个具有代表性的项目 888TRON 和 TronCrush 的兴衰史。从文章中我们可以一窥 Dapp 生态的秘辛。以人为鉴，可以明得失；以史为鉴，可以知兴替。
  
    > 888 Tron 在3月15-16日的48小时里，该游戏分给玩家约 5000万人民币价值的TRX。

    > TronCrush 由于上线前做足了预热，3月26号首日挖矿流水惊人的突破了12亿TRX。

    > 以上两个案例，除了技术问题和游戏的机制设计之外，更本质的暴露出了项目方对于市场的无知。目前的 Dapp 大多带有金融属性，而金融的本质是信息不对称，Smart Money 并不在乎你的产品逻辑和游戏机制，在乎的是如何利用信息不对称赚取超额收益，如果开发者不懂市场，也不敬畏市场，还去开发金融属性的游戏，“市场先生”分分钟教你做人。
    > 

  - [LoreFree, 基于 EOS 和 IPFS 的去中心化知识共享社区](http://www.lorefree.com/) 
    从网站的介绍来看，该项目计划有三个里程碑：
    1. 免费电子图书分享平台
    2. 阅读写作服务平台
    3. 搭建知识公链LoreChain。
  
      目前用户已经可以在上面进行上传和下载电子书资源，电子书将通过IPFS来存储，上传电子书的用户可以通过贡献奖励来获得通证奖励。目前来看，Lore Free 已经成为了盗版电子书的集聚地，并且种类齐全。
      
      理论上讲，不止是电子书，任何文件，如音频、视频等等都可以通过相同的方式来进行分享。比起 Lore Free 这种传播盗版的方式，如如何用区块链技术来保护原创，更值得被提倡。
      


  - [《刑事局破獲首宗「以 EOS 為賭注」的總統大選賭博 DApp，區塊鏈賭博爭議如何解？》](https://www.blocktempo.com/taiwan-eos-gamble-bet-president-election-1) 
    上周仙女电波编辑组推荐了这款以大选为主题的 EOS 游戏，主要原因是项目的前端和合约均开源，完美符合小仙女们关于 可分叉 Dapp 的要求。很遗憾的是，这款 Dapp 居然上线一周就被端了，我和几位台湾的开发者交流都表示了惋惜，预测市场和菠菜之间的界限有时候并不是那么清楚。
    
    > 基于 EOS 的菠菜 DApp 已屡见不鲜，但由于大选将至，近日，名为「2020总统大选 」的赌博网站引起了警方注意。该网站是建立在 EOS 上的去中心化应用，使用 EOS 下注后，会待明年一月选举投票结束且锁定总统候选人后，竞猜获胜。律师表示，因选举结果并非纯然是依靠几率，所以不一定完全符合法律上赌博罪的不确定性条件。
    

## 行业洞察 Industry Insight 🔭
![](https://camo.githubusercontent.com/47906664c901cc073495658cb2f1aa8aa08c4d8f/68747470733a2f2f75706c6f616465722e7368696d6f2e696d2f662f656d6e653572414178454d796f5a525a2e706e67217468756d626e61696c)

### Defi 开放式金融

DeFi 已经取代 Fintech 成为时下区块链最热点的话题。

#### 什么是 DeFi? 

[热点：开放式金融全景图](https://mp.weixin.qq.com/s/g3293N_Pr5VA9cdH1aPMog)
> DeFi 是「Decentralized Finance」的缩写，指的是「去中心化金融」，在区块链的世界中，也称为「Open Finance 开放式金融」，因为这个概念指代那些在开放的去中心化网络中发展而出的各类金融领域的应用，目标是建立一个多层面的金融系统，以区块链技术和密码货币为基础，重新创造并完善已有的金融体系。

#### DeFi 和 Fintech 的区别

DeFi 与传统 FinTech 的区别在于 Fintech 更多的是基于数据与机器学习算法，使得金融机构可以更精准的作出信用的评估和预测等等，以提供更好的服务。而 DeFi 则是由开源软件驱动的，它对所有参与者都一视同仁，任何人都可以参与进来。

#### DeFi 的优势

[洞见 | 潘超：DeFi 的理论与实践](https://ethfans.org/posts/defi-theories-and-practices-by-Chao-Pan) 中指出，去中心化金融的核心和优势在于**无需准入**。无需准入有三个层级：开发者的无需准入、节点的无需准入和用户的无需准入。
> 我们看到 DeFi 的核心是围绕着无需准入、低门槛进行的。去中心化金融的目标不是去中心化本身，而是更加开放和公平。

#### DeFi 的现状

[看懂DeFi，为什么多数去中心化金融产品没有用户](https://mp.weixin.qq.com/s/XeFjHvU_KsSGHAlBzXBKkw)
> 对于开发者和商家来说，由于 DeFi 项目大部分是搭建在链上比如以太坊，产品开发将受到现有区块链技术性能的制约。换句话说，如果以太坊性能不得到突破，那么上面一百多个 DeFi 产品技术的突破也十分有限，其它公链也是如此。
> 
> 对于市场用户来说，Defi 产品和 DAPP 应用一样，仍然存在很多落地问题，都面临着用户体验差、用户准入门槛高的问题。现阶段的 Defi 产品，仍是以牺牲用户的效率为代价，换取隐私、资产安全和资产管理自由等。
>
> Defi 希望创造一个极低成本、透明、去信任化的流动性和借贷市场，这种优势在普通用户的进入门槛和成本面前，显得毫无吸引力。这也是目前大部分 DeFi 项目根本没人用的重要原因。

#### DeFi 项目举例

去中心化交易所和协议：[0x](https://0x.org/)、[uniswap](https://uniswap.io/)、[Kyber Network](https://kyber.network/)、[Bancor Network](https://www.bancor.network/)、[Ren](https://renproject.io/)、[IDex](https://idex.market/)

借贷协议：[Maker DAO](https://makerdao.com/en/)、[Compound](https://compound.finance/)、[Dharma](https://www.dharma.io/)

与身份认证相关的 DeFi 项目: [Bloom](https://bloom.co/) 、[Project Hydro](https://projecthydro.org/)、[SelfKey](https://selfkey.org/)

### 监管
- [《【重要】美國證券交易委員會 SEC 發佈了「密碼貨幣、代幣」監管指南》](https://www.blocktempo.com/sex-clearing-ico-to-sell-tokens-under-us-law/)

- [《金管會 STO 草案規劃：募資額 3,000 萬以下採群募概念；3,000 萬元以上進沙盒》](https://www.blocktempo.com/taiwan-fsc-sto-1m/)，台湾金管会主委顾立雄表示，目前证券型代币发行（STO）的草案规划将以募资额3000万台币作为分野，以下采群募概念，以上进入监理沙盒实验。

- [中國「區塊鏈審查」《區塊鏈信息服務管理》備案名單出爐，百度、阿里、騰訊、京東都在內](https://www.blocktempo.com/china-blockchain-censorship-list-include-batj)

### 稳定币
- [最大穩定幣 Tether 更新條款：穩定幣 USDT 可能「不會只由美元作為儲備」](https://www.blocktempo.com/tether-says-its-usdt-stablecoin-may-not-be-backed-by-fiat-alone-1)

- [波場（Tron）宣稱：將在其區塊鏈上空投「6 億台幣」的 USDT 穩定幣](https://www.blocktempo.com/tron-airdrop-20m-usdt-on-its-blockchain)

### 交易所

- [打鐵趁熱？趙長鵬宣布：本月將推出新加坡「法幣交易所」，幣安 DEX 主網也將於本月上線](https://www.blocktempo.com/binance-new-progress-singapore-dex/)

- [Coinbase 宣布：為客戶「熱儲存的 2.55億美元」資產投保](https://www.blocktempo.com/coinbase-confirms-extent-of-crypto-insurance-coverage)

### 投融资
- [全球最大的區塊鏈創投公司 DCG，過去三年來的投資案表現如何？](https://www.blocktempo.com/dcg-blockchain-deal-data)

- [日本新創圈「第二間新創獨角獸」：Liquid.com 在 IDG、比特大陸融資下誕生](https://www.blocktempo.com/liquid-series-c-1-billion-bitmain-idg/)

- [矽谷超級天使投資人、創投傳奇「a16z」註冊為財務顧問，計劃進行更多包括 Crypto 在內的高風險投資](https://www.blocktempo.com/andreessen-horowitz-is-blowing-up-the-venture-capital-model-again/)

## 密码朋克 Cypherpunk 💻

### Gitcoin

本周岛娘接了一个 Gitcoin 上的 Bounty，给 Redeem Kudos 页面增加 Twitter 登录的接口，奖金是 1 个 eth。这个功能可以顺利开发完成吗？让我们拭目以待吧。

https://gitcoin.co/issue/gitcoinco/web/4111/2733



## 即将到来 Upcoming

 ![图片](https://uploader.shimo.im/f/XImnCbGFkXoJ7ii1.png!thumbnail)
 
 ### [04 月 08~10 日] [EDCON 黑客松](https://mp.weixin.qq.com/s/9h6tcjPzTzY3DrMFv39N7Q)，14500$ `Hackathon`
[EDCON 2019](https://www.edcon.io/) （全球以太坊社区发展峰会）将于 04 月 08 日至 13 日在澳大利亚悉尼举行。本届峰会持续一周，主要包含 EDCON HACK 黑客松（04 月 08 日至 10 日）、 主分会场演讲（04 月 11 日至 13 日）以及会后派对（暂定）等。EDCON HACK 是一个为期三天的黑客松，除了总计 14500 美元的奖金之外，为了鼓励开发者的参与和创新，EDCON 会务组还将为所有黑客松参赛者提供免费门票，用于参与后续的主分会场演讲。

### [04 月 15~30 日] [The Ethereal Hackathon](https://medium.com/gitcoin/the-ethereal-hackathon-4f5dc2eb56d6?fbclid=IwAR1hrGew3O67lxFSqZ16REY9Q-VJmiBMpi8cqQS7LNtHzQRBWo5RpY_eLNI)，25000$, `Hackathon`
Gitcoin 是一家旨在 [Build OSS Sustainability](https://medium.com/gitcoin/code-sponsor-gitcoin-oss-sustainability-5684c4adf4b4) 的由以太坊驱动的线上协作社区。这将会是 Gitcoin 举办的首场线上 Hackathon，除了优胜奖金之外，主办方还会给最终实现并上线的产品提供额外的资助，协办方包括但不限于 Microsoft, ConsenSys Labs, MythX。岛娘的朋友圈已经都在组队了，快来召集你的好友一起参加吧！

### [04 月 13~15 日] [EOS WORLD EXPO 2019](https://www.eosworldexpo.com/) `EXPO`
EOS World Expo 2019 将于下个中旬在三藩举行，作为一个 EOS Only 的 Event，从 [议程](https://www.eosworldexpo.com/#program-section) 上来看，这个活动会 Share 很多 EOS only 的 Insight，这些话题在其他公链上可是不多见的哦。

仙女电波，关注宇宙人与赛博空间。投稿与订阅，请发送邮件到 [newsletter@andoromeda.io](mailto:newsletter@andoromeda.io) 或在 Github 下提交 pr，祝有好收获。
