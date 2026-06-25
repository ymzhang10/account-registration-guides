---
title: ChatGPT 账号注册教程
created: 2026-05-21
updated: 2026-05-22
type: tutorial
status: draft
owner: human
author: ymzhang
tags:
  - ChatGPT
  - OpenAI
  - Codex
  - OAuth
  - 账号注册
  - 教程
---

# ChatGPT 账号注册教程

> 作者：ymzhang
> 来源：由 `50-Content/草稿/2026-05-16 ChatGPT Plus 安全订阅文案/X - ChatGPT 账号注册.md` 教程化整理。
> 适用对象：中国大陆用户，想用自己长期可控的邮箱和账号体系注册 ChatGPT，而不是购买成品号、共享号或接码号。
> 核心原则：**账号先稳，订阅才稳。不要买号，不要共享号，不要接码号。**

## 核对评估结论

原 X 长帖的主判断是对的：**不要买成品号、共享号、接码号、代充号、所谓永久会员号。**

需要根据 OpenAI 当前官方说明修正的地方：

1. ChatGPT 新账号创建和日常使用现在不再默认要求手机号验证。普通 ChatGPT 用户可以用长期可控邮箱或社交登录注册；但如果后续要把账号授权给 Codex / 第三方 Agent，并准备用英国 Giffgaff 号码承接验证，应优先使用手机号注册，再绑定邮箱。
2. OpenAI 当前支持地区列表里没有中国大陆。官方说明也提示，从未支持的国家或地区访问或提供访问，可能导致账号被封禁或暂停。注册和使用前应确认自己所在地、网络环境、付款方式符合 OpenAI 当前支持范围。
3. 实操重点发现：虽然 ChatGPT 注册、网页版登录、App 登录和日常使用不再默认要求手机号，但当账号通过 OAuth 授权给 Codex 或第三方 Agent 使用时，仍可能强制弹出电话号码验证，而且无法跳过。
4. Giffgaff 实操重点：如果账号已经用邮箱注册完成，再想后补绑定 Giffgaff 电话号码，实操中无法正常添加。更稳路径是从一开始选择手机号注册，用 Giffgaff 完成账号创建，注册成功后再绑定邮箱。
5. 如果确实遇到手机号验证，OpenAI 官方说明只支持短信，部分地区支持 WhatsApp；不支持座机、VoIP、Google Voice、高价号码等号码类型。
6. 登录方式很重要：如果注册时选择 `Continue with Google` / `Continue with Apple` / `Continue with Microsoft`，后续通常要继续用同一种方式登录。乱切登录方式容易出现 `Wrong authentication method` 或“邮箱已存在”类问题。
7. OpenAI 现在支持符合条件的账号在网页端修改邮箱；Phone only 账号也可以在网页端 `Settings -> Account -> Email -> Add` 添加邮箱。社交登录账号可能需要先添加密码；企业、SSO、工作区账号有额外限制。

## 不推荐的账号来源

不要为了省事购买：

- 成品号。
- 共享号。
- 接码注册号。
- 代充号。
- 永久会员号。
- 多人共用的 Plus / Pro 账号。

这些账号后续常见风险：

- 登录异常。
- 安全验证过不去。
- 邮箱或手机号不受自己控制。
- 被原卖家找回。
- 多人共用导致封控。
- 订阅、退款、发票和账单纠纷。
- 账号历史记录、记忆、文件和隐私不可控。

## 已有账号怎么处理

如果已有 ChatGPT 账号还能正常登录，优先继续使用自己的老账号。

先确认三件事：

1. 登录邮箱或社交账号是否长期可控。
2. 是否能收到 OpenAI 的验证邮件。
3. 当前登录方式是什么。

登录方式要记清楚：

| 注册时使用 | 后续应如何登录 |
|---|---|
| 邮箱 + 密码 | 用同一邮箱和密码登录 |
| Continue with Google | 继续用 Google 登录 |
| Continue with Apple | 继续用 Apple 登录 |
| Continue with Microsoft | 继续用 Microsoft 登录 |

如果你当初用 Apple 登录并开启了 Hide My Email，账号可能绑定的是 `@privaterelay.appleid.com` 中转邮箱，不一定是你的真实邮箱。一定要记录清楚。

## 什么时候考虑重新注册

