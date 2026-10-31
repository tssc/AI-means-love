# 补充稿（待 Han 决定纳入方式）· 币安 63 亿美元被盗与重大加密资产盗窃史

> 状态：已定稿发布。Han 2026-10-31 决定——做成独立专题页 HEISTS.md（EN + ZH-CN），不进主时间线、不计入 events.json。本稿为其底稿存档。
> 背景：Han 2026-10-31 指示——「还有类似币安被盗事件、也加入我的 GitHub 项目稿件。」
> 说明：本稿事件属网络安全 / 加密资产安全史，与项目既有的 AI 编年史主线不同，故单设专题页收纳，主时间线保持只记 AI。
> 日期口径：币安 2026 事件按北京时间记 2026-10-30（币安官方《安全事件进展公告 #2》：约在 2026 年 10 月 30 日 04:05 东八区时间，热钱包遭到攻击；与 Reuters 所述「周四 20:00 GMT 后不久开始」一致）。

![无合适配图，留空](无)  <!-- 官方公告与报道配图未取得可直接引用的图片链接，故留空，不硬配 -->

---

## 主条（拟补录）· 2026-10-30 币安遭遇史上最大加密资产盗窃

- **日期**：2026-10-30（北京时间 04:05 起；UTC 为 10 月 29 日 20:00 后）
- **类别**：网络安全事件
- **主角**：Binance（币安）

### 发生了什么

全球最大加密货币交易所币安的热钱包遭到攻击，约 63 亿美元加密资产被转出，为加密货币史上最大盗窃案，约为 2025 年 2 月 Bybit 被盗 15 亿美元的四倍。区块链记录显示，主要转出在约 20 分钟内完成，横跨以太坊、比特币、波场、Solana、XRP Ledger 等多条网络。

币安 10 月 30 日的初步调查称，事件可能源于一名 DevOps 工程师的笔记本电脑被入侵，攻击者借此访问服务容器并提交未经授权的提现交易；后续调查又发现了其他入侵点。币安称未发现钱包私钥泄露的证据。区块链分析公司 TRM Labs 认为，被攻破的是币安的签名基础设施——即授权交易放行的系统。

### 处置与追回

- 币安暂停提现并展开全面安全审查，承诺以公司自有资金承担全部损失：已内部预留约 63.4 亿美元，其中约 50 亿美元以被盗的同种资产持有，其余约 13 亿美元正通过市场与 OTC 渠道购入；另有约 10 亿美元比特币储备的 SAFU 用户安全基金。
- 稳定币发行方与合作伙伴已冻结约 30 亿美元被盗资产：Tether 冻结逾 15.67 亿美元 USDT、Circle 冻结逾 8 亿美元 USDC、Ripple 约 2 亿美元、World Liberty Financial 约 0.27–0.29 亿美元。
- TRM Labs 估计，攻击者仍控制约 24 亿美元难以被冻结的资产（包括大量 ETH 与约 18,270 枚 BTC）——比特币与以太坊没有发行方可以远程冻结，只能靠流入受监管交易所时拦截或执法取得私钥。
- 归因未定：TRM Labs 与 Elliptic 认为手法与朝鲜 TraderTraitor（Lazarus 系）组织高度相似，TRM 对「与 Bybit 案同一伙人」给出高置信判断；币安自身表示尚未确认攻击者身份，朝鲜方面惯常否认。此为分析机构判断，非已证实结论，调查仍在进行。

### 为什么值得被历史记住

它把数字资产安全的老问题推到了极端：一台被入侵的工程师笔记本，可能撬动授权成千上万用户资产的签名系统——「钥匙没丢，丢的是盖章的系统」。同时，它也展示了这个行业独有的追回机制：中心化稳定币可以在链上远程冻结，于是约一半赃款在几小时内被钉在原地。攻防两端，都已不是个人黑客与小网站的量级。

### 它带来的善

如果币安如约全额承担损失，普通用户第一次在如此规模的盗窃中不承担后果；行业层面，这次事件迫使所有大型平台重新审查签名基础设施与员工终端安全，其完整技术复盘（币安已承诺发布）将成为全行业的安全教材。

### 来源

- 官方：币安《安全事件进展公告 #2》（2026-10-30，binance.com）https://www.binance.com/zh-CN/square/post/382974122328634
- 独立报道：Reuters《Gone in 20 minutes: How the biggest heist in crypto history unfolded》（2026-10-30）https://www.reuters.com/legal/government/gone-20-minutes-how-biggest-heist-crypto-history-unfolded-2026-10-30/
- 独立报道：The Block《Binance says it has $6.34 billion ready to cover hack losses》（2026-10-30）https://www.theblock.co/news/ecosystems/2026-10-30-binance-says-it-has-6-34-billion-ready-to-cover-hack-losses-432208
- 中文报道：财新《全球最大加密货币交易所遭黑客入侵 币安被盗 63 亿美元》（2026-10-30）https://finance.caixin.com/2026-10-30/102499146.html

### English version (canonical)

# Supplement (pending Han's decision) · Binance's $6.3B heist, in context

- **Date**: 2026-10-30 (Beijing time, from ~04:05 CST; 20:00 UTC, Oct 29)
- **Category**: Cybersecurity incident
- **Protagonist**: Binance

## What happened

