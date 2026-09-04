<div align="center">

# XXD Panel 112｜Gold-Line Paper Chronicle

Let an irregular field of paper hold one quiet, glimmering memory.

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)

<a href="README.md">简体中文</a> · <strong>English</strong> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

## Sample works

**16:9 landscape left–right samples**

| sample-05 | sample-06 |
|---|---|
| ![sample-05](assets/examples/sample-05.png) | ![sample-06](assets/examples/sample-06.png) |
| ![sample-07](assets/examples/sample-07.png) | ![sample-08](assets/examples/sample-08.png) |

**3:4 portrait top–bottom samples**

| sample-09 | sample-10 |
|---|---|
| ![sample-09](assets/examples/sample-09.png) | ![sample-10](assets/examples/sample-10.png) |
| ![sample-11](assets/examples/sample-11.png) | ![sample-12](assets/examples/sample-12.png) |

All eight were generated independently from different original references: reality left/design right in landscape and reality above/design below in portrait. They use intelligent English copy and passed the strict 50:50 two-region review.

Some photographs are memorable because of a relationship, texture, or pause rather than information alone. This Panel keeps the reality of the photograph and translates the other half through an independent paper-based visual language for art posters, independent publishing, exhibitions, social content, and design-only outputs.

It addresses image and design talking past each other, over-decoration, weak whitespace, and inconsistent delivery across formats.

## Original prompt · five languages

[简体中文](references/original-prompt/zh-CN.md) · [English](references/original-prompt/en.md) · [日本語](references/original-prompt/ja.md) · [한국어](references/original-prompt/ko.md) · [العربية](references/original-prompt/ar.md)

## Four output modes

- `top-bottom`: reality above and Panel 112 design below, exactly 50% each.
- `left-right`: reality left and design right, exactly 50% each; never rotate it into a top-bottom layout.
- `design-only`: the full canvas shows only this Panel’s design translation; the photo is reference only.
- `wallpaper-pack`: generate a complete canvas independently for each device.

## Getting started

```bash
git clone https://github.com/nevertoday/xxd-panel-112.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-112" ~/.codex/skills/xxd-panel-112
```

You can also install it directly with `npx skills`:

```bash
npx skills add https://github.com/nevertoday/xxd-panel-112 --skill xxd-panel-112
```

The command fetches the GitHub repository and installs the same-named Skill. For a user-level Codex installation, append `--global --agent codex --yes`.

After installation, restart the agent session and invoke `$xxd-panel-112`.

## License

This project is released under the **PolyForm Noncommercial License 1.0.0**. See [LICENSE](LICENSE) for the complete legal text and <https://polyformproject.org/licenses/noncommercial/1.0.0> for the official page.

- Personal, educational, research, testing, hobby, private-entertainment, and eligible public-interest use is allowed.
- Noncommercial users may use, copy, modify, create derivatives, and distribute with the license and required notices.
- Commercial products, services, paid delivery, selling access, or anticipated commercial use require separate written permission.
