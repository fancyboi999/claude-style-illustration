# Claude Style Illustration

**One idea. A few marks.**

Turn an idea into a warm, minimal editorial illustration: a clear metaphor, a few bold marker forms, and room to breathe. An independent Agent Skill inspired by Claude’s visual language. Not affiliated with or endorsed by Anthropic.

[中文](README.zh-CN.md) · [Examples & prompts](examples/README.md) · [Skill](skills/claude-style-illustration/SKILL.md)

<table>
<tr><td><img src="examples/knowledge-growth.png" alt="An open book growing a sprout" width="280"></td><td><img src="examples/clarity.png" alt="A tangled line becoming clear through a ring" width="280"></td><td><img src="examples/06-playco-hand.png" alt="A looping marker hand holding a game controller" width="280"></td></tr>
<tr><td>Let knowledge grow</td><td>Make room for clarity</td><td>Make an idea playable</td></tr>
<tr><td><img src="examples/01-astra.png" alt="A cursor crossing an ivory bridge" width="280"></td><td><img src="examples/02-fable.png" alt="A thread continuing across folded pages" width="280"></td><td><img src="examples/04-memory.png" alt="A bookmark inside a human profile" width="280"></td></tr>
<tr><td>From thought to action</td><td>Carry the thread forward</td><td>Keep the context</td></tr>
</table>

<img src="examples/03-cyber.png" alt="A curved arrow beside an ivory shield" width="280">

Capability with safeguards.

## Install

```sh
npx skills add fancyboi999/claude-style-illustration --skill claude-style-illustration
```

Choose your agent in the installer. This skill requires an image-generation tool and a way to view reference images; installing it does not supply a model, API access, or generation credits. The gallery was made with Codex’s built-in imagegen. Other generation tools may interpret the same instructions differently.

For manual installation, copy the entire `skills/claude-style-illustration/` directory into your agent’s skills directory. Keep its references and license files together.

## Try it

```text
Use claude-style-illustration to draw “let knowledge grow”:
an open book growing a small sprout, muted green background, square, no text.
```

```text
Use claude-style-illustration for an article about making complex work clearer.
A tangled line passes through an ivory ring and opens into a calm curve.
Heather background, 1:1, no text.
```

```text
Use claude-style-illustration to show “make an idea playable”.
A loose looping marker hand holds a simple game controller.
Muted ochre background, square, no text.
```

## What it does

- Translates a theme into one physical object, action, or relationship.
- Reduces the composition to a handful of expressive forms.
- Uses near-black `#141413`, ivory `#FAF9F5`, and one muted background.
- Defaults to square images without text; accepts your palette and aspect ratio.
- Returns the image, final prompt, metaphor, and palette.

The handmade character comes from irregular shapes and changing line width. Sample raster images retain slight texture and color drift; exact three-color pixels are not guaranteed.

## Examples and sources

[Seven examples](examples/README.md) include the original prompts and editorial context. News-inspired illustrations are visual interpretations, not official product artwork or factual diagrams. All displayed images were generated on September 7, 2026.

The installable reference library contains this project’s generated examples. Design lineage is documented through [source links](skills/claude-style-illustration/references/visual-language.md).

## License

Skill text, prompts, and configuration: [MIT](LICENSE).

Project-provided PNG examples: [CC BY 4.0](ASSET-LICENSE.md), to the extent of the publisher’s rights. See that file for attribution and AI-generated-image boundaries. External references retain their own rights.
