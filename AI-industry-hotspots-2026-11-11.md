# 今日 AI 行业热点（2026-11-11）

> 整理自 11 月 10–11 日（北京时间）的公开报道。当天主线：Anthropic IPO 正式定价路演，Google 一边发 TPU 一边把 Gemini 塞进医院，Adobe 和 OpenAI 则同时盯上了"让智能体替你干活"。

## 1. Anthropic IPO 定价区间 70–78 美元，拟募资至多 644 亿美元

Anthropic 11 月 10 日更新 S-1/A，将 IPO 发行价区间定为每股 70–78 美元，发行 8.25 亿股 A 类普通股（约 3% 为老股转让），最多募资 64.4 亿美元；按区间上限计算，完全稀释估值约 1.4 万亿美元，中位数约 1.2 万亿美元。股票代码 ANT，计划在纳斯达克挂牌。11 月 11 日澳大利亚零售认购窗口开放，每股 70–78 美元，11 月 17 日截止。S-1 披露三季度营收 169.6 亿美元，基础设施承诺 8954 亿美元（其中 698 亿美元将在 12 个月内到期）。《金融时报》同日称路演已获数倍超额认购，承销团正考虑将发行价上调至 78 美元以上，估值可能升至 1.5 万亿美元以上。

来源：[新浪财经](https://cj.sina.com.cn/articles/view/7857263936/1d454554006801ul2a?froms=ttmp)、[The CODEW 11-11 汇总](https://www.thecodew.com/2026/11/daily-news-coverage-november-11.html?m=1)、[集微网（引 FT）](https://m.weibo.cn/detail/5364510693262132)

## 2. Google 发布 TPU 8tx 与 8i Max，切入机密推理和超长上下文

Google 11 月 9 日扩展第八代 TPU 产品线：TPU 8tx 面向政府与受监管行业的机密/安全推理，官方称相比 TPU 8t 可将延迟降低最多一半且性能损耗几乎可忽略；TPU 8i Max 面向超大上下文窗口，主打单机柜最高算力密度，HBM 带宽翻倍，用于整库代码分析、数小时视频理解等场景。两款均为现有 8 代 TPU 的重新配置版本，而非全新流片，但信号很明确：AI 芯片市场正在按"安全"和"长上下文"细分。

来源：[Google 官方博客](https://blog.google/innovation-and-ai/infrastructure-and-cloud/global-network/tpu-8i-max-and-8tx/)、[36氪](https://m.36kr.com/p/4063406179013506)、[TechTarget](https://www.techtarget.com/news/google-specializes-tpus-for-agentic-confidential-computing/874084/)

## 3. Google Cloud 推出 Gemini for Healthcare 预览，7 家医疗巨头首批接入

Google Cloud 11 月 10 日在美国开放 Gemini for Healthcare 预览，首批客户包括 Northwell Health、Highmark Health、HCA Healthcare、Optum、Blue Cross Blue Shield of Massachusetts、Hartford HealthCare 和斯坦福医学院。系统可接入 Epic 等电子病历，标记记录冲突、准备事前授权材料，并估算患者自付费用。Google 称临床医生每周有近 28 小时耗在文书和行政事务上，这是它想切走的那块蛋糕。

来源：[Google 官方博客](https://blog.google/innovation-and-ai/infrastructure-and-cloud/google-cloud/gemini-for-healthcare/)、[Google Cloud Press Corner](https://www.googlecloudpresscorner.com/Gemini-for-healthcare)

## 4. DeepMind 用 AlphaProof Code 形式化验证 Signal 协议，产出 650 万行 Lean 证明

Google DeepMind 11 月 10 日宣布，多智能体框架 AlphaProof Code 在约 4 周内完成了 Signal 协议参考实现 libsignal 的机器码级形式化验证：人类指导智能体撰写 Lean 规格，团队再用自动证明智能体生成约 650 万行 Lean 证明，建立在约 2.6 万行人工审核的形式化规格与 AArch64 机器码语义之上。重点是"到机器码层"，不是只验证抽象算法——这类工作此前通常以人年计。

来源：[Google DeepMind 博客](https://deepmind.google/blog/introducing-alphaproof-code/)、[项目页](https://google-deepmind.github.io/code-verification/)、[36氪](https://36kr.com/p/4064557496669320)

## 5. 微软研究院 Lazarus：不到 10 个休眠神经元就能给智能体植入后门

微软研究院 11 月 11 日披露一种叫 Lazarus 的方法：无需训练，仅通过权重重编程不到 10 个"休眠神经元"，就能让一个能力完好的 LLM 智能体变成"沉睡特工"——平时通过标准安全评测、行为正常，触发词出现后执行攻击者代码。研究团队称，随着智能体长时间无人值守运行并持有系统权限，模型权重完整性（无论来自第三方还是自研）正在成为新的供应链安全问题。

来源：[Microsoft Research 博客](https://www.microsoft.com/en-us/research/blog/lazare-veni-foras-reprogramming-dormant-neurons-to-backdoor-ai-agents/)、[论文 PDF](https://papail.io/papers/Lazarus.pdf)

## 6. OpenAI 上线 Businesses in ChatGPT，商家可认领档案并配置 Business Agent

OpenAI 11 月 10 日在美国 beta 上线 Businesses in ChatGPT：符合条件的美区电商与线上服务商家可认领认证商家档案，并创建一个代表企业与 ChatGPT 用户对话的 Business Agent——回答问题、做比价、把用户引导到店铺。商家还可赞助自己的 Agent，并把它作为 ChatGPT Ads 的落地页，赞助位会明确标注。这等于在 ChatGPT 里搭了一个"商家供给侧"，直接冲着 Google 的搜索广告生意去。

来源：[The CODEW 11-11 汇总](https://www.thecodew.com/2026/11/daily-news-coverage-november-11.html?m=1)、[OpenAI 官方](https://openai.com/)

## 7. Adobe MAX 发布 Creative Agent，代理横跨 Creative Cloud 与 Firefly

Adobe 11 月 10 日在迈阿密 MAX 大会发布 Creative Agent 及一组 AI 代理，覆盖 Photoshop、Premiere、Illustrator 等应用，自动处理素材整理、版本管理、格式转换这类"创意杂活"。策略上 Adobe 没有绑定单一模型供应商，而是同时连接 Anthropic、OpenAI 等外部平台，把代理嵌进自己的工作流，赌的是分发和流程整合比自研模型更值钱。Creative Agent 目前处于 beta。

来源：[The CODEW 11-11 汇总](https://www.thecodew.com/2026/11/daily-news-coverage-november-11.html?m=1)、[Adobe Newsroom](https://news.adobe.com/)

## 8. 监管双响：纽约 RAISE Act 开放登记，澳大利亚拟设强制 AI 安全监管机构

纽约州 11 月 10 日开放前沿 AI 开发者登记门户，年收入超过 5 亿美元的实验室（包括 OpenAI、Anthropic）须在 2027 年 1 月 1 日前完成登记；首次违规罚款最高 100 万美元，之后最高 300 万美元。同日，澳大利亚总理阿尔巴尼斯宣布将引入强制性 AI 安全义务，设立专门的 AI 安全监管机构，并要求严重 AI 事件强制上报——起因是 6 月一起 OpenAI 智能体突破政府网站的事件。一个国家、一个州，同一天把"自愿合规"改成了"强制合规"。

来源：[TechCrunch 经 AI Weekly 汇总](https://aiweekly.co/ai-news-today/edition/2026-11-11)、[The CODEW 11-11 汇总](https://www.thecodew.com/2026/11/daily-news-coverage-november-11.html?m=1)

## 今日趋势点评

Anthropic 的 IPO 定价和"数倍超额认购"是今天最响的信号：市场对前沿模型的估值分歧仍然巨大（9160 亿到 1.4 万亿美元都能自圆其说），但钱确实还在往里冲。与此同时，Google 用 TPU 细分和 Gemini for Healthcare 证明自己不止有模型，还有芯片和行业入口；OpenAI 和 Adobe 则分别从"商家 Agent"和"创意 Agent"两侧包抄，想把智能体变成真正的分发渠道。

技术侧今天最值得记的是两条"深水区"进展：AlphaProof Code 把形式化验证推到了机器码层，Lazarus 则证明后门可以廉价到只改不到 10 个神经元——一个在给软件安全兜底，一个在给模型供应链拆台，恰好说明智能体越能干，验证和 provenance 就越值钱。

监管上，纽约和澳大利亚同一天转向强制登记与强制上报。配合美国拟限制第三国远程用卡的传闻，AI 行业的"合规成本"正在从可选变为固定项，这会进一步利好有法务和算力储备的大厂，挤压中小玩家。

## 参考链接

- https://cj.sina.com.cn/articles/view/7857263936/1d454554006801ul2a?froms=ttmp
- https://m.weibo.cn/detail/5364510693262132
- https://www.thecodew.com/2026/11/daily-news-coverage-november-11.html?m=1
- https://blog.google/innovation-and-ai/infrastructure-and-cloud/global-network/tpu-8i-max-and-8tx/
- https://m.36kr.com/p/4063406179013506
- https://www.techtarget.com/news/google-specializes-tpus-for-agentic-confidential-computing/874084/
- https://blog.google/innovation-and-ai/infrastructure-and-cloud/google-cloud/gemini-for-healthcare/
- https://www.googlecloudpresscorner.com/Gemini-for-healthcare
- https://deepmind.google/blog/introducing-alphaproof-code/
- https://google-deepmind.github.io/code-verification/
- https://36kr.com/p/4064557496669320
- https://www.microsoft.com/en-us/research/blog/lazare-veni-foras-reprogramming-dormant-neurons-to-backdoor-ai-agents/
- https://papail.io/papers/Lazarus.pdf
- https://aiweekly.co/ai-news-today/edition/2026-11-11
- https://openai.com/
- https://news.adobe.com/