如果旧号已经出现这些问题，可以考虑重新注册一个自己完全可控的新账号：

- 已经无法访问原邮箱。
- 忘记当初用的是哪种登录方式。
- 登录时一直提示错误登录方式。
- 账号是买来的或别人代注册的。
- 账号绑定的手机号、邮箱、订阅方式都不受自己控制。
- 长期反复安全验证，且无法稳定恢复。

注意：重新注册前，如果旧号有 Plus / Pro 订阅，要先处理订阅取消或账单问题。不要在多个账号上重复订阅。

## 准备清单

| 项目 | 建议 |
|---|---|
| 网络和地区 | 确认处于 OpenAI 支持的国家或地区，并使用稳定网络 |
| 邮箱 | 推荐长期可控 Gmail 或其他长期邮箱 |
| 登录方式 | 日常 ChatGPT 用户可用邮箱或社交登录；Codex / Agent 用户如使用 Giffgaff，优先手机号注册 |
| 密码 | 使用密码管理器生成强密码 |
| 手机号 | ChatGPT 日常使用当前不默认要求；但 Codex / 第三方 Agent OAuth、API 或安全验证场景可能强制要求。若使用 Giffgaff，应在注册阶段用手机号创建账号 |
| 设备 | 建议先用电脑浏览器注册，再登录手机 App |

关于 Gmail `+` 别名：

- 可以用于区分不同注册用途，例如 `name+chatgpt@gmail.com`。
- 主力长期账号更建议使用独立、清晰、长期维护的邮箱地址。
- 不要用会失效的临时邮箱。

## 推荐注册路径

先按账号用途选择路线：

| 用途 | 推荐注册方式 |
|---|---|
| 只用于 ChatGPT 网页 / App 日常聊天 | 邮箱 + 密码，或 Google / Apple / Microsoft 社交登录 |
| 后续要用于 Codex / 第三方 Agent OAuth，且准备用英国 Giffgaff 号码 | 手机号注册优先，注册成功后再绑定邮箱 |
| 需要 API 首次 key 生成 | 提前准备长期可控手机号，因为 API 首次 key 生成仍需要电话验证 |

### 路线 A：邮箱或社交登录注册

适合只用于 ChatGPT 网页版、官方 App 和普通 Plus 订阅的用户。

1. 确认自己位于 OpenAI 当前支持的国家或地区。
2. 打开 `https://chatgpt.com/`。
3. 点击 `Sign up` / 注册。
4. 选择一种注册方式：
   - 邮箱 + 密码。
   - Continue with Google。
   - Continue with Microsoft。
   - Continue with Apple。
5. 如果使用邮箱注册，按提示完成邮箱验证。
6. 如果页面要求补充信息，按页面提示完成。
7. 注册完成后，进入 ChatGPT 首页。
8. 到设置中检查账号邮箱、登录方式和安全设置。

只用于日常 ChatGPT 的主力账号，可以优先使用“邮箱 + 密码”或自己的 Google 账号。不要用公司邮箱、临时邮箱、一次性邮箱或别人可管理的邮箱。

### 路线 B：Giffgaff 手机号注册，再绑定邮箱

适合这种情况：你明确要把账号用于 Codex、编程 Agent、自动化工具或第三方客户端 OAuth 授权，并准备用英国 Giffgaff 号码处理电话验证。

关键结论：

**不要先用邮箱注册完账号，再尝试后补绑定 Giffgaff 号码。实操中，这条路无法正常完成电话号码绑定。**

推荐流程：

1. 准备一张长期可控的英国 Giffgaff SIM / eSIM。
2. 确认 Giffgaff 可以正常接收短信。
3. 打开 `https://chatgpt.com/`。
4. 注册时选择手机号注册入口，而不是邮箱注册入口。
5. 国家/地区选择英国，输入 Giffgaff 手机号码。
6. 接收并输入短信验证码。
7. 完成 ChatGPT 账号创建。
8. 登录 ChatGPT 网页版。
9. 进入 `Settings -> Account -> Email -> Add`。
10. 绑定自己的长期邮箱，例如 Gmail。
11. 保存好手机号、邮箱、登录方式和恢复方式。

注意：

