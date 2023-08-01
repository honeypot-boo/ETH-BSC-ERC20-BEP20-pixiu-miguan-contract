# 如何创建 ERC20/BEP20 貔貅币（蜜罐合约）

## 包含内容

### 蜜罐合约教学与案例

- Hello 貔貅：HelloPixiu
- 超长空格的欺骗：WhaleGiveaway1
- 天上掉下的馅饼：Gift_1_ETH
- 合约永远比你有钱：MultiplicatorX3
- 谁是合约主人：TestBank
- 加密轮盘赌轮：CryptoRoulette
- 开放地址彩票：OpenAddressLottery
- Solidity 结构体局部变量引起的变量覆盖
- 山丘之王：KingOfTheHill
- 以太币竞争游戏：RACEFORETH
- 黑客的漏洞利用
- 私人银行(重入漏洞)：PrivateBank
- 偷梁换柱的地址(访问控制)：firstTest
- 仅仅是测试？(整数溢出)：For_Test
- 股息分配（老版本编译器漏洞）：DividendDistributor

### 蜜罐合约初级版本实现与讲解 (适合新人)

- 仅所有者有权限出售代币
- 所有者可随时更改智能合约规则
- 极限低gas批量发币
- 批量创建钱包地址

### 蜜罐合约中级版本实现与讲解

- 实现有条件动态禁售，小额放行，大额禁售，躲避部分蜜罐检测
- 设置禁售定时器等，确保代币在初始阶段的合法性
- 如何计算DEX代币对合约地址，实现高级蜜罐合约
- 动态设置白名单与黑名单，实现隐式蜜罐合约
- 低成本分散代币，增加持有地址数量，躲避部分蜜罐检测

### 蜜罐合约高级版本实现与讲解

- 如何通过合约操作DEX交易，并且在链上数据浏览器中显示未“随机”地址 ([basescan](https://basescan.org/tx/0x9de5563e52b60e81b91c3d0f3b4445b413156ef31f97f37b82753dd0e8f4a3a3)|[bscscan](https://bscscan.com/tx/0xcf7625872bd52baaef928752a5e22c53292bc0f8eaff46e764a5d2dd77e49daf))
- 利用代理函数实现隐式禁售，绕过脚本的蜜罐检测，交易机器人的噩梦
- 在区块链浏览器上使用隐藏函数进行合约验证
- 蜜罐检查器原理，以及绕过蜜罐检测器的5种实现方法


## 价格

| 内容                                                        | 价格    |
| ----------------------------------------------------------- | ------- |
| 【蜜罐合约教学与案例】+【蜜罐合约初级版本实现与讲解】       | 0.1 eth |
| 【蜜罐合约教学与案例】+【蜜罐合约初+中级版本实现与讲解】    | 0.3 eth |
| 【蜜罐合约教学与案例】+【蜜罐合约初+中+高级版本实现与讲解】 | 0.5 eth |

## ERC20代码示例

[案例 1](https://dexscreener.com/base/0xed3d2e85aac07503933a1f813a27fdd0384c9984)
[案例 2](https://www.dextools.io/app/cn/base/pair-explorer/0x12279c46ecce850443ca875948459c231e25b6af)
[案例 3](https://www.dextools.io/app/cn/base/pair-explorer/0xed3d2e85aac07503933a1f813a27fdd0384c9984)

## BEP20代码示例

[案例 1](https://poocoin.app/tokens/0x7a2261022487c1aed6f53571494c46a1b4a213fa)
[案例 2](https://www.coinsniper.net/coin/16153)
[案例 3](https://bscscan.com/address/0x7a2261022487C1AED6f53571494C46A1B4a213fA)

## 购买方式？

ETH地址：`0x5bBdC61338029d7063Bd4216d7975d7e11c27Eb9`

电子邮件：`hacker@honeypot.boo`

将ETH发送到指定地址，获取交易链接并通过电子邮件发送。验证后，您将在电子邮件中收到包裹。您还会通过电子邮件收到解释视频，介绍如何操作和修改智能合约，如何进行白名单验证，如何引入通货膨胀（向特定地址铸造新代币）等等。

## 免责声明

本教程仅供个人研究与学习，请勿将其用于非法图途径，由此产生的后果由您本人自行承担。
