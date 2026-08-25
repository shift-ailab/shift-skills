---
name: "surveillance-street-archive"
title: "监控街头档案"
description: "当用户想把图片处理成 gritty 街头监控档案风格，或明确要求深色噪点背景、监控界面、红/蓝边框小视窗、主体标注线框、数据字段文字、扫描线/glitch 等数字复古科技感效果时使用。即使只提到'监控''街头''档案''glitch''CCTV''亚文化''黑客档案'' gritty'也应考虑触发。"
version: 1
namespace: "user-generated"
extended:
  cover: "https://raw.githubusercontent.com/shift-ailab/shift-skills/main/covers/surveillance-street-archive.jpg"
  keywords: "surveillance, street archive, gritty, retro tech, CCTV, glitch, underground magazine, street subculture, monitoring, data annotation,扫描线,红蓝线框"
  template: "把[图片]处理成监控街头档案风格：深色噪点背景，中央主体照片，四周带红/蓝边框的小视窗，叠加红/蓝色矩形标注线框与编号标签，顶部监控信息条，底部Shift Design署名，等宽/街头字体数据字段，颗粒、扫描线、glitch数字复古质感。"
  tool_policy:
    allowed_tools:
      - "skill_file"
      - "write_skill"
      - "ask_human"
    enforcement: "enforce"
    mode: "restrict"
    version: 1
---

# 监控街头档案

## 核心方法论
- **调性锚定**：以街头亚文化、数字监控、黑客档案、 gritty 复古科技感为基调，画面带有监控录像、人脸比对与地下杂志的混合气质。
- **背景处理**：使用暗色调（黑色或深灰）背景，叠加噪点、扫描线、数字 glitch 或细微纹理，模拟监控屏幕或老旧数字显示器。
- **主体布局**：中央放置一张主体全身或半身照片，作为画面核心；画面中不规则分布多个参差布局的带彩色边框（红/蓝为主）的小视窗截图，呈现主体局部或不同角度。
- **线框系统**：用红色或蓝色矩形线框标记主体身体部位或关键区域，线框可带编号标签，形成监控识别与数据标注感。
- **文字元素**：使用等宽字体、无衬线字体或街头涂鸦字体，排布模拟数据字段：NAME、ID、STATUS、TIME、CODE、GROUP、SHOT BY、DESIGN BY 等；文字颜色以白、红、蓝为主。
- **顶部/底部信息条**：顶部可加入类似监控界面信息（CAMERA X.X、时间码），底部加入署名/制作信息，强化档案界面感。
- **质感强化**：添加轻微颗粒、扫描线、低比特色带、文字错位或 CRT 显示器光晕，增强数字复古氛围。

## 工作流程
1. 接收原始图片，识别主体姿态与可截取局部。
2. 设置深色噪点背景，加入细微扫描线或 glitch 纹理。
3. 中央放置主体主图，画面中参差不规则位置分布带红/蓝边框的小视窗局部图。
4. 在主体上叠加红/蓝矩形标注线框与编号标签。
5. 顶部加入监控信息条与标题/Logo，底部加入署名信息“Shift Design”。
6. 排布数据字段文字，使用等宽/无衬线/街头字体。
7. 添加颗粒、扫描线、色带等数字复古质感。
8. 输出为竖版或按原图比例适配。

## 关键约束
- 必须使用深色噪点背景与监控界面式信息条。
- 必须有红/蓝彩色边框的小视窗与主体标注线框。
- 文字需包含模拟数据字段与署名信息，字体需带有街头/科技感。
- 必须添加噪点、扫描线或 glitch 等数字复古质感。
- 整体风格 gritty、街头、亚文化，避免干净商业感。
