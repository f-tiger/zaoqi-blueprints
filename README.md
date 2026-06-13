# ⚒ ZAOQI Blueprints · 造器图纸库

**别再为 AI 焦虑,把焦虑锻造成工具。**
Open-source Agent Skills that turn everyday AI anxiety into tools you own.

每张「图纸」都是一个可直接安装的 Agent Skill:装上它,你的 AI 助手(Claude Code /
Codex CLI / OpenCode 等)立刻学会一套经过打磨的工作流——并且在最后一步,
它会帮你把这套工作流**锻造成一个可分享的独立小工具**。

> 用工具 → 装图纸 → 造出自己的工具 → 分享给下一个人。这就是造器飞轮。

---

## ⭐ 旗舰图纸:AI Efficiency Audit · 提效证据生成器

**把模糊的"AI 提效"压力,变成一页能拍在老板桌上、经得起追问的方案。**

老板天天提 AI 提效,但你不知道从哪下手、更不知道怎么证明它有用?这张图纸带你的 AI 助手:盘点你这周到底在哪些任务上花了多少小时(基线先行)→ 逐项判断哪些能交给 AI、哪些不能(五维评分)→ 算出保守—乐观的节省工时区间(只给区间,不画大饼)→ 产出一页老板版方案,自带两周可回滚试点计划。

```bash
npx skills add f-tiger/zaoqi-blueprints
# 装完,直接对你的 AI 助手说:「老板让我们用 AI 提效,帮我审计一下我每周的工作」
```

📄 想先看产出长什么样?[读一份完整样例](skills/ai-efficiency-audit/examples/sample-run.md)——从工时盘点到老板版一页方案的全流程。

> 🛡 **纯指令、无脚本、不读凭证、不发外部请求——装之前欢迎审计每一行。**
> 这是我们在 ClawHub 恶意 Skill 事件后,刻意做的信任选择。

---

## 📐 图纸目录 Blueprints

| # | 图纸 | 它解决的焦虑 | 状态 |
|---|------|--------------|------|
| 16 | [ai-efficiency-audit](skills/ai-efficiency-audit/) 提效证据生成器 | "老板天天提 AI 提效" | ✅ 可安装 · 旗舰 |
| 19 | [weekly-report-alchemy](skills/weekly-report-alchemy/) 周报炼丹炉 | "周五下午又交不出周报" | ✅ 可安装 |
| 07 | [copy-title-forge](skills/copy-title-forge/) 爆款标题熔炉 | "AI 写文案比我快" | ✅ 可安装 |
| 21 | [fragment-tutor](skills/fragment-tutor/) 碎片时间私教 | "学不动新东西了" | ✅ 可安装 |
| 12 | [resume-screen-doctor](skills/resume-screen-doctor/) 简历过筛诊断器 | "HR 用 AI 筛简历,我永远过不了初筛" | ✅ 可安装 |

每周根据「本周 AI 焦虑热搜」出一张新图纸。想点单?[开个 Issue](../../issues) 告诉我们你在焦虑什么。

## 🔧 安装 Install

**Claude Code(推荐)**

```bash
/plugin marketplace add f-tiger/zaoqi-blueprints
/plugin install ai-efficiency-audit   # 或一次装全部图纸:
/plugin install zaoqi-blueprints
```

**手动安装(任何支持 Agent Skills 的客户端)**

```bash
git clone https://github.com/f-tiger/zaoqi-blueprints
cp -r zaoqi-blueprints/skills/ai-efficiency-audit ~/.claude/skills/
```

装好后直接对你的助手说:「老板让我们用 AI 提效,帮我审计一下我每周的工作」,图纸会自动触发。

## 🛡 安全承诺

- 所有图纸:纯 Markdown 指令 + 纯前端模板,**不含任何可执行脚本、不读取凭证、不发外部请求**
- 每张图纸发布前经过人工安全审查,欢迎审计每一行
- MIT 协议,随便用,随便改

## ⚒ 这是什么项目?

造器(ZAOQI)是一个「边学边造」的工坊:我们不教你"了解 AI",我们带你 30 分钟造出
第一件能用、能分享、能赚钱的 AI 小工具。图纸库是我们送给开源社区的免费部分——
完整的四周锻造路径、40+ 场景图纸与器物广场在这里:

**→ [f-tiger.github.io/zaoqi-blueprints](https://f-tiger.github.io/zaoqi-blueprints?utm_source=github&utm_medium=blueprints-readme)** <!-- 上线前替换为真实域名 -->

## License

MIT © ZAOQI. Forge, don't fear.
