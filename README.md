# Lovart Skills 合集

这里收集了我搭建的 Lovart 设计 Skill。每个 Skill 是一个 `SKILL.md` 文件，可直接复制到 Lovart 的「Create a Skill」中复用。

## 包含的 Skill

| Skill | 说明 | 文件 |
|-------|------|------|
| 复古专辑封面 | 把照片变成复古胶片框 + 手写文字风格，含暗角/颗粒/漏光/暖调单色 | `vintage-album-cover_SKILL.md` |
| 监控街头档案 | 把照片变成 gritty 街头监控档案风格，含深色噪点背景/红蓝小视窗/标注线框/扫描线 glitch | `surveillance-street-archive_SKILL.md` |

## 封面图

封面图放在 `covers/` 目录，供各 `SKILL.md` 的 `cover` 字段引用。

## 安装方法（单个 Skill）

1. 打开对应的 `SKILL.md` 文件，复制全部内容
2. 在 Lovart 打开 Skill Book → Create a Skill
3. 把内容粘贴进 SKILL.md 文本区
4. 保存为 My Skills 即可使用

## 替换封面图

`SKILL.md` 中的 `cover` 字段是一个公开图片 URL。本仓库的封面图经 GitHub 公开后，可替换成对应的 Raw URL：

- 复古专辑封面：`https://raw.githubusercontent.com/shift-ailab/shift-skills/main/covers/vintage-album-cover.jpg`
- 监控街头档案：`https://raw.githubusercontent.com/shift-ailab/shift-skills/main/covers/surveillance-street-archive.jpg`
