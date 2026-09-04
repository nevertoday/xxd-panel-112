---
name: xxd-panel-112
description: "Create XXD Panel 112 raster artwork by translating a source photograph into a quiet two-layer handmade-paper collage with a narrow irregular colour field, deep matte crayon lines, restrained gold accents, Risograph grain, and generous whitespace. Supports isolated image or directory inputs and strict 50:50 top-bottom or left-right comparisons, design-only work, and wallpapers. Use when the user invokes xxd-panel-112 or asks for this gold-accented paper-collage style."
---

# XXD Panel 112

Create finished PNG artwork from the current user-supplied photograph or image directory. Read `references/original-prompt/zh-CN.md` completely immediately before every generation. That Chinese source brief is the sole creative and aesthetic authority; never summarise, translate, blend, or replace it with this file, a README, a sample, or another Panel.

## Delivery contract

- One source photograph produces its own isolated outputs. Never combine source photographs or reuse another source's subject, wording, or result.
- The canonical presentation is a 3:4 portrait canvas with reality above and the paper-collage transformation below, exactly 50:50.
- Support `top-bottom`, `left-right`, `design-only`, and `wallpaper-pack`. Comparison modes always have exactly two equal regions: reality above or left, design below or right. Never add a header, footer, inset panel, grid, or third band.
- A directory is explicit batch intent. Inventory supported raster files in stable order, report the count, resolve shared settings once, generate each source independently, and account for every success and failure.
- Resolve mode(s), size(s), text mode, locale, wallpaper relationship, device sizes, and output root before generation. Do not infer a silent ratio or locale.

## Prompt authority

For each output, concatenate the complete verbatim Chinese source brief, then a short delivery preamble, exactly one selected mode contract, exactly one text contract, and only the user's explicit non-style requirements. Runtime additions may change delivery variables only. Never add an outer palette, title, slogan, or aesthetic theory.

Text modes are `prompt`, `exact`, and `none`. Resolve the target locale explicitly. Exact text is passed verbatim; text-free output contains no letters, numbers, logos, labels, or pseudo-text. In prompt text mode, preserve the source brief's specific requirement for small handwritten English phrases unless the user explicitly overrides it.

Prefer the built-in image tool and make one complete-canvas generation per distinct output. Never feed an intermediate stylisation, another Panel's result, or a sample back through a second transformation pass. If no compatible image route is available, ask the user to enable one or voluntarily provide an API key; never expose secrets. Use `scripts/compose_panel.py` only for exact raster sizing, pixel-preserving composition, or read-only audits, never to invent the design.

## Output and acceptance

Write final PNGs directly inside one fresh task directory under `~/Desktop/xxd/xxd-panel-112/` or the explicit output root. Use collision-safe filenames; do not create source, mode, or size subdirectories and do not generate an automatic contact sheet.

Inspect every result at full and thumbnail size. Accept only when the source, ratio, source visibility, split direction, and exact 50:50 midpoint are correct; the transformed region follows the two-layer handmade-paper brief directly from the current source; text follows the chosen mode and locale; and there is no watermark, SVG substitute, UI, third band, or second-pass artefact.

For linked wallpapers, create one anchor from the original source, then independently recompose each remaining device using the original source plus that anchor. Independent wallpapers receive only the original source.

## References

- `references/original-prompt/zh-CN.md` — canonical runtime brief
- `references/original-prompt/README.md` — translation index and authority note
- `references/runtime-preferences.md` — safe delivery-preference reuse
- `references/xxd-panel-112-prompt.zh-CN.md` and `.en.md` — delivery adapter notes
