# liu-xiaoyan-english

**刘晓燕英语教学 Skill** —— 一个 [Claude Code](https://claude.ai/code) 技能插件，将考研/四六级英语名师刘晓燕的教学方法论、讲课风格和备考规划能力蒸馏为 AI 技能。

## 这是什么？

这个 skill 让 Claude 像刘晓燕老师一样教你英语——用她的"骂醒式教学"风格、系统的解题方法论、和实用的备考策略，帮助学生备考四六级和考研英语。

### 三种互动模式

- **讲课模式** 🎤 —— 像晓燕老师上课一样，用段子和大白话讲解语法、阅读技巧等概念
- **解题教练** 🏋️ —— 发一道阅读/翻译/写作/完形题，按她的方法论一步步拆解
- **备考规划** 📅 —— 根据你的水平和目标，给出分阶段的复习计划

### 覆盖的方法论

| 模块 | 核心方法 |
|------|---------|
| 阅读理解 | 骨架定位 + **同义转述** + 干扰项四/六大套路（2026.6 校准） |
| 听力 | 预读场景词 + 同义转述选答案 |
| 翻译 | "没有不会写的词"——上位词法、解释含义法替换 |
| 写作 | **给句起笔**（抄句）+ 句型组装法 |
| 选词填空 | 词性归类优先，最后做 |
| 长难句 | 拆洋葱法：找主干→剥修饰→逐层还原 |
| 词汇 | 谐音联想 + 词根词缀 + 故事串联 |

### 真题校准

已融入 **2026年6月 CET-6** 真题结构、第1套客观题答案速查、写作三套给句、翻译题材与官方解析逻辑（见 `references/cet6-2026-06.md`）。

## 安装方法

### 方法一：克隆到 skills 目录（推荐）

```bash
# macOS / Linux
cd ~/.claude/skills
git clone https://github.com/tong666-bit/liu-xiaoyan-skill.git liu-xiaoyan-english

# Windows
cd %USERPROFILE%\.claude\skills
git clone https://github.com/tong666-bit/liu-xiaoyan-skill.git liu-xiaoyan-english
```

### 方法二：手动下载

1. 下载本仓库的 ZIP 文件
2. 解压到 `~/.claude/skills/liu-xiaoyan-english/` 目录下
3. 确保 `SKILL.md` 文件在该目录的根目录

## 使用方法

安装后，在 Claude Code 中直接对话即可触发。示例：

- "四六级阅读理解怎么做？"
- "帮我分析这道长难句"
- "还有两个月考四级，基础差，怎么准备？"
- "用刘晓燕的方式教我写作文"

## 文件结构

```
liu-xiaoyan-english/
├── SKILL.md                        # 核心人设 + 方法论
├── README.md                       # 本文件
├── LICENSE                         # MIT 许可证
└── references/
    ├── cet6-2026-06.md             # 2026.6 六级真题校准（答案/题型/范例）
    ├── reading-strategies.md       # 阅读理解完整攻略
    ├── writing-translation.md      # 写作模板 + 翻译技巧
    ├── long-sentences.md           # 长难句拆解框架
    └── study-plans.md              # 备考规划模板
```

## 适用考试

- 大学英语四级（CET-4）
- 大学英语六级（CET-6）
- 考研英语一
- 考研英语二

## 贡献

欢迎提交 Issue 和 PR！如果你也是刘晓燕老师的学生，欢迎补充更多她的教学方法和技巧。

## 免责声明

本项目是基于公开教学资料的方法论整理，旨在帮助更多学生学习。本项目与刘晓燕老师本人及其所属机构无直接关联。如有侵权请联系删除。

## License

[MIT](LICENSE)
