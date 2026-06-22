# tuxing-tuili-coach

公务员行测图形推理（图推）解题 Skill。

它把图推题的解题流程封装成一个可复用的 Agent Skill：

- 判断题型
- 抓第一眼特征
- 调用图推规律
- 验证题干
- 排除选项
- 给出答案与识别信号

## 文件结构

```text
tuxing-tuili-skill/
├─ SKILL.md
├─ references/
│  ├─ answer_template.md
│  └─ rule_checklist.md
└─ examples/
```

## 使用方式

把整个文件夹放到支持 Agent Skills 的工具中，或把仓库上传到 GitHub 后分享给别人。

使用时可以这样提问：

```text
请使用 tuxing-tuili-coach skill 解这道公务员行测图推题。
要求：先判断题型，再观察特征，调用知识点，验证规律，排除选项，最后给答案。
```

## 版权说明

本仓库只提供通用解题流程和原创整理框架。请不要上传未经授权的教材、课程讲义、题库截图或付费资料原文。
