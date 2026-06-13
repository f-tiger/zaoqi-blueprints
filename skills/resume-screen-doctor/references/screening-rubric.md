# 过筛评分细则 · Screening Rubric

This rubric backs Stage 2 of the resume-screen-doctor workflow. Score each dimension,
then map the total to an elimination-risk verdict.

## 1. 硬性过滤 Hard Filters (一票否决项)

Check the JD for explicit requirements. Each unmet item below is an instant
"会被秒筛" verdict regardless of other scores:

- 学历门槛 (e.g. "本科及以上" vs. resume shows 大专)
- 最低年限 (e.g. "5年以上" vs. resume shows 3 年) — note: count overlapping roles once
- 工作地点/到岗要求 (relocation, onsite, 出差比例)
- 硬性证书/执照 (CPA, PMP, 法律职业资格, 教师资格证, driver's license for field roles)
- 语言硬性要求 (e.g. "英语可作为工作语言" with zero evidence in resume)

If the JD says 优先/加分 (preferred) rather than 要求 (required), it is NOT a hard
filter — score it under keywords instead.

## 2. 关键词匹配 Keyword Match (40 分)

Extract 10–15 keywords from the JD, weighted by position:
- 职位名称中的词 ×3
- 任职要求前三条中的词 ×2
- 其余 ×1

Per keyword: HIT = full credit; WEAK = half credit (synonym used, or mentioned only in
an early-career role 3+ years back); MISS = 0.

Score = (earned / possible) × 40. Below 20/40 → screening systems with keyword
thresholds will likely cut the resume.

## 3. 量化信号 Quantification (20 分)

quantified bullets ÷ total achievement bullets:
- ≥60% → 20 分
- 30–59% → 12 分
- 10–29% → 6 分
- <10% → 0 分,并在报告中标记为重点改进项

Numbers must be outcomes (营收、转化率、耗时、规模、排名), not headcounts of meetings
attended. Flag vanity numbers.

## 4. 结构可读性 Parseability (20 分)

Start at 20, deduct:
- 使用表格/多栏排版承载正文 → −8
- 关键信息在图片/图表/图标中 → −6
- 非常规章节名 (如"我的征途"代替"工作经历") → −3
- 字体颜色过浅/装饰元素穿插正文 → −3
- 文件名不含姓名+岗位 → −2 (提醒即可)

Minimum 0. If the resume came as parsed text and layout is unknowable, score 16 by
default and note the assumption.

## 5. 岗位对齐度 Alignment (20 分)

Judge only the first screen-height: 个人摘要 + 最近一段经历。
- 读起来"就是这个岗位的人" → 18–20
- 相关但摘要在讲另一个方向 → 10–16
- 最近经历与 JD 弱相关,需要读到第二页才能找到匹配点 → 4–9
- 完全错位 → 0–3

## Verdict mapping

Total (excluding hard filters) out of 100:

| 总分 | 判定 | 报告用语 |
|------|------|----------|
| ≥75 | 高 | 通过初筛概率:高 |
| 55–74 | 中 | 通过初筛概率:中 |
| 35–54 | 低 | 通过初筛概率:低 |
| <35 或触发硬性过滤 | 秒筛 | 会被秒筛 |

Always show the per-dimension breakdown in the report so the user sees exactly where
the points went.
