# 刘晓燕英语 · Claude Code Skill

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blue)](https://claude.ai/code)
[![CET-6 2026.6](https://img.shields.io/badge/CET--6-2026.6%20校准-success)](references/cet6-2026-06.md)
[![GitHub stars](https://img.shields.io/github/stars/tong666-bit/liu-xiaoyan-skill?style=social)](https://github.com/tong666-bit/liu-xiaoyan-skill)

> **30 秒懂：** 把考研/四六级名师「骂醒式教学」装进 Claude——像晓燕老师一样讲阅读、拆长难句、组写作、定计划。  
> **额外加持：** 已用 **2026 年 6 月六级真题三套** 校准答案逻辑与给句写作格式。

如果你在用 [Claude Code](https://claude.ai/code) 备考英语，装上这个 skill，对话即可触发。

**觉得有用？点右上角 ⭐ Star，让更多同学刷到。**

---

## 这是什么？

| 你得到的 | 说明 |
|----------|------|
| 🎤 **讲课模式** | 大白话 + 段子讲语法/阅读/翻译，不灌鸡汤 |
| 🏋️ **解题教练** | 贴题进来 → 同义转述定位 → 干扰项点杀 |
| 📅 **备考规划** | 按考试、剩余时间、水平给可执行计划 |
| 📘 **真题校准** | 2026.6 六级听力/阅读答案速查 + 写作给句 + 翻译三套 |

**不是**又一个「温柔 AI 老师」。核心标签是 **骂醒式**：犀利、可操作、跟分数挂钩。

---

## 一行安装

**macOS / Linux**

```bash
git clone https://github.com/tong666-bit/liu-xiaoyan-skill.git ~/.claude/skills/liu-xiaoyan-english
```

**Windows（PowerShell / CMD）**

```bat
git clone https://github.com/tong666-bit/liu-xiaoyan-skill.git %USERPROFILE%\.claude\skills\liu-xiaoyan-english
```

装好后 **新开一轮 Claude Code 对话**，直接说下面任意一句即可。

> 手动：下载 ZIP → 解压到 `~/.claude/skills/liu-xiaoyan-english/`，保证根目录有 `SKILL.md`。

---

## 复制即用 · 触发语

```
用刘晓燕的方式讲六级阅读怎么做
2026年6月六级第1套听力帮我对答案
给句写作：文化自信，帮我列提纲并写一版 150–200 词
帮我分析这道长难句（下面粘贴）
还有两个月考四级，基础差，怎么保命
翻译：远程医疗那段，按「没有不会写的词」带我做
```

---

## 效果长什么样（示意）

**你：** 六级仔细阅读正确选项一般长啥样？

**Skill：**  
来来来，别玄学。2026.6 官方解析几乎统一一句话——**正确答案 = 原文的同义转述**。  
做题四步：题干关键词 → 回原文定位 → 写出「题干词↔原文词」→ 用四类干扰把另外三个宰了。  
……（无中生有 / 偷换对象 / 手段当目的 / 答非所问）

**你：** 写作必须抄题目那句吗？

**Skill：**  
必须。卷面写的是 *begins with the sentence* + *copy the sentence given in quotes*。  
第一句一个字母都别改，第二句马上亮观点，全文 **150–200 词**。  
2026.6 三套给句：文化自信 / 亲近自然 / 青年责任……

---

## 方法论一览

| 模块 | 核心方法 |
|------|----------|
| 阅读 | 骨架法 + **同义转述** + 干扰项套路（2026.6 校准） |
| 听力 | 预读场景词 + 同义转述选答案 |
| 写作 | **给句起笔** + 句型组装（个人/社会/国家） |
| 翻译 | 「没有不会写的词」— 上位词 / 解释含义 |
| 选词 | 词性归类优先，最后做 |
| 长难句 | 拆洋葱：主干 → 剥修饰 → 逐层还原 |
| 词汇 | 谐音 + 词根词缀 + 故事串联 |

---

## 仓库结构

```
liu-xiaoyan-english/
├── SKILL.md                      # 人设 + 模式切换 + 方法论
├── README.md
├── LICENSE
└── references/
    ├── cet6-2026-06.md           # 2026.6 三套答案 / 写作 / 翻译
    ├── reading-strategies.md
    ├── writing-translation.md
    ├── long-sentences.md
    └── study-plans.md
```

---

## 适用考试

CET-4 · CET-6 · 考研英语一 · 考研英语二

---

## 传播文案（可直接发）

**小红书 / 朋友圈标题示例：**

> 把刘晓燕的骂醒式教学做成了 Claude Skill  
> 还塞了 2026.6 六级三套答案校准  
> 链接：https://github.com/tong666-bit/liu-xiaoyan-skill

**一句话推荐：**

> 备考四六级别只让 AI 温柔安慰——这个 Skill 按真题逻辑拆题，给句作文和同义转述都写进方法论了。

---

## 贡献

- Issue / PR 欢迎：真题勘误、更多范例对话、听力扩充  
- 帮到你了请 **Star ⭐** 或转发给正在备考的同学  

---

## 免责声明

基于公开教学资料与方法论整理，**与刘晓燕老师本人及其所属机构无直接关联**。仅供学习交流；如有侵权请联系删除。考试内容版权归命题与出版方。

## License

[MIT](LICENSE)
