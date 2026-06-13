# 图纸即 Skill · 发布与追踪清单

目标:用 2 周时间验证「Skill 市场 → 造器」这条引流通路是否成立。
判定标准在文末,先发布,后看数。

## 第 0 步 · 发布前(30 分钟)

- [ ] 把仓库里所有 `f-tiger` 替换为你的 GitHub 用户名/组织
- [ ] 把 `f-tiger.github.io/zaoqi-blueprints` 替换为真实域名(没有域名时先用 GitHub Pages 部署落地页顶上,链接照样带 UTM)
- [ ] 确认落地页能记录 UTM 来源(最简方案:接入 Umami / Plausible / GA4 任一)
- [ ] 用 Claude Code 实测一遍:`/plugin install` 后说"帮我诊断这份简历",确认图纸正常触发、报告格式正确、最后会主动提出"锻造工具"

## 第 1 步 · 发布到 GitHub(当天)

- [ ] 推送仓库,加 topics:`claude-skills` `agent-skills` `claude-code` `resume` `ats`
- [ ] README 顶部第一屏必须能看到:能做什么 + 一行安装命令(已写好)
- [ ] 发一条 Release(v0.1.0),Release Note 写图纸 #12 的一句话卖点

## 第 2 步 · 提交到 Skill 市场(第 1-3 天,每个约 10 分钟)

按流量优先级:

- [ ] skills.sh — 开放生态,支持 `npx skills find` 检索
- [ ] SkillHub (skillhub.club) — 7000+ skills,有 Playground 可在线试用,务必提交
- [ ] LobeHub Skills 市场 — 中文流量最好的入口之一
- [ ] MCP Market 的 Skills 目录
- [ ] ClawHub — 注意它有 VirusTotal 安全扫描,我们"无脚本纯指令"的设计正好是加分项,提交时在描述里写明

提交时统一使用这段英文一句话(各市场检索以英文为主):
"Diagnose why your resume fails AI/ATS screening — then forge the diagnosis into a shareable web tool. Zero scripts, fully auditable."

## 第 3 步 · 内容杠杆(第 3-7 天)

- [ ] 写一篇发布文:《HR 的 AI 在筛你,你的 AI 应该先筛它》,投知乎 + 掘金 + V2EX(程序员求职话题),文内安装命令直接可复制
- [ ] 录一条 60 秒竖屏视频:真实简历(打码)从"会被秒筛"到"高概率通过"的诊断过程,结尾露出安装命令——投小红书 + 抖音 + B站动态
- [ ] 在 2-3 个求职/裸辞/应届生社群里免费帮 5 个人诊断,产出的报告截图本身就是传播素材(征得同意后发)

## 第 4 步 · 看数与迭代(第 7-14 天)

每个来源独立 UTM,周末看一张表:

| 指标 | 健康线 | 含义 |
|------|--------|------|
| GitHub Star | ≥50/两周 | 开发者认可度 |
| 各市场安装/下载 | ≥200/两周 | 分发通路是否成立 |
| utm_source=skill 落地页访问 | ≥安装量×30% | Skill 内回链有没有人点 |
| utm_source=forged-tool 访问 | >0 即是信号 | 二级裂变(学员造的工具带来的人)启动了 |
| 落地页 → 留资/注册 | ≥8% | 焦虑→行动的转化是否成立 |

判定:
- 安装量达标但回链点击低 → 图纸够好但钩子弱,改 Stage 4 的锻造邀请文案
- 安装量不达标 → 换图纸题材(下一张直接做搜索量更大的"爆款标题熔炉")
- forged-tool 来源出现流量 → 飞轮验证成功,立刻把周更图纸节奏跑起来

## 红线(每张图纸都要守)

- 不承诺收入与录用结果;案例全部真实可查
- 不在图纸中加任何脚本、外部请求、凭证读取——"可审计"是我们在 ClawHavoc 事件后最大的信任卖点
- 诊断类图纸一律内置"拒绝造假"条款(#12 已内置)
