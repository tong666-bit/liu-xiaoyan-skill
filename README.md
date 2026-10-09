# 刘晓艳风格英语 Skill

直白、幽默、分步讲题的英语陪练，覆盖 **CET-4 / CET-6 / 考研英语一、二**。保留原 skill 名 `liu-xiaoyan-english` 和仓库名，兼容“刘晓燕 / liuxiaoyan”叫法；书目作者名为刘晓艳。

**非本人、非官方出品。**课堂话术与例题为教学设计，不冒充老师原话。

## 2026-10-09 更新

- 增加听力精听与错因诊断、熟词僻义与搭配、检索/间隔复习。
- 增加考研完形、新题型、英一/英二区别与时间安排。
- 增加作文批改、最小修改、图表百分点辨析和错题卡。
- 扩充长难句：限定谓语、非谓语、同位语/定语、形式主语/强调、倒装。
- 核对官方题型、权重、报道分与2026下半年安排。
- 保留2026年6月旧版OCR答案，**标记待核验**；取消旧表强制优先，补花卷/套号配对规则。
- 建立[来源索引](references/sources.md)：能确认的事实、历史资料、未逐题核验部分分开说明。

## 安装与更新

Claude Code 用户级安装：

**macOS / Linux**
```bash
git clone https://github.com/tong666-bit/liu-xiaoyan-skill.git ~/.claude/skills/liu-xiaoyan-english
```

**Windows PowerShell**
```powershell
git clone https://github.com/tong666-bit/liu-xiaoyan-skill.git "$env:USERPROFILE\.claude\skills\liu-xiaoyan-english"
```

**Windows CMD**
```bat
git clone https://github.com/tong666-bit/liu-xiaoyan-skill.git "%USERPROFILE%\.claude\skills\liu-xiaoyan-english"
```

已安装且没有本地修改时，在该skill目录执行 `git pull --ff-only`。有自定义内容先保存，处理冲突后更新。重新打开会话以读取更新。

其他支持 Agent Skills 的工具可把整个仓库放进其文档指定的skill目录，保留 `SKILL.md`、`references/` 和 `examples/`。复制SKILL.md正文到普通提示词不会自动携带参考文件。

## 用法

```text
用刘晓艳风格讲这篇六级阅读，先定位证据，再分析我误选的选项。（附原题）
看听力稿懂、实际听不出来，按我提供的录音诊断。
拆这个长难句，并告诉我哪个动词是主句谓语。
批改我的考研英语二作文，保留我的句子，先给最小修改版。
还有8周考六级，每天90分钟，听力弱，给我可执行的计划。
```

更多请求和行为检查见 [examples/demo-prompts.md](examples/demo-prompts.md)。

## 讲题示意（自编）

“来，别跟选项谈感情。原文只是说‘相关’，这个选项却说‘必然导致’，它把结论升级了。咱们把对象、范围和因果分别对一遍。”

风格用于帮助理解；学生情绪低落时可以放缓。不会以“保命技巧”代替原文证据，也不保证分数。

## 资料导航

| 模块 | 文件 |
|---|---|
| 考试结构、日期、分数解释 | [exam-facts.md](references/exam-facts.md) |
| 阅读/匹配/选词 | [reading-strategies.md](references/reading-strategies.md) |
| 听力 | [listening.md](references/listening.md) |
| 词汇与复习 | [vocabulary.md](references/vocabulary.md) |
| 长难句 | [long-sentences.md](references/long-sentences.md) |
| 作文与翻译 | [writing-translation.md](references/writing-translation.md) |
| 考研专项 | [kaoyan-english.md](references/kaoyan-english.md) |
| 批改与诊断 | [feedback-and-diagnosis.md](references/feedback-and-diagnosis.md) |
| 计划 | [study-plans.md](references/study-plans.md) |
| 旧版2026年6月六级记录 | [cet6-2026-06.md](references/cet6-2026-06.md) |
| 来源与核验状态 | [sources.md](references/sources.md) |

## 关于旧版真题答案

旧版整理声称来自桌面试题册OCR，原件未随仓库提交。机构参考资料与旧版套号存在差异；花卷选项也可能不同。提供原题与选项之后再核证据，不能只按“第几套”取答案。

考试规则以最新官方通知和当次题面为准；近期安排不能永久写死。开源指令和原创内容采用 [MIT](LICENSE)；第三方试题、教材和课程内容保留其原有权利，不因仓库MIT许可而变成自由授权材料。
