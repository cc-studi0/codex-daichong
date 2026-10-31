# Codex 充值指南：国内给 ChatGPT 账号开通 Plus / Pro（2026）

> **利益相关声明**：本仓库由 [Plus宇宙](https://www.pluscosmo.com/)（ChatGPT 自有账号人民币充值服务）维护。本仓库与 OpenAI 没有隶属、授权或合作关系；ChatGPT、Codex 是 OpenAI 的商标。文中的官方规则都附了来源链接，**以 OpenAI 官方页面和你账号内显示为准**。
>
> 核验日期：2026-10-31 · 姊妹篇：[ChatGPT 充值 / 代充指南](https://github.com/cc-studi0/chatgpt-plus-recharge-guide)

搜「Codex 充值」「Codex 代充」的人，多半卡在两件事上：钱到底充到哪里，以及国内付款走不通。这份指南把这两件事讲清楚。

---

## 目录

1. [Codex 充值，充的是什么](#1-codex-充值充的是什么)
2. [三种「Codex 充值」不是一回事](#2-三种codex-充值不是一回事)
3. [各档位与 Codex 权益（官方口径）](#3-各档位与-codex-权益官方口径)
4. [用量机制：5 小时估算、每周上限与速度模式](#4-用量机制5-小时估算每周上限与速度模式)
5. [国内开通的三条路径](#5-国内开通的三条路径)
6. [代充流程：四步](#6-代充流程四步)
7. [避坑清单](#7-避坑清单)
8. [常见问题](#8-常见问题)
9. [更新日志](#9-更新日志)
10. [免责声明](#10-免责声明)

---

## 1. Codex 充值，充的是什么

Codex 没有单独的会员。用 ChatGPT 账号登录 Codex 时，用的是**该账号 ChatGPT 方案自带的用量**。官方写明 Codex 覆盖各个 ChatGPT 方案，**包括 Free 和 Go**，只是各方案的用量和可用功能不同（来源：[Using Codex with your ChatGPT plan](https://help.openai.com/en/articles/11369540-using-codex-with-your-chatgpt-plan)）。

所以「给 Codex 充值」通常是下面两件事之一：

- 给自己的 ChatGPT 账号**开通或升级**付费方案（Go / Plus / Pro），拿到更多用量和更多功能；
- 已经是 Plus / Pro，只是阶段性不够用 → 购买官方 **credits** 补量，不必换方案（来源：[Using Credits for Flexible Usage](https://help.openai.com/en/articles/12642688-using-credits-for-flexible-usage-in-chatgpt-personal-plans)）。

## 2. 三种「Codex 充值」不是一回事

| 你的情况 | 实际要办的事 | 正确入口 |
| --- | --- | --- |
| 想更顺畅地用 Codex，账号还是 Free / Go | 开通或升级 Plus / Pro | 本指南第 5–6 节 |
| 已是 Plus / Pro，只是某段时间不够用 | 官方 credits 补量 | ChatGPT「设置 → 用量」，或 Codex App「Usage & Billing」 |
| 用 API Key 调用 Codex / 模型 | API 平台余额 | [OpenAI 开发者平台](https://platform.openai.com/)，与 ChatGPT 账单完全分开 |

后两种情况，买会员解决不了：ChatGPT 订阅和 API 是两套独立账单（来源：[Managing billing for ChatGPT and the API platform](https://help.openai.com/en/articles/9039756-managing-billing-for-chatgpt-and-the-api-platform)）；ChatGPT 内的 credits 也**不是** API credits。

## 3. 各档位与 Codex 权益（官方口径）

| 档位 | 官方月费（美元） | Codex 相关权益（摘要） |
| --- | --- | --- |
| Free | $0 | 桌面 App 中以标准速度使用 GPT-6 Luna（逐步开放） |
| Go | $8（美国标价；部分地区为本地化定价） | 同上，定位“轻量编程任务”；不含 Codex Cloud |
| Plus | $20 | 网页、CLI、IDE 插件、iOS；自动代码审查、Slack 集成；可用 credits 补量 |
| Pro 100 / Pro 200 / Pro 500 | $100 / $200 / $500 | Plus 的全部权益加更高用量；**Ultrafast 只在 Pro 500 上有** |

来源：[Codex Pricing](https://learn.chatgpt.com/docs/pricing)、[About ChatGPT Pro tiers](https://help.openai.com/en/articles/9793128-about-chatgpt-pro-tiers)、[Introducing ChatGPT Go](https://openai.com/index/introducing-chatgpt-go/)（Go 的 $8 为美国标价，官方注明部分市场本地化定价）。

关于各 Pro 档位之间的用量差距：

- 官方只说明 **“Pro 200 的用量多于 Pro 100，Pro 500 是三档中最高的”**，没有给出相对 Plus 的固定倍数。本指南旧版写的“约 10x / 约 25x”**无法在官方页面核实，已删除**。
- 2026-10 官方更新：此前公告的 Pro 200 用量下调**已撤销**，Pro 200 重新开放新订阅；Pro 100 和 Pro 500 的 Work / Codex 用量翻倍；Plus 不变（来源：[About ChatGPT Pro tiers](https://help.openai.com/en/articles/9793128-about-chatgpt-pro-tiers)）。
- 第三方商品页上的“5X / 10X / 25X”之类命名属于商家标注，**不是官方倍数**，下单前请以官方说明和账号内用量页为准。
- Go、Plus、Pro 都**只能按月订阅**，官方不支持年付或预付多个月（来源：[What is ChatGPT Go?](https://help.openai.com/en/articles/11989085-what-is-chatgpt-go)）。

## 4. 用量机制：5 小时估算、每周上限与速度模式

以下内容整理自官方 [Codex Pricing](https://learn.chatgpt.com/docs/pricing)：

- **Plus**：官方给的是“每 5 小时本地消息数”的**估算区间**，不是固定上限，例如 GPT-6.1 Sol 为 15–160 条、GPT-6 Luna 为 350–3,000 条。差距大，是因为消耗取决于模型、上下文、推理、工具调用和缓存，而不是你发了几句话。
- **Pro**：官方写明 **Pro 目前没有 5 小时限制**（以后可能变）。
- **每周上限**：官方写明“可能还有每周上限”（Weekly limits may also apply），具体以账号内用量页为准。
- **速度模式**：相对同模型的标准模式，Fast 消耗会员自带用量 2.5 倍、消耗 credits 2 倍；Ultrafast（GPT-6 Astra / GPT-6.1 Sol，仅 Pro 500）消耗自带用量 8 倍、credits 6 倍。
- **共用额度**：本地消息和云端任务共用额度，Codex 与 ChatGPT Work 也共用同一份额度。
- 查看剩余额度：CLI 里输入 `/status`，或打开用量页面。官方客服**不会**手动重置用量。

触限时，先看是哪一层（5 小时 / 每周）受限，再决定是等待重置、买 credits，还是升档。同一层受限反复出现，才说明需要升档。更细的记录方法见 [Codex 额度说明](https://www.pluscosmo.com/blog/codex-usage-limits-reset-guide)。

## 5. 国内开通的三条路径

| 路径 | 能否用微信 / 支付宝 | 主要卡点 |
| --- | --- | --- |
| 官网直接订阅 | 否，通常需要国际卡 | 国内发卡常被拒；官方[支持地区列表](https://help.openai.com/en/articles/7947663-chatgpt-supported-countries)不含中国大陆与中国香港，在不支持地区使用可能导致账号被限制 |
| App Store 内购 / 礼品卡 | 视 Apple ID 区服与余额来源而定 | 需要外区账号；礼品卡来源有风险；取消和退款都找 Apple |
| 第三方代充 | 是 | 渠道质量参差不齐：要密码、私下转账、售后找不到人 |

三条路径对应的都是同一个 ChatGPT 方案，Codex 的权益只由**账号的官方档位**决定，与你从哪条路付款无关。三条路径的详细对比见姊妹篇 [ChatGPT 充值 / 代充指南](https://github.com/cc-studi0/chatgpt-plus-recharge-guide#2-三条实际路径对比官网--app-store礼品卡--代充)。

## 6. 代充流程：四步

以本仓库维护方的流程为例（其他平台的流程大同小异；逐步截图见 [充值教程](https://www.pluscosmo.com/guide)）：

1. **选档**：在[套餐页](https://www.pluscosmo.com/shop)核对档位、周期和当日价格。账号里已有订阅（官网 / Apple / Google Play）的，先确认归属和到期日，避免两份订阅同时计费。
2. **提交 Session**：登录自己的 ChatGPT 账号，按结算页说明获取临时会话凭据（Session），只填在平台自己的 HTTPS 订单页。全程不需要密码、验证码和恢复码。
   > Session 在有效期内可能具有账号访问权限，只填在平台自己的订单页，不要发到聊天窗口。完成后可在 ChatGPT 设置中退出所有设备，使该 Session 失效。
3. **付款**：用微信或支付宝在**平台生成的订单里**付款，保留订单号。不要按私聊要求转账到个人账户。
4. **验收**：用同一个账号登录官方 ChatGPT，在「设置 → 账户」核对方案名称和有效期，再到 Codex 里确认同一个账号已生效。**只认账号内显示，不凭订单状态判断。** 处理时效以订单页说明为准。

## 7. 避坑清单

- ❌ 要账号密码、短信 / 邮箱验证码、2FA 恢复码的“代充”→ 直接放弃。
- ❌ 只收 Session，但没有订单号、查不到进度 → 谨慎。
- ❌ 要求转账到个人账户、绕过站内订单的“内部渠道”→ 不要付。
- ❌ 会员还在有效期内，又重复购买同档订阅 → 可能被两处同时计费。
- ❌ 为了 API 额度去买会员 → 两套账单，互不抵扣。
- ❌ 承诺“必不封号”“永久可用”“官方渠道”→ 当作营销话术，不要当成保证。
- ✅ 验收只在官方账号内做；售后时保留订单号和脱敏截图。

## 8. 常见问题

**Q：Codex 充值和 ChatGPT Plus 充值是同一件事吗？**
对用 ChatGPT 账号登录 Codex 的人来说，基本是同一件事：Codex 用量跟着 ChatGPT 方案走。例外是用 API Key 的人，那属于 API 账单。

**Q：Free 能不能用 Codex？**
可以，官方写明 Codex 覆盖 Free 和 Go，但用量和功能有限，Codex Cloud 不含在 Free / Go 里（来源：[Using Codex with your ChatGPT plan](https://help.openai.com/en/articles/11369540-using-codex-with-your-chatgpt-plan)）。

**Q：Plus 不够用，一定要升 Pro 吗？**
不一定。Plus / Pro 触限后可以直接买 credits，不用换方案。只有同一层限制长期影响交付时，再考虑升档。

**Q：代充会不会封号？**
没有人能替官方保证不封号。只选订单可查、不碰密码的渠道，并遵守官方条款和支持地区规则；凡是承诺“零风险”的，反而要警惕。

**Q：会员开着，API 还是报余额不足？**
正常。会员和 API 是两套独立计费，需要到开发者平台单独充值。

## 9. 更新日志

| 日期 | 变更 |
| --- | --- |
| 2026-10-31 | 加入利益相关声明；档位表按官方页面重写（Go $8 美国标价、Pro 三档 $100 / $200 / $500）；删除无法核实的“约 10x / 约 25x”倍数，补充 Pro 200 下调已撤销的官方说明；更正“Free 不能用 Codex”的暗示；用量机制改为官方原文口径（Plus 5 小时估算、Pro 当前无 5 小时限制、可能有每周上限、速度模式倍率）；新增 credits 补量路径、目录、免责声明；互链姊妹仓库。 |
| 2026-10-16 | 首版。 |

发现过时信息，欢迎提 Issue 并附上官方链接。

## 10. 免责声明

- 本文只整理公开信息和常见操作路径，不构成购买建议。价格、方案、可购地区与规则可能随时变化，**以 OpenAI 官方页面和你的账号内显示为准**。
- 第三方充值平台（包括本仓库维护方）不是 OpenAI 的官方渠道，OpenAI 不为任何第三方背书。使用前请自行评估风险，并遵守 [OpenAI 使用条款](https://openai.com/policies/terms-of-use)和所在地法律法规。
- 本仓库采用 [MIT](LICENSE) 许可，转载请注明出处。
