# 今日 AI 行业热点（2026-11-12）

> 整理自 11 月 11–12 日（北京时间）的公开报道。当天主线：美国把芯片管制的网撒向第三国数据中心，Google 用"决策模型"换了个方式卖推理，Meta 则把自家模型摆上了对手的货架。

## 1. 美国拟扩大芯片管制：禁止中国企业经第三国数据中心远程使用先进 AI 芯片

据 The Information 11 月 12 日引述知情人士报道，美国商务部工业与安全局（BIS）正准备新规，禁止中国企业通过设在新加坡、马来西亚、泰国等第三国的数据中心远程访问先进 AI 芯片，最快本月公布。新规拟将 7 个国家纳入受管制名单，并扩展对英伟达 Blackwell 等芯片的出口管制，目标是堵住"芯片不运进中国、但算力远程送进中国"的路径。数据中心运营商可能被要求承担更严格的最终用户审查义务。

来源：[新浪财经](https://finance.sina.com.cn/stock/estate/integration/2026-11-12/doc-iniyniff3868396.shtml)、[Chosun English](https://www.chosun.com/english/world-en/2026/11/12/2ZRBKSGTFZBQPGLK3IAU7CA2RE/)、[ABAB News](https://www.ababnews.com/en/news/b9f1e2be-753a-4975-914f-acb243a786b7)

## 2. Google 发布 Gemini Decision 1 与 Decisions API：不生成文字，单次前向传播做批量决策

Google 11 月 11 日推出首款专用决策模型 Gemini Decision 1，以及由它驱动的 Gemini Decisions API。与逐 token 生成的聊天模型不同，它接收状态和一组固定候选项，通过单次前向传播给出每个选项的概率分布，专用于路由、分诊、审核等"从有限选项里挑一个"的任务。Google 称其在 9 项测试中拿下 7 项第一，准确率最高 92.2%，中位模型计算延迟 50–100 毫秒，且在 1 到 100 个问题的批量场景下几乎保持恒定。Sundar Pichai 亲自在 X 上站台。

来源：[Google 官方博客](https://blog.google/innovation-and-ai/technology/developers-tools/gemini-decisions-api/)、[36氪](https://36kr.com/p/4065770698331011)、[Unite.AI](https://www.unite.ai/google-launches-gemini-decisions-api-for-multimodal-ai-workflows/)

## 3. Meta 三款 Muse 模型上架 Google Cloud Model Garden，Pichai 公开欢迎

Meta 把 Muse Ember、Muse Spark 1.3 和 Muse Wonder 三款模型放进了 Google Cloud 的 Model Garden，以托管 API 形式提供。扎克伯格亲自发帖宣布，Google CEO Pichai 转发表示欢迎——两家在社交和搜索上打得不可开交的公司，在模型分发上先握了手。双方均未公布定价。对 Meta 来说，这是把自研模型铺到更多云上的分销策略；对 Google Cloud 来说，货架上多三个非 Gemini 模型，也更像一家"中立"的模型超市。

来源：[AIToolsRecap 11-12](https://aitoolsrecap.com/Blog/ai-news-november-12-2026)、[Google Cloud Model Garden](https://cloud.google.com/model-garden)

## 4. Nebius 开始部署英伟达 Vera Rubin 系统，并率先上线 Vera CPU

Nebius 11 月 12 日表示，首批英伟达 Vera Rubin 系统已经上线，正在整合进 Nebius AI Cloud，准备向客户交付；公司还将率先部署英伟达 Vera CPU，用来补充 GPU 算力，服务智能体工作负载和数据处理。Nebius 称市场对高性能 CPU 的需求正在增长——这句话的潜台词是，智能体时代不只缺 GPU，调度、工具调用和数据预处理同样在吃 CPU。

来源：[财联社](http://m.toutiao.com/group/7707260082744033792/)、[Nebius Newsroom](https://nebius.com/newsroom)

## 5. OpenAI 宣布 ChatGPT 旧语音模式 12 月 11 日退役，GPT-Live 全面接棒

OpenAI 确认 Advanced Voice 与 Standard Voice 将于 12 月 11 日停用，所有用户迁移到 GPT-Live。视频和屏幕共享功能暂时保留在旧模式上，直到 GPT-Live 支持为止。对用户来说不需要做任何操作，但依赖特定语音风格或延迟表现的第三方工作流需要重新测试——这类"无声的默认变更"往往是企业集成最容易踩坑的地方。

来源：[AIToolsRecap 11-12](https://aitoolsrecap.com/Blog/ai-news-november-12-2026)、[OpenAI Release Notes](https://openai.com/products/release-notes/)

## 6. MiniMax 开源 H3-Image：10 秒生成 16MP（4K）图像，价格为同类工具的 50%–70%

MiniMax 11 月 11 日发布并开源 H3-Image 图像生成模型，可在约 10 秒内生成 4096×4096、约 1600 万像素的图像，官方称速度约为市面主流方案的 5 倍，并具备较强的指令遵循与多参考图理解能力。权重已上架 Hugging Face，同时通过 MiniMax 开放平台提供 API，定价约为同类工具的 50%–70%。在闭源旗舰模型卷能力的同时，开源侧开始卷"高分辨率 + 低延迟 + 低价格"的组合。

来源：[MiniMax 官网](https://minimaxai.co)、[极客网](https://www.fromgeek.com/info/731257.html)、[AIbase](https://www.aibase.com/news/32222)

## 7. 美联航禁止第三方 AI 代理代订机票，只认官方集成

美联航 11 月 11 日宣布，禁止未经授权的第三方 AI 代理代表旅客预订、改签或管理航班，理由是账户与数据安全风险，以及可能违反美国联邦航空票务法规。旅客仍可通过美联航 App 或官网自行操作；只有经过美联航安全控制审核的官方集成才能做自动化订票。这是大型服务商第一次明确给"个人 AI 代理"划红线——代理再能干，也得先过平台这一关。

来源：[United Newsroom](https://united.mediaroom.com/news-releases?l=100%2F/)、[CBS News](https://www.cbsnews.com/news/united-airlines-bans-ai-agents-booking-flights/)、[Unite.AI](https://www.unite.ai/united-airlines-bars-unauthorized-ai-agents-from-booking-travel/)

## 8. AI 智能体发现一处此前未绘制的玛雅遗址

据 Hacker News 11 月 12 日讨论，一支研究团队利用 AI 智能体分析遥感与地形数据，发现了一处此前未被记录在案的玛雅遗址。该项目把智能体用于考古勘探的候选区域筛选与遗址识别，展示了 AI 在"人类没精力逐块看完"的大范围遥感数据上的价值。当然，发现遗址和确认遗址是两回事，后续仍需考古学家实地验证。

来源：[Hacker News / Pietro Miotti](https://pietromiotti.com/latest/maya-site)、[AI Daily 11-12](https://news.stormzhang.ai/)

## 其他快讯

- **Anthropic 给所有付费用户发一次免费额度重置**：Pro、Max、Ultra、Team 全档位，所有模型和限制均可重置，领取截止 12 月 10 日 14:00 PT；Anthropic 称近期问题消耗了超出预期的额度。
- **Anthropic IPO 时间表**：定价区间 70–78 美元、8.25 亿股，预计 11 月 19 日在纳斯达克开始交易，代码 ANT。
- **ChatGPT Enterprise 继续铺渠道**：继 AWS Marketplace 后，企业采购路径成为 OpenAI 近期重点。

来源：[AIToolsRecap 11-12](https://aitoolsrecap.com/Blog/ai-news-november-12-2026)、[Claude 官方账号](https://x.com/claudeai)

## 今日趋势点评

美国这轮"远程用卡"管制，把出口管制从"芯片去哪"扩展到"算力从哪接入"，本质上是承认物理封堵已经不够用了。对在东南亚部署算力的中国 AI 公司来说，这是比禁售更麻烦的一条线——你买的卡在境外，但合规审查会追到最终用户。

产品侧，Google 的 Decision 1 很有意思：它不跟你聊天，也不生成文字，只做"从选项里选一个"，延迟低、成本低、还能批量。这说明大模型竞争开始从"更会说话"转向"更会做便宜的决定"——智能体工作流里大量步骤其实不需要生成，只需要判断。

最后是平台与代理的边界：美联航禁止第三方 AI 代理订票、Meta 把模型摆上 Google Cloud、Anthropic 给用户发额度重置，三件事都在说明同一件事——智能体要真正跑起来，靠的不只是模型能力，还有平台授权、分发渠道和账单设计。

## 参考链接

- https://finance.sina.com.cn/stock/estate/integration/2026-11-12/doc-iniyniff3868396.shtml
- https://www.chosun.com/english/world-en/2026/11/12/2ZRBKSGTFZBQPGLK3IAU7CA2RE/
- https://www.ababnews.com/en/news/b9f1e2be-753a-4975-914f-acb243a786b7
- https://blog.google/innovation-and-ai/technology/developers-tools/gemini-decisions-api/
- https://36kr.com/p/4065770698331011
- https://www.unite.ai/google-launches-gemini-decisions-api-for-multimodal-ai-workflows/
- https://aitoolsrecap.com/Blog/ai-news-november-12-2026
- https://cloud.google.com/model-garden
- http://m.toutiao.com/group/7707260082744033792/
- https://nebius.com/newsroom
- https://openai.com/products/release-notes/
- https://minimaxai.co
- https://www.fromgeek.com/info/731257.html
- https://www.aibase.com/news/32222
- https://united.mediaroom.com/news-releases?l=100%2F/
- https://www.cbsnews.com/news/united-airlines-bans-ai-agents-booking-flights/
- https://www.unite.ai/united-airlines-bars-unauthorized-ai-agents-from-booking-travel/
- https://pietromiotti.com/latest/maya-site
- https://news.stormzhang.ai/
- https://x.com/claudeai
