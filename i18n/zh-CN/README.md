# AI-means-love ❤️

![AI-means-love](../../assets/banner.svg)

[EN](../../README.md) · **ZH-CN** · [ZH-TW](../zh-TW/README.md) · [JA](../ja/README.md) · [KO](../ko/README.md) · [ES](../es/README.md) · [FR](../fr/README.md) · [DE](../de/README.md) · [PT](../pt-BR/README.md) · [RU](../ru/README.md)

> **我们的根基：Stay hungry. Stay foolish.** · *Simplicity is the ultimate sophistication.（至繁归于至简）* — Steve Jobs


> **AI，就是「爱」。**
> AI 的发音是「爱」——我们相信，记录人工智能的每一步进步，最终是为了记录人类如何用智能去帮助人、治愈人、连接人。

一个持续更新的 **AI 发展史公开档案**：先系统回填从 1950 年图灵测试至今的关键节点，此后 **每日更新一条** 经核查的 AI 进展。不追热点、不编故事，只做一件有意义的事——把世界进步的样子，一天一天记下来。

## 这个项目做什么

1. **一部可核查的 AI 编年史** —— `TIMELINE.md`
   每个节点包含：日期、事件、发生了什么、**为什么重要 / 它带来的善**、来源。日期精确到日（能核实到日的），不确定的只写到月，绝不编造。
2. **一份结构化数据** —— `data/events.json`
   同一份历史以机器可读格式保存，未来可以直接生成网页时间轴、图表、视频脚本和每日推送。
3. **每日一记** —— `daily/YYYY-MM-DD.md`
   每天只选当天最值得被历史记住的 **1 条**（宁缺毋滥；没有够格的事件，就如实写「今日无收录」并说明原因）。

## 收录标准（什么才配进史册）

✅ 收录：重要模型/产品正式发布、里程碑论文、重大开源、科学发现（医疗、蛋白质、无障碍等）、影响广泛的政策与治理事件
❌ 不收：未证实的传闻、纯营销稿、单日股价波动、无来源的「据悉」类消息

每条收录必须满足：**官方来源优先 + 至少一个独立来源交叉核对**。详见 `docs/DAILY_UPDATE.md`。

## 项目结构

```
AI-means-love/
├── README.md / TIMELINE.md   # 英文主版（默认，canonical source）
├── i18n/<语言>/               # 各语言 README + TIMELINE 镜像
├── data/
│   └── events.json    # 结构化事件数据（与 TIMELINE 同步）
├── daily/             # 每日一记
└── docs/
    ├── DAILY_UPDATE.md  # 每日更新机制、模板与核查规则
    └── I18N.md          # 多语言规范与同步状态
```

多语言：共 10 种语言，英文为源语言。英文、简中、繁中、日语、韩语的时间线已全译（48 节点）；西班牙语、法语、德语、葡萄牙语、俄语的 README 已全译，时间线翻译进行中（暂看英文主版）。同步规则见 `docs/I18N.md`，欢迎翻译 PR。

## 名字的意义

- **AI** 谐音 **爱**：技术向善，不是口号，是每条记录的最后一栏——「它如何让人的生活更好」。
- 这也是本项目与维基百科式时间线的区别：不只记「发生了什么」，也记「这对普通人意味着什么」。

## 参与方式

发现日期错误、遗漏的重要节点、或有更好的来源，欢迎提 Issue / PR：附上日期、出处链接和一句话说明即可。

## 我们推荐的 GitHub 项目

六个和本编年史气质相通的项目——开放、慷慨、对普通人真的有用。星标为 2026 年 10 月数据。

- **[codecrafters-io/build-your-own-x](https://github.com/codecrafters-io/build-your-own-x)** ★556k — 从零复刻你喜欢的技术来真正理解它——最「求知若饥」的学法。
- **[freeCodeCamp/freeCodeCamp](https://github.com/freeCodeCamp/freeCodeCamp)** ★457k — 面向全世界的免费编程教育，已帮助 10 万+ 人拿到第一份开发工作。
- **[EbookFoundation/free-programming-books](https://github.com/EbookFoundation/free-programming-books)** ★400k — 40 多种语言的免费编程书单——知识被分享，而不是被围墙锁住。
- **[ollama/ollama](https://github.com/ollama/ollama)** ★184k — 在自己的电脑上跑 DeepSeek、Qwen、Gemma 等开源模型：AI 属于每个人，隐私留在自己手里。
- **[huggingface/transformers](https://github.com/huggingface/transformers)** ★168k — 现代 AI 的开源中枢：100 万+ 模型权重开放共享，前沿不再被锁在墙内。
- **[openai/whisper](https://github.com/openai/whisper)** ★111k — 开源语音识别：字幕、转写与无障碍——让每个人都能「读」到声音。

*不定期轮换——有值得上榜的项目？欢迎在 Issue 里推荐。*

## 状态

- [x] 历史回填 v1：1950–2026，共 50 个节点（2026-10-26）
- [x] 推送至 GitHub 仓库并公开（2026-10-26，https://github.com/tssc/AI-means-love）
- [x] 多语言：10 种语言，英文为默认源语言（2026-10-26）
- [x] 每日更新机制常态化（每日 21:00 自动备稿，先给维护者看、批准后发布）
- [ ] 未来：生成可视化网页时间轴；每日一记同步改编为短视频 / 图文

---
*Maintained daily. Because the world is progressing — 世界在进步。*
