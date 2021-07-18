# StarLink 内测游戏方法

参与游戏测试的玩家可以下载 iopay 手机钱包或者桌面钱包。然后使用一个**对你不是那么重要的钱包**的钱包进行游戏。

**游戏期间请关闭 vpn 的全局模式，以免出现连接不上钱包的问题。如果你浏览器有安装 adblock，请暂时关闭 adblock，避免出现连不上服务器的问题。**

游戏中游玩过程中目前有发现时有的掉线，请大家不要担心，重新使用钱包签名即可，我们会在后续版本修复这个问题，不影响您游玩游戏。

建议大家测试使用 iopay 的桌面版，这样能在浏览器中打开开发者工具查询日志，这样我们比较容易定位问题。

游戏 loainding 界面结束以后大约等待 5-10 秒钟（根据网络情况可能会有所延长，请耐心等待）会弹出来钱包的签名，点击确认即可进入游戏。

![image](https://github.com/GameFantasyDev/StarLinkBetaTest/blob/main/IMG/loading.png)

由于本次测试在 iotex 的测试网。所以您需要一些测试网的 iotex 作为 gas。请确认您的 iopay 连接到了测试网。然后打开如下的网站：
https://faucet.iotex.io/
这里可以每个人申请一次 1000 个 iotx 测试币。用于游戏内的 gas 已经足够。

![image](https://github.com/GameFantasyDev/StarLinkBetaTest/blob/main/IMG/testtoken.png)

如果您想要进行流动性挖矿，则你需要打开 mimov2，在添加流动性页面输入：0xb5f92e508d020f479291582996798476a085e517 以添加测试网 GFT。

![image](https://github.com/GameFantasyDev/StarLinkBetaTest/blob/main/IMG/lp1.png)

![image](https://github.com/GameFantasyDev/StarLinkBetaTest/blob/main/IMG/lp2.png)

如何使用 iopay 转为测试网？
pc：
![image](https://github.com/GameFantasyDev/StarLinkBetaTest/blob/main/IMG/pc.png)

mobile:
![image](https://github.com/GameFantasyDev/StarLinkBetaTest/blob/main/IMG/mobile.png)

mimov2 在 pc 上如何转测试网？
https://iotexdefi.com/
这里可以往 metamask 上添加 iotex 的主网和测试网，然后切换测试网即可。

特别注意：如果您在游戏内执行合约失败，请一定确认自己当前网络切换到了测试网。

![image](https://github.com/GameFantasyDev/StarLinkBetaTest/blob/main/IMG/main.png)

游戏主界面下方有四个按钮分别对应为：

- nft 展示界面
- nft 合成界面
- nft 交易拍卖界面
- nft 挖矿界面

## nft 展示界面

点击进第一个按钮进入 nft 展示界面，这也是游戏默认初始化界面。一开始可能大家都没有新猫咪。不用着急，你可以在交易拍卖界面中获得您的猫咪。如果你获得了属于你的猫咪的话可以在这里看到您猫咪的信息。右上角的感叹号可以查看猫咪详细的品质和信息。如果您的猫咪身体部位总分达到一个分值的时候，猫咪卡牌的背景将会发生改变。

## nft 合成界面

![image](https://github.com/GameFantasyDev/StarLinkBetaTest/blob/main/IMG/mix.png)

nft 合成界面可以将两张 nft 卡牌进行合成。从而有机会获得品质更高的卡牌，所有属性将从父母亲卡牌中继承和进化。所有身体部位的稀有度是不会低于父母亲双方的原有稀有度的。所以合成的时候大家一定要掌握好这个最基本的原则。如果您想您的卡牌某个部位保持某个稀有度，那你必须至少让父母双方都达到这个稀有度。（比如 R 和 R 合成是不会生成比 R 还要低的品质的）选定好合成的卡牌以后，点击合成调用合约，等待大约 10 秒左右合约会执行完毕将会播放合成动画，生成新的卡牌。

## nft 交易拍卖界面

nft 交易拍卖界面我们分为三部分来说：

#### nft 交易界面

进入市场默认打开的就是 nft 交易界面。在这里可以看到玩家自己在游戏中挂出来售卖的卡牌。上面会有售价，点击购买会弹出猫咪的详情界面。再此点击确认调用合约以后等待 10 秒左右如果您的 GFT 余额足够则会将这张卡牌购买到您的仓库中。

#### nft 拍卖界面：

这里是官方直拍的界面。在这里永远都会有 20 张卡牌等待大家的领养。只要任何一个玩家对其中一个出价则会开始倒计时。在经过一定的区块数（一个区块大概是 5 秒）如果没有人继续出价，则这个卡牌的倒计时会增加一定数量的区块。直到没有人出价为止，这个卡牌则会进入个人所有流程。你可以在第三个界面中领取这个卡牌。注意，这块目前还在优化中，列表刷新速度不是很快，请耐心等待。

#### 我的卡牌界面：

这个界面会列出来所有你拥有的卡牌，包括你正在售卖，可以领取的卡牌。你也可以在这个界面将自己的卡牌挂到市场上售卖。别的玩家将可以在第一个界面里查看到你的挂单信息。如果成交，会从你能获得的金额中扣除 0.3%作为手续费。这个手续费会存入到游戏的分红池内。供长期对游戏做出贡献的玩家共同分享。

## nft 挖矿界面：

nft 卡牌有一个属性叫做挖矿力，这个能力决定了你的这张卡牌派遣出去挖矿所占的权重。挖矿矿池将会根据所有卡牌的挖矿力总和来进行 GFT 的分配。一旦您将 nft 卡牌派遣出去挖矿了，这张卡牌将从您的仓库里移除。但是您仍然能在挖矿见面看到它并且将它召回。直到你将它召回位置，这张 nft 卡牌将暂时不属于您。

nft 挖矿界面有一个 lp 挖矿，这里您可以使用 gft 和 iotx 配对在 mimo 上提供流动性以获得 lp token。在这个鸡面里将 lp token 质押就可以参与流动性挖矿，流动性挖矿的奖励将是游戏的 dao 治理代币 gfs。持有 gfs 以后将可以分享游戏分红池内的奖励。gfs 以后还会开放在游戏内玩游戏的其他获取方式。gfs 将采取公平分发的方式，获得方式只有为游戏做出贡献。