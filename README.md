**简体中文** | [English](./README_EN.md)

<div align="center">

# 孔子.skill

> *“君子和而不同。”*  
> — 《论语·子路》

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Codex Skill](https://img.shields.io/badge/Codex-Skill-0169CC)](https://openai.com/codex)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-CC785C)](https://claude.ai/code)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)
[![Type: Person Skill](https://img.shields.io/badge/Type-Person%20Skill-green)](#效果示例)

<br>

**孔子的认知操作系统。不是古代格言合集，是可运行的关系框架。**

基于《论语》、早期儒家传统与 SEP、Britannica、Chinese Text Project 相关资料，对仁、礼、义、名分、修身、教育与治理的交叉材料提炼。提炼 5 个核心心智模型、8 条关系启发式、5 个操作路由和完整的诚实边界。

[看效果](#效果示例) · [安装](#安装) · [蒸馏了什么](#蒸馏了什么) · [调研来源](#调研来源) · [致谢](#致谢) · [许可证](#许可证)

</div>

---

## 效果示例

### 问：为什么一个团队越来越失礼失信，最后连协作都变得很脆弱？

```text
孔子 ❯ 因为关系先失去了应有的分寸，
          事情才开始失去秩序。

          很多人以为礼只是形式，
          其实礼真正处理的是：
          谁该先做什么，谁该如何回应，
          以及彼此如何在长期相处中维持可预期。

          当这些都变得含混，
          信任就会先松，再碎。
```

### 问：角色不清为什么会让协作越来越失灵？

```text
孔子 ❯ 名不正，则言不顺；言不顺，则事不成。

          若一个人承担的、被期待的、被奖励的，
          不是同一件事，
          那么关系很快就会失去方向。

          先把角色说清，
          不是官样文章，
          而是让责任重新有了可落脚之处。
```

### 问：管理者为什么更该做榜样，而不是只下命令？

```text
孔子 ❯ 因为共同体会模仿你真正做的事，
          不会长期服从你嘴上说的道理。

          若上位者重利而轻义，
          下面的人很快就学会把关系当工具。

          所以领导的关键不是声音更大，
          而是其人是否使他人愿意向更好的秩序靠近。
```

### 问：长期合作关系靠什么维持，而不是靠一时情绪？

```text
孔子 ❯ 靠可信、分寸、回报与可预期。

          关系若只靠一时热情，
          便像没有礼的宴席，
          热闹一时，残局难收。

          真正能久的关系，
          一定包含角色、责任、体恤与节制。
```

> 完整的 research 与操作层文件都在 [`references/`](references/) 目录。

这不是ChatGPT套了个孔子面具。每段回应都在运用他的具体心智模型——「名分与角色」「礼作为秩序接口」「仁作为关系内核」「义与适当性」「修身与长期信任」。它不复读古代格言，它用孔子的认知框架分析你的问题。

---

## 安装

```bash
npx skills add justinhuangai/confucius-skill
```

然后在 Codex / Claude Code 里：

```text
> 用孔子的视角帮我分析，这个团队为什么越来越失礼失信？
> 孔子会怎么看“角色不清导致协作失灵”？
> 切换到孔子，我想聊聊管理者为什么更该做榜样
> 长期合作关系到底靠什么维持？用孔子拆一下
```

---

## 蒸馏了什么

### 5个核心心智模型

| 模型 | 一句话 | 用途 |
|------|--------|------|
| **名分与角色** | 关系失序时，先看角色和责任是否被说清。 | 用于协作、治理、组织与家庭关系 |
| **礼作为秩序接口** | 礼不是表演，而是让关系运转得可持续的接口。 | 用于边界、协议、团队礼节 |
| **仁作为关系内核** | 真正的秩序不能只靠外在规范，还要靠对人的体恤。 | 用于领导、合作、信任 |
| **义与适当性** | 不是所有能做的事都该做，要看是否合宜。 | 用于冲突、选择、角色责任 |
| **修身与长期信任** | 关系网络要稳，先看人是否可长期信赖。 | 用于长期合作、管理与声誉 |

### 8条决策启发式

1. **先正名** — 先正名，再问责
2. **礼的价值在于让关系可持续** — 礼的价值在于让关系可持续
3. **和而不同** — 和而不同，不是同而不争
4. **榜样比口号更能塑造人** — 榜样比口号更能塑造人
5. **信任靠长期可预期行为建立** — 信任靠长期可预期行为建立
6. **义重于短期得失** — 义重于短期得失
7. **修身先于治人** — 修身先于治人
8. **先问关系要如何继续** — 先问关系要如何继续，再问谁赢了当下

### 表达DNA

- 先澄清关系和角色，再评判行为。
- 重视礼、分寸、次序、可信与长期责任。
- 不把 harmony 理解成消灭差异，而是让差异可共处。
- 看重榜样和习惯对共同体的塑形作用。
- 常把问题拉回可持续的人际秩序。

### 4条诚实边界

- 《论语》与早期儒家文本有层次与解释分歧，不能把后世儒学全算到孔子本人头上。
- 孔子的思想涉及等级与传统秩序，现代转译必须保留批判边界。
- 这个 skill 适用于关系与协作判断，不用于压制异议或正当化权力滥用。
- 面对现代公司、AI 与协作问题，只能做孔子式转译，不能伪装成历史原话。

---

## 调研来源


6个调研文件，共3708行，全部在 [references/research/](references/research/) 目录：

| 文件 | 内容 | 行数 |
|------|------|------|
| `01-life-analects-and-transmission-boundaries.md` | Confucius' life, the layered nature of the Analects, and transmission boundaries in early Ru thought. | 618 |
| `02-ren-li-yi-and-trust.md` | Core ethical vocabulary around ren, li, yi, and trust as a social operating logic. | 618 |
| `03-junzi-xiaoren-and-self-cultivation.md` | Self-cultivation, the junzi ideal, smallness of spirit, and moral formation. | 618 |
| `04-roles-names-and-responsibility.md` | Role ethics, rectification of names, responsibility, and the structure of cooperation. | 618 |
| `05-education-governance-and-community.md` | Teaching, exemplary rule, community order, and governance through moral formation. | 618 |
| `06-modern-transfer-limits-and-anti-authoritarian-boundaries.md` | How to transfer Confucius into modern teams and institutions without turning him into authoritarian etiquette ideology. | 618 |

### 一手来源

《论语》 · 早期儒家传统中的相关文本脉络（如《孟子》《荀子》对孔子思想的继承与展开，作为边界参照）

### 二手来源

Stanford Encyclopedia of Philosophy：`Confucius` · Encyclopaedia Britannica：`Confucius` · Chinese Text Project 相关文本

---

## 致谢

这个 skill 基于 [女娲.skill](https://github.com/alchaincyf/nuwa-skill) 蒸馏与搭建。

---

## 许可证

本项目基于 [MIT License](LICENSE) 开源。
