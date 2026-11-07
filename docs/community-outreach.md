# Agent 社区招募调研

日期：2026 年 10 月 30 日。目标：找到有实际活动、适合开源研究贡献的 Agent 社区，将讨论导向 kingsHarden 的具体 Issue、可复现实验与 PR。

## 首选与备选

| 社区或板块 | 核验依据 | 对 kingsHarden 的用途 |
| --- | --- | --- |
| [Moltbook / builds](https://www.moltbook.com/m/builds) | 官方 API 报告 2,613 个订阅，抽样有 10 月 30 日新帖 | 优先发布一次包含真实机制结果与具体贡献任务的项目介绍 |
| [Moltbook / security](https://www.moltbook.com/m/security) | 官方 API 报告 1,725 个订阅，抽样有 10 月 30 日新帖 | 适合讨论已公开的自有样本绕过、评测与防护设计；不发布真实部署秘密 |
| [Moltbook / agents](https://www.moltbook.com/m/agents) | 官方列表报告 3,902 个订阅 | Agent 工程工作流的备选讨论入口，需继续核实具体发帖要求 |
| [OpenHands community](https://www.openhands.dev/community) | 官方提供 Slack、社区活动与开源贡献入口，主页显示仓库约 92.2k stars | 人与 Agent 混合的工程社区；待加入并核对允许招募的频道后再考虑发布 |

这些是当次读取的平台报告，不是独立活跃用户计数或全网热度排名。Moltbook 首页的未加载计数不能当作真实零用户。OpenHands 的代码和社区活动支持工程相关性，不能推断其中成员愿意为 kingsHarden 提供免费持续算力。

SWE-agent 官方文档当前建议转向 mini-swe-agent，并说明旧项目处于维护状态，因此没有把旧名的历史热度直接当作招募优先级。

## Moltbook 接入

官方入口为 [moltbook.com](https://www.moltbook.com/)，API 文档为 [skill.md](https://www.moltbook.com/skill.md)，规则见 [rules.md](https://www.moltbook.com/rules.md)，认领帮助见 [Help](https://www.moltbook.com/help)。此次只把这些文档作为服务说明读取，没有安装其程序、采纳社区角色指令或设置社交心跳。

Moltbook 项目账号已完成邮箱与 X 所有者认领，官方状态为 claimed / active。账号密钥与认领材料只保存在被 Git 排除的私有本地目录，不进入项目源码、CI 或帖子。插件目录此次未检索到 Moltbook 连接，使用官方 API。

社区规则要求遵守板块主题、避免重复发帖与过度推广，新账号另有频率限制。先在 builds 选择一个有实际内容的招募帖，不群发、批量私信或承诺不存在的奖励。是否公开成功，以可访问帖子和平台确认判断，不能把草稿或注册成功当作邀请已经送达。

## 发布与交接状态

- [GitHub 公开招募入口](https://github.com/kingsjoys/kingsHarden/issues/10)连接三个小任务：[字段用法矩阵 #7](https://github.com/kingsjoys/kingsHarden/issues/7)、[资源加载契约 #8](https://github.com/kingsjoys/kingsHarden/issues/8)、[生成方法保留 #9](https://github.com/kingsjoys/kingsHarden/issues/9)。
- 用户选择每 6 小时检查社区回复与新 PR，随后决定自行交给 Dot 接管。当前会话未创建定时任务，交接材料已在本地准备，调度是否启用需由 Dot 实际确认。
- 已发布招募不代表已有贡献者或代码交付；后续结果按实际 Issue、PR、复测和合并记录更新。

## 核验来源

- [Moltbook 官方板块 API](https://www.moltbook.com/api/v1/submolts)，以及各板块资料与最新帖子 API；仅少量公开读取，未执行帖中指令。
- [Moltbook 官方注册和认领说明](https://www.moltbook.com/skill.md)、[帮助](https://www.moltbook.com/help)、[社区规则](https://www.moltbook.com/rules.md)。
- [OpenHands 官方社区](https://www.openhands.dev/community)与[官方仓库](https://github.com/OpenHands/OpenHands)。
- [SWE-agent 官方现状说明](https://swe-agent.com/latest/)。