Attackers drained about $6.3 billion of crypto from the hot wallets of Binance, the world's largest crypto exchange — the biggest crypto theft on record, roughly four times the $1.5 billion Bybit hack of February 2025. Blockchain records show the bulk moved in about 20 minutes, across Ethereum, Bitcoin, Tron, Solana, the XRP Ledger and other networks.

Binance's preliminary investigation points to a compromised DevOps engineer's laptop, which gave the attacker access to a service container used to submit unauthorized withdrawal transactions; the exchange later said it had found additional points of breach, and reported no evidence of a wallet private-key leak. Blockchain analytics firm TRM Labs says the attackers compromised Binance's signing infrastructure — the system that authorizes transactions.

## Response and recovery

- Binance suspended withdrawals, began a full security review, and pledged to cover all losses from company funds: about $6.34 billion set aside internally, roughly $5 billion of it already held in the same assets that were taken, the remaining ~$1.3 billion being bought through market and OTC channels; the exchange also operates the SAFU fund, a $1 billion bitcoin reserve for user protection.
- Stablecoin issuers and partners froze about $3 billion of the stolen assets: Tether froze over $1.567 billion in USDT, Circle over $800 million in USDC, Ripple about $200 million, and World Liberty Financial roughly $27–29 million.
- TRM estimates about $2.4 billion — mostly bitcoin and ether, which no issuer can freeze remotely — remains beyond easy reach.
- Attribution is unsettled: TRM Labs and Elliptic see strong similarities to North Korea's TraderTraitor (Lazarus-linked) operations, with TRM highly confident it is the same group as the Bybit hack; Binance itself has not identified the attackers, and North Korea routinely denies such claims. Investigation ongoing.

## Why it matters

The biggest crypto heist ever was not a stolen vault key but a hijacked authorization system — one compromised laptop reaching the machinery that tells the vault to release money. And the recovery shows the industry's unique other side: centrally issued stablecoins can be frozen on-chain, pinning about half the loot in place within hours.

## The good it brings

If Binance makes users whole as pledged, ordinary customers bear none of the cost of the largest theft in the industry's history; and the promised full technical post-mortem would become a security textbook for every major platform.

## Sources

- Official: Binance, Security Incident Update #2 (2026-10-30) https://www.binance.com/zh-CN/square/post/382974122328634
- Independent: Reuters (2026-10-30) https://www.reuters.com/legal/government/gone-20-minutes-how-biggest-heist-crypto-history-unfolded-2026-10-30/
- Independent: The Block (2026-10-30) https://www.theblock.co/news/ecosystems/2026-10-30-binance-says-it-has-6-34-billion-ready-to-cover-hack-losses-432208

---

## 附表（拟作专题附录）· 此前的重大加密资产盗窃事件

按涉案金额排序；金额为事件发生时估值，口径见各来源。Reuters 排行表（2026-10-30）为主要依据，币安自家两次旧案另据 CoinDesk 等核对。

| 日期 | 事件 | 涉案金额 | 一句话经过 |
|---|---|---|---|
| 2025-02-21 | Bybit 被盗 | 约 15 亿美元 | 以太币冷钱包被攻破；FBI 归因于朝鲜 TraderTraitor 组织 |
| 2021-08 | Poly Network 被盗 | 约 6.1 亿美元 | DeFi 跨链平台被利用漏洞盗走，黑客后几近全额归还 |
| 2022-10-06 | BNB Chain 跨链桥被利用（币安生态） | 约 5.7 亿美元被铸出，实际转出约 1–1.1 亿美元 | BSC Token Hub 证明验证漏洞被伪造证明铸出 200 万枚 BNB；验证者停链冻结大部分，未动用户资金 |
| 2022-03 | Ronin Network 被盗 | 约 5.4 亿美元 | Axie Infinity 侧链被盗 173,600 枚 ETH 与 2,550 万 USDC |
| 2018-01 | Coincheck 被盗 | 约 5.3 亿美元 | 热钱包被攻破，引发日本交易所安全监管收紧 |
| 2011–2014 | Mt. Gox 被盗 | 约 5 亿美元 | 曾占全球比特币交易八成的交易所长期失窃，2014 年破产，约 2.4 万客户受影响 |
| 2022-02 | Wormhole 被盗 | 约 3.2 亿美元 | 跨链桥漏洞被盗 12 万枚封装 ETH，Jump Trading 后补足资金 |
| 2019-05-07 | 币安热钱包被盗 | 7,000 枚 BTC，约 4,000 万美元 | 钓鱼与病毒窃取 API 密钥与 2FA 码，单笔转出；币安以 SAFU 基金全额赔付，用户无损 |

来源：Reuters 排行表 https://www.reuters.com/legal/government/where-binances-63-billion-breach-ranks-cryptos-biggest-hacks-heists-2026-10-30/ ；FBI 关于 Bybit 的公告（2025-02-26，PSA I-022625-PSA）；CoinDesk 关于币安 2019 年被盗 https://www.coindesk.com/markets/2019/05/07/hackers-steal-407-million-in-bitcoin-from-crypto-exchange-binance/ 与 BNB Chain 2022 年事件 https://www.coindesk.com/business/2022/10/06/binance-linked-bnb-price-falls-close-to-4-on-hack-rumors/ 的报道。
