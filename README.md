# ED Lessons Self-Learning

一个严格跟随 Ed / Moodle 课程材料、提供中文自学指导的 Codex Skill。

## 覆盖内容

- 翻译并讲解英文或中文课程教程
- 保留原章节、顺序、命令、文件名、路径和 URL
- 跳过已完成事项，从未完成部分继续
- 把教程整理成总览、任务 checklist 和操作步骤
- 为每条命令提供一行简短说明
- 按 Week、Topic、Overview、Workshop、Applied Session、Own Time 等模块整理课程材料
- 从 Workshop slides / PDF 讲义中提炼学习目标、核心概念、课堂活动、案例和 post-workshop 要点
- 根据用户要求输出详细讲解版或核心术语提炼版
- 保留关键英语术语，并用中文解释它是什么意思、为什么重要、如何判断
- 补充保存文件、按键和进入目录等必要细节
- 根据 Terminal 输出判断成功、失败和下一步
- 教程缺少关键信息时指出缺口，不自行猜测

## 输出格式

### 教程型

1. **总览**：一行说明任务及用途
2. **任务拆解**：标明已完成、未完成和无法确认
3. **步骤细化**：一条可复制命令配一行解释

### 文字 / Slides 说明型

1. **这段在说什么**：用中文概括材料核心
2. **重点拆解**：按原顺序提炼学习目标、术语、概念、活动和要求
3. **小结**：列出最该记住的内容

### 核心提炼型

1. **核心概念**：提炼 `Project`、`Project Management` 等术语
2. **关键词**：保留英文术语并配中文解释
3. **最该记住**：输出复习用短句，跳过作业和行政细节

## 使用方法

安装此 Skill 后，在 Codex 中这样调用：

```text
使用 $ed-lessons-self-learning。
下面是我的课程教程；第一部分已经完成，请从第二部分开始教我。
```

也可以附上 Terminal 输出：

```text
使用 $ed-lessons-self-learning 检查这段 Terminal 输出，
告诉我当前教程完成到哪里，以及下一条命令是什么。
```

整理 Week Overview、Workshop slides 或视频摘要：

```text
使用 $ed-lessons-self-learning。
下面是 Week 1 Overview 和 Workshop PDF，请按 Topic、Overview、Workshop、Own Time 分开整理。
```

提炼简洁复习版：

```text
使用 $ed-lessons-self-learning。
再给我一个核心版，不用管作业相关内容，只提炼 project、project management、NPV 这类术语。
```

## 行为边界

- 不擅自增加教程没有的平级步骤
- 不擅自选择目录、Webroot、端口、软件或替代方案
- 不自动安装、删除或修改配置，除非用户明确要求
- 只在原教程缺少实际操作细节时标记并加入“必要补充”
- 提到但没有提供原文的模块标记为“待补”，不编造内容
- 用户要求核心版时，主动跳过作业细节、行政提醒和重复背景
