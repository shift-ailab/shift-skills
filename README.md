# 设计 Skill 合集

这里收集了我整理的设计类 Skill / 提示词模板。每个 Skill 是一个 Markdown 文件，包含完整的风格定义、工作流程与关键约束，可直接复制到支持自定义提示词或 Skill 的 AI 平台中使用。

## 包含的 Skill

| Skill | 说明 | 文件 |
|-------|------|------|
| 复古专辑封面 | 把照片变成复古胶片框 + 手写文字风格，含暗角/颗粒/漏光/暖调单色 | `vintage-album-cover_SKILL.md` |
| 监控街头档案 | 把照片变成 gritty 街头监控档案风格，含深色噪点背景/红蓝小视窗/标注线框/扫描线 glitch | `surveillance-street-archive_SKILL.md` |

## 封面图

封面图放在 `covers/` 目录，供各 Skill 文件中的 `cover` 字段引用。各 Skill 的 `cover` 字段指向 GitHub Raw URL：

- 复古专辑封面：`https://raw.githubusercontent.com/shift-ailab/shift-skills/main/covers/vintage-album-cover.jpg`
- 监控街头档案：`https://raw.githubusercontent.com/shift-ailab/shift-skills/main/covers/surveillance-street-archive.jpg`

## 使用方法

1. 打开对应的 Skill 文件，复制全部内容或按需提取正文提示词。
2. 粘贴到你想使用的 AI 平台（如 Midjourney、ChatGPT、Claude、Kimi、豆包等）的提示词/自定义 Skill 区域。
3. 根据平台要求保存为自定义 Skill 或作为系统提示词使用。
