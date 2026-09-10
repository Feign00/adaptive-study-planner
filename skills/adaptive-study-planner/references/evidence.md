# 方法依据与适用边界

核验日期：2026-09-10。以下把学习原则、工程化调度规则和社区 Skill 的灵感分开。具体时间表没有直接经过对本人的实验验证。

## 学习研究

| 来源 | 支持的设计方向 | 不应从中推出 |
|---|---|---|
| Dunlosky等，2013，[Improving Students’ Learning With Effective Learning Techniques](https://www.psychologicalscience.org/journals/pspi/1529100612453266/)，[DOI](https://doi.org/10.1177/1529100612453266) | 综述对练习测试和分散练习给出较高总体评价；本技能将独立检索与跨天复习作为常用方法 | 每个人都必须用相同分钟数；所有任务都适合闪卡；必要讲解没有价值 |
| Pashler等，2007，[IES/WWC实践指南](https://ies.ed.gov/ncee/wwc/PracticeGuide/1) | 指南支持分散学习、交替使用已解示例与解题练习，以及通过测验再接触关键内容；据此保留视频示例并配套独立输出 | 初学者应完全跳过示例；一开始随机混合所有科目更有效；所有建议的证据强度相同 |
| Karpicke & Blunt，2011，[Retrieval Practice Produces More Learning than Elaborative Studying with Concept Mapping](https://doi.org/10.1126/science.1199327)，[作者版全文](https://learninglab.psych.purdue.edu/downloads/2011/2011_Karpicke_Blunt_Science.pdf) | 科学文本学习实验中检索练习在延迟学习结果上表现较好；本技能据此加入闭卷回忆与延迟验证 | 该文本实验已直接验证所有高数题、英语口语、计算机实操的固定流程 |

解释原则时引用对应来源并说明迁移范围。发现某学习方法不适合任务或基础时调整，不为了守形式而延误必要教学。间隔学习并不保证能算出个人“即将遗忘”的准确时刻。

## 本技能的调度参数

25–50分钟专注、约10%–20%机动、5–10分钟基础题尝试上限、次日/约3日/7日复习检查点，以及示例中的题数与比例，都是可修改的初始工作假设。它们服务于收尾、反馈与时间约束，不是上面论文证明的统一最优值。

休息由累计负荷与实际疲劳共同决定；不要求数学一定早晨学，不要求运动一定放学习前，不设置每档固定小时数。优先级是依据材料和表现的判断，未知考试概率/分值时不编造数字来计算“精确提分效率”。

## 已核验的社区 Skill 灵感

以下仅概括设计思想，正文为针对本任务重新编写的说明，未整段复制或捆绑外部 Skill；各项目自己的许可仍适用于原文。

- [Study System](https://github.com/SkillMedev/personal-operating-system/blob/main/skills/study-system/SKILL.md)：借鉴可测试学习单元与错因记录；保留新手必要输入，不采纳“重读一律不算学习”或永远只复习错项的绝对规则。
- [Exam Planner](https://github.com/blueqwertz/study-planner/blob/main/SKILL.md)：借鉴优先排序、完成条件与机动时间；去掉默认七天倒计时、无根据的考试概率与僵硬每日时长，增加先修与多科覆盖约束。
- [Exam Study Plan](https://github.com/mohitagw15856/pm-claude-skills/blob/main/skills/exam-study-plan/SKILL.md)：借鉴从考试反推阶段与练习反馈；实际阶段依科目掌握情况，而非到某天统一切换。
- [Spaced Practice Schedule Builder](https://github.com/GarethManning/education-agent-skills/blob/main/skills/memory-learning-science/spaced-practice-scheduler/SKILL.md)：借鉴复习队列与检索活动；不采用固定遗忘百分比或把最佳间隔简化为统一比例的说法，改为依据实际表现调整。

GitHub Skill 是工作流程参考，不能替代研究证据；本仓库不宣称获得这些项目作者背书。