- OpenAI 的 phone only signups 仍属于逐步 rollout / beta 机制，入口可能按地区、账号状态和页面实验变化。
- OpenAI 的 phone-only signups 页面目前把英国列入 mostly rolled out 地区；但另一个电话号码说明页仍把美国和印度描述为主 rollout，其他国家可能是 limited experimental option。所以英国 / Giffgaff 路径要以当前页面实际入口为准，不保证每个账号都稳定出现。
- OpenAI 官方说明，不支持更改或更新账号关联手机号。所以一开始就要使用自己长期可控的号码。
- 手机号注册后再添加邮箱，比邮箱注册后再补 Giffgaff 电话号码更稳。

## 如果页面要求手机号验证

OpenAI 当前说明：ChatGPT 新账号创建和日常使用不再默认需要手机号验证。但如果你在特定流程中仍然遇到手机号验证，按下面原则处理：

1. 使用自己长期可控的移动手机号。
2. 能长期接收短信，后续可能还会用到。
3. 如果所在地区支持 WhatsApp 验证，可以按页面提示选择 WhatsApp。
4. 不使用接码平台、临时手机号、座机、VoIP、Google Voice 或来源不明虚拟号。

可以考虑长期可控的境外移动运营商 SIM / eSIM，但重点不是“境外”，而是：**号码必须长期属于你，能持续接收验证。**

如果你使用的是英国 Giffgaff 号码，并且账号未来要用于 Codex / 第三方 Agent 授权，不要把手机号验证当成“注册后随时能补”的步骤。实操更稳的是：注册阶段直接用 Giffgaff 手机号创建账号，之后再绑定邮箱。

## Codex / 第三方 Agent 授权的特殊情况

这是实操中需要单独记住的重点：

**ChatGPT 注册、网页版登录、App 登录和日常聊天使用，不代表账号已经满足 Codex 或第三方 Agent 的 OAuth 授权要求。**

在把 ChatGPT / OpenAI 账号通过 OAuth 授权给 Codex、编程 Agent、自动化工具或第三方客户端时，即使这个账号平时可以正常登录 ChatGPT，也可能再次弹出电话号码验证。

这个验证的特点：

- 通常出现在 OAuth 授权流程中。
- 和普通 ChatGPT 网页/App 登录不是同一个体验。
- 可能要求绑定或验证手机号。
- 页面可能不给“跳过”选项。
- 如果没有长期可控手机号，授权流程会卡住。

所以，如果这个账号后续准备用于 Codex 或第三方 Agent，不能只看“能不能登录 ChatGPT”。还要提前准备一个长期可控、能接短信的移动手机号。

如果使用英国 Giffgaff 号码，要特别注意：

- 已经用邮箱注册完成的 ChatGPT 账号，实操中无法再顺利添加 Giffgaff 电话号码绑定。
- 如果目标是 Codex / 第三方 Agent OAuth 授权，建议直接重新走“手机号注册 -> 绑定邮箱”的路径。
- 不要把一个已经注册好的邮箱账号当成最终账号投入订阅、记忆、文件和长期工作流后，才发现 OAuth 授权卡在电话号码验证。

不建议：

- 用接码平台临时过一次。
- 用别人手机号。
- 用无法长期接收短信的临时 SIM。
- 用 Google Voice、VoIP、座机或来源不明虚拟号。

推荐判断标准：

1. 这个号码属于自己。
2. 后续半年到一年还能接短信。
3. 不依赖卖家、代收或一次性接码平台。
4. 绑定后能承受后续再次验证。

## 注册后安全设置

注册完成后，建议立刻做这些事：

1. 保存登录邮箱、注册方式和密码。
2. 打开 ChatGPT 设置。
3. 进入 `Security` / 安全。
4. 开启 MFA / 多因素认证。
5. 有条件的话添加 Passkey。
6. 确认邮箱能收到 OpenAI 登录、验证和账单邮件。
7. 不要把账号密码给任何代充、代订阅、共享平台。

MFA 开启后，会在登录时增加第二步验证。OpenAI 官方说明，MFA 会应用到 ChatGPT、API Platform 等 OpenAI 服务。

## 手机 App 登录

网页注册完成后，再登录手机端：

1. 从官方 App Store / Google Play 下载 `ChatGPT` App。
2. 打开 App。
3. 使用和网页注册时相同的登录方式。
4. 如果是 Google / Apple / Microsoft 注册，不要改用邮箱密码登录。
5. 确认聊天记录、设置和账号状态正常同步。

