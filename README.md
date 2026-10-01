# GPT_Intelligence_Reduction_Incident_Investigation_Report

[English](#english-readme) | [中文](#chinese-readme)

<a name="english-readme"></a>

## English README

Statistical Report and In-Depth Analysis of the GPT Degradation Incident Based on Personal Observations—I Have Brought a Comprehensive Perspective, Valuable Data, Bold Speculations, and Psychological Support for Everyone [Completed on the evening of 26-09-27]

### Introduction

Written entirely by hand by an individual, this report brings together personal observations, community feedback, and test records to explore GPT intelligence degradation, detection methods, possible causes, and potential responses. It also aims to offer some support to affected users.

- Completed on September 27, 2026. Ongoing updates are not guaranteed.
- Start with “Key Conclusions” (核心结论先行); test prompts are provided in Section 15.
- The report includes personal judgments and hypotheses, with the author's confidence levels marked. Please read them in light of the evidence.

Sharing, quoting, and redistribution are welcome, as are discussion and corrections.

### September 30, 2026 — Additional Information

#### Observation 1

Using the same set of test questions (keep in mind that users affected by degradation are the ones likely to follow this information), even among users who claim their models are operating at full capability or have recovered:

- No one has answered all test questions correctly across all models from 6 to 5.6.
- When users test the 6 series across all models and reasoning levels, the reported breakdown is:
  - <1% → 6.5
  - 95% → 5.5
  - 5% → 5.2 / 5.4

#### Observation 2

As the model tier and reasoning level increase, test results form a progressively longer staircase pattern. This characteristic persists across fluctuation cycles (250s).

- Assumed pattern: A123 B123 C123
- Observed pattern: L12**3** A1**23** B**123** C**123** ← 【A12**3** B1**23** C**123**】 → A123 B12**3** C1**23**

#### Observation 3

The web version of chat-5.6-sol-instant consistently passes the internal knowledge test.

#### Updated Hypotheses About the Mechanism

1. All models and reasoning levels, except web-chat-5.6-sol-instant, are involved in the degradation incident.
2. One possible internal mechanism is that each model and reasoning level has a different base score according to its intelligence or standing, rather than necessarily being treated directly according to intelligence. OpenAI assigns flags based on collected information, then deducts points across all models and reasoning levels according to how “clean” those flags are. After these deductions, some models or reasoning levels fall below a threshold and are routed to the lower-capability 5.5 model.
3. The possibility of larger models being replaced internally by smaller models within the same series cannot be ruled out either (based on unreliable reports).

#### Another Possible Mechanism

Over the past two days, 2–3 users have suggested that “GPT automatically assigns models or reasoning levels based on task difficulty.”

[English](#english-readme) | [中文](#chinese-readme)

---

<a name="chinese-readme"></a>

## 中文 README

基于个人观察的GPT降智事件的统计报告与深入分析——我带来了全面的视角，珍贵的数据，大胆的推测，以及同在的心理支持【完稿于26-09-27日晚】

### 简介

完全由个人手动撰写，汇总个人观察、网友反馈与测试记录，讨论 GPT“降智”现象、检测方法、可能原因及应对思路，也希望为受影响的用户提供一些支持。

- 完稿于 2026 年 9 月 27 日，不承诺持续更新。
- 建议先看“核心结论先行”；测试提示词见第 15 节。
- 文中包含个人判断与推测，并标注了作者的确信程度，请结合证据阅读。

欢迎转发、引用、分发，也欢迎交流与纠正。

### 2026 年 9 月 30 日补充信息

#### 现象 1

在同一套测试题下（留意：降智用户才会关注这些信息），即便在声称自己满血／恢复的用户中：

- 没有人从 6 到 5.6 的所有测试是能全部答对的。
- 大部分人用 6 系列（所有模型、所有思考等级）测试的情况下：
  - <1% → 6.5
  - 95% → 5.5
  - 5% → 5.2／5.4

#### 现象 2

测试结果随着模型及思考等级的提升呈现逐渐变长的阶梯状，且跨波动周期（250s）仍保留该特性。

- 假设：A123 B123 C123
- 结果：L12**3** A1**23** B**123** C**123** ← 【A12**3** B1**23** C**123**】 → A123 B12**3** C1**23**

#### 现象 3

网页 chat-5.6-sol-instant 始终能回答出内部知识测试。

#### 机制推论更新

1. 除了 web-chat-5.6-sol-instant 外，所有的模型和思考等级都参与了降智事件。
2. 内部机制可能是所有模型和思考等级按照智商或地位有不同基础分数（而不一定直接根据智商处理），OpenAI 根据收集的信息打标记，之后根据标记的干净程度，对所有模型的所有思考等级进行扣分。扣分后，有些模型或思考等级的分数直接被击穿，路由到更低的 5.5 模型去。
3. 同时无法排除内部用同系列的小模型替换大模型（有不可靠消息）。

#### 潜在机制补充

这两天，有 2–3 名用户提供了“GPT 会根据任务难度自动分配模型／思考程度”的说法。

[English](#english-readme) | [中文](#chinese-readme)
