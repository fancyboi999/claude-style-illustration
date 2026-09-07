# Claude Style Illustration

**把一个想法，画成几笔就懂的图。**

一个用于生成温暖、克制的编辑插画的 Agent Skill：一个明确隐喻，几笔粗马克笔形状，一块低饱和底色。灵感来自 Claude 的视觉语言；本项目独立制作，与 Anthropic 无隶属或背书关系。

[English](README.md) · [全部示例与提示词](examples/README.md)

<table>
<tr><td><img src="examples/knowledge-growth.png" alt="An open book growing a sprout" width="280"></td><td><img src="examples/clarity.png" alt="A tangled line becoming clear through a ring" width="280"></td><td><img src="examples/06-playco-hand.png" alt="A looping marker hand holding a game controller" width="280"></td></tr>
<tr><td>Let knowledge grow</td><td>Make room for clarity</td><td>Make an idea playable</td></tr>
<tr><td><img src="examples/01-astra.png" alt="A cursor crossing an ivory bridge" width="280"></td><td><img src="examples/02-fable.png" alt="A thread continuing across folded pages" width="280"></td><td><img src="examples/04-memory.png" alt="A bookmark inside a human profile" width="280"></td></tr>
<tr><td>From thought to action</td><td>Carry the thread forward</td><td>Keep the context</td></tr>
</table>

<img src="examples/03-cyber.png" alt="A curved arrow beside an ivory shield" width="280">

Capability with safeguards.

## 安装

```sh
npx skills add fancyboi999/claude-style-illustration --skill claude-style-illustration
```

在安装器中选择你的 Agent。使用环境需要图像生成工具和查看参考图的能力；安装 Skill 本身不会提供模型、API 权限或生成额度。本页示例由 Codex 内置 imagegen 生成，其他绘图工具的效果可能不同。

手动安装时，将 `skills/claude-style-illustration/` 整个目录复制到 Agent 的技能目录，保留其中的参考文件与许可证。

## 试试看

```text
用 claude-style-illustration 画“让知识生长”：
一本打开的书长出小芽，灰绿底，1:1，无文字。
```

```text
用 claude-style-illustration 画“把复杂理顺”：
缠绕的线穿过象牙白圆环后舒展开来，浅紫灰底，1:1，无文字。
```

```text
用 claude-style-illustration 画“把想法，玩起来”：
一只用连续弯线画出的手握着极简游戏手柄，低饱和赭黄底，方图，无文字。
```

## 风格与输出

- 用一个物体、动作或关系表达主题。
- 把画面简化为少量可辨认的形状，保留充足留白。
- 墨黑 `#141413`、象牙白 `#FAF9F5`，加一种低饱和底色。
- 默认方图、无文字；支持指定底色和比例。
- 交付图片、最终提示词、隐喻与配色说明。

手绘感来自不规则形状与粗细变化。示例仍有轻微纹理和色值漂移，不能保证每个像素严格属于三个指定颜色。

## 示例与来源

[七张示例](examples/README.md)记录了完整提示词和新闻语境，均生成于 2026 年 9 月 7 日。新闻插画是原创视觉隐喻，不是产品官方素材或事实示意图。随 Skill 安装的参考库使用本项目生成的图像；[设计来源](skills/claude-style-illustration/references/visual-language.md)通过链接说明。

## 许可

技能文字、提示词和配置采用 [MIT](LICENSE)。本项目 PNG 示例采用 [CC BY 4.0](ASSET-LICENSE.md)，授权范围以发布者所拥有的权利为限；署名方式和 AI 图片边界见该文件。外部参考保留原权利。