## 常见问题

### 1. 提示 `Wrong authentication method`

通常是登录方式用错了。

例如你当初用 Google 注册，就继续点 `Continue with Google`，不要改用邮箱密码登录。

### 2. 提示 `There is already a user with email`

可能是这个邮箱已经通过另一种方式注册过。先尝试：

- 邮箱 + 密码。
- Continue with Google。
- Continue with Microsoft。
- Continue with Apple。

用无痕窗口测试会更干净。

### 3. 收不到验证邮件

处理方法：

- 检查垃圾邮件。
- 搜索 OpenAI、ChatGPT、noreply 等关键词。
- 换无痕窗口重新登录。
- 确认邮箱没有被公司或学校网关拦截。
- 不要用临时邮箱。

### 4. 一直卡在浏览器验证或 Cloudflare

可以尝试：

- 清理浏览器缓存和 Cookie。
- 用无痕窗口。
- 换浏览器。
- 暂停广告拦截、脚本拦截、隐私插件。
- 换一个稳定网络。
- 不要短时间内频繁刷新和重试。

### 5. 账号能登录，但想换邮箱

OpenAI 当前支持符合条件的个人账号在 ChatGPT 网页端修改邮箱：

1. 登录 ChatGPT 网页版。
2. 进入 `Settings`。
3. 选择 `Account`。
4. 点击邮箱地址。
5. 输入新邮箱并完成验证。

如果是 Google / Apple / Microsoft 社交登录账号，可能需要先给账号添加密码，再修改邮箱。企业、SSO 或工作区账号可能不能自助修改。

### 6. 旧号不能登录，但还有 Plus 订阅

如果无法登录旧号，但旧号仍在扣费，应先处理订阅取消或账单支持，再决定是否新注册。

如果是 Apple App Store 订阅，去 Apple 订阅管理里取消；如果是网页订阅，则走 ChatGPT / OpenAI 账单支持。

## 最小成功检查表

- [ ] 使用的是自己长期可控邮箱。
- [ ] 如果账号要给 Codex / 第三方 Agent 使用，已准备长期可控手机号。
- [ ] 如果使用 Giffgaff，已用手机号注册账号，而不是邮箱注册后再补绑电话。
- [ ] 记录了注册方式：邮箱密码 / Google / Apple / Microsoft。
- [ ] 能收到 OpenAI 验证邮件。
- [ ] 能正常登录 `chatgpt.com`。
- [ ] 手机 App 能用同一方式登录。
- [ ] 已开启 MFA 或 Passkey。
- [ ] 没有购买成品号、共享号、接码号。
- [ ] 如果后续要订阅 Plus，确认订阅账号就是这个主力账号。

## 官方参考

- [ChatGPT Supported Countries](https://help.openai.com/en/articles/7947663-chatgpt-supported-countries)
- [ChatGPT and API services in unsupported countries and territories](https://help.openai.com/en/articles/9131992-chatgpt-and-api-services-in-unsupported-countries-and-territories)
- [What does phone verification look like?](https://help.openai.com/en/articles/8983040)
- [Phone only signups](https://help.openai.com/en/articles/10388702-phone-only-signups-for-the-us-and-india-beta)
- [How to change the phone number associated with your account](https://help.openai.com/en/articles/9135134-how-to-change-the-phone-number-associated-with-your-account)
- [Can I phone verify over email/call instead of SMS?](https://help.openai.com/en/articles/8983027)
- [Can I use a premium number, landline, Google Voice, or other VoIP phone number?](https://help.openai.com/en/articles/8983024-can-i-use-a-premium-number-landline-google-voice-or-other-voip-phone-number)
- [Why can't I log in to ChatGPT?](https://help.openai.com/en/articles/7426629-why-cant-i-log-in-to-chatgpt)
- [How to change your email address](https://help.openai.com/en/articles/4936827-how-to-change-your-email-address)
- [Enabling or disabling multi-factor authentication MFA](https://help.openai.com/en/articles/7967234-enabling-or-disabling-multi-factor-authentication-mfa)

## 相关笔记

- [[40-Resources/教程/账号申请类/用美区Apple余额订阅ChatGPT Plus教程|用美区Apple余额订阅ChatGPT Plus教程]]
