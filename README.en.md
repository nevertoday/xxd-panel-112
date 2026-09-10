<div align="center">

# XXD Panel 112｜Gold-Line Paper Chronicle

Let an irregular field of paper hold one quiet, glimmering memory.


<a href="README.md">简体中文</a> · <strong>English</strong> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

## 16:9 Left–Right Samples

Four independent sources on complete 16:9 canvases: reality left, this Panel's design right, exact 50:50. English copy is generated from each photograph.

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-05.png" alt="XXD Panel 112 Sample 5"></td>
    <td width="50%"><img src="./assets/examples/sample-06.png" alt="XXD Panel 112 Sample 6"></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-07.png" alt="XXD Panel 112 Sample 7"></td>
    <td width="50%"><img src="./assets/examples/sample-08.png" alt="XXD Panel 112 Sample 8"></td>
  </tr>
</table>

## 3:4 Top–Bottom Samples

Four further independent sources, different from the 16:9 set, regenerated as complete 3:4 top–bottom canvases. The original photograph remains above; the lower design follows this Panel's original brief.

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-09.png" alt="XXD Panel 112 additional top-bottom sample 1"></td>
    <td width="50%"><img src="./assets/examples/sample-10.png" alt="XXD Panel 112 additional top-bottom sample 2"></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-11.png" alt="XXD Panel 112 additional top-bottom sample 3"></td>
    <td width="50%"><img src="./assets/examples/sample-12.png" alt="XXD Panel 112 additional top-bottom sample 4"></td>
  </tr>
</table>


## Best-fit situations and problems solved

Some photographs need less visual noise and a paper field capable of holding one memory. **Panel 112** keeps the photographic reality and compresses the other half into off-white handmade paper, a narrow horizontal colour field, a small wax-crayon seal, and a few gold lines. It suits quiet portraits, travel fragments, plants and objects, literary covers, private keepsakes, and exhibitions.

It addresses paper styles that turn muddy and heavy, gold that becomes flashy, stiff full-scene tracing, and compositions filled edge to edge with colour blocks and decoration.

## Usage tips

- **Start with one clear photo:** choose a source whose subject, action, and relationships are easy to recognize before choosing the delivery format.
- **Join the parameters in one sentence:** say “top-bottom / left-right / design-only + 16:9 / 3:4 / phone wallpaper”; you can also name desktop, tablet, or smartwatch sizes.
- **State what must stay:** identify the people, objects, actions, relationships, and copy to preserve, while leaving room for the style to design the layout.
- **Choose a text mode:** let the model write from the image, lock exact wording with `--text exact --copy`, or remove text completely with `--text none`.
- **Clarify reality and design regions:** for top-bottom or left-right, say which region keeps the photograph and which region is redesigned; for design-only and wallpapers, say that the whole canvas is redesigned.
- **Test one image before batching:** confirm mode, ratio, text, and language on one source, then reuse the settings for a folder; change one variable per iteration.

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

## Original prompt · five languages

[简体中文](references/original-prompt/zh-CN.md) · [English](references/original-prompt/en.md) · [日本語](references/original-prompt/ja.md) · [한국어](references/original-prompt/ko.md) · [العربية](references/original-prompt/ar.md)

The Chinese file preserves the original prompt verbatim and is the sole runtime creative authority; the other four files are complete, faithful reading translations.

**Signature:** double-layer handmade paper · narrow irregular horizontal field · deep matte crayon line · restrained gold line · small seal-like subject · boundary-crossing whitespace · Risograph grain

## Quick fit check

| What you need | What Panel 112 gives you |
|---|---|
| A quiet, vintage paper poster without heaviness? | Warm off-white paper, dark wax-crayon lines, and a few gold accents hold one memory. |
| A recognisable subject without a full redraw? | Structure and atmosphere are distilled into a small seal inside a narrow central field. |
| Gold that stays refined rather than flashy? | Gold marks only key contours; generous blank space and no heavy shadows keep it restrained. |

## Full capabilities and boundaries

Supports the four modes above, multiple ratios or exact pixels, prompt-generated/exact/no text, directory batches, and linked or independent four-device wallpapers. A directory is recursively inventoried, reported once, and processed source by source. Every final PNG goes directly into one fresh task directory. Generate one complete canvas per output; never feed an intermediate, sample, or another Panel's result through a second transformation. `compose_panel.py` is only a lossless sizing/split fallback or audit tool.

## Text and language

Resolve the visible-text locale explicitly. `prompt` follows the brief's sparse handwritten-English logic, `exact` passes user copy verbatim, and `none` forbids letters, numbers, logos, and pseudo-text. The Skill never invents a title or guesses language from a person, place, or filename.

## Four output modes

- `top-bottom`: reality above and Panel 112 design below, exactly 50% each.
- `left-right`: reality left and design right, exactly 50% each; never rotate it into a top-bottom layout.
- `design-only`: the full canvas shows only this Panel’s design translation; the photo is reference only.
- `wallpaper-pack`: generate a complete canvas independently for each device.

<!-- xxd-panel-catalog:start -->
## XXD Panel catalogue

Each of the 112 Panels keeps its own original prompt and aesthetic logic. This directory lists every project continuously from 001 to 112; the current project is bold.

| Project | Style |
|---|---|
| [xxd-panel-001](https://github.com/nevertoday/xxd-panel-001) | NAÏVE LINE · RETRO PAPER · MIXED MEDIA · WITTY METAPHOR · WARM SPACE |
| [xxd-panel-002](https://github.com/nevertoday/xxd-panel-002) | NARRATIVE CONTOUR · HESITANT LINE · ANALOGOUS COLOUR · SELECTIVE ENLARGEMENT · MISREGISTERED TYPE |
| [xxd-panel-003](https://github.com/nevertoday/xxd-panel-003) | CONTINUOUS BLACK LINE · PUBLIC ISSUE · FORCE POINTS · SILENT SPACE · RELEASE |
| [xxd-panel-004](https://github.com/nevertoday/xxd-panel-004) | LOCAL REALITY · PRECISE SINGLE LINE · GEOMETRIC PERSPECTIVE · THEME COLOUR · CITY-BRAND TYPE |
| [xxd-panel-005](https://github.com/nevertoday/xxd-panel-005) | BLUNT MASSES · DARK STRUCTURAL FIELD · PARTIAL REVEAL · THREE-LAYER COLOUR · SCREENPRINT × PASTEL |
| [xxd-panel-006](https://github.com/nevertoday/xxd-panel-006) | 10–20% SUBJECT · 80–90% PAPER · FINE HAND LINE · FOUR COLOURS MAX · FLAT ACRYLIC |
| [xxd-panel-007](https://github.com/nevertoday/xxd-panel-007) | OBJECT-LIKE MINIATURES · CLOSE-UP / SECTION / REPEAT · STAGGERED PAPER · THIN BLACK NOTES |
| [xxd-panel-008](https://github.com/nevertoday/xxd-panel-008) | ORTHOGRAPHIC ISOMETRIC · PLATFORMS / STAIRS / DOORS · SPATIAL PARADOX · DYNAMIC PASTELS · MATTE 3D |
| [xxd-panel-009](https://github.com/nevertoday/xxd-panel-009) | TINY ANCHOR · VAST NEGATIVE SPACE · ONE SPATIAL RELATION · SPOT COLOUR · HALFTONE SCREENPRINT |
| [xxd-panel-010](https://github.com/nevertoday/xxd-panel-010) | ROUGH BLACK SILHOUETTE · WHITE FEATURE CUTOUT · DRY-MEDIA PAPER · SPARSE SETTING MARKS · PICTURE-BOOK TYPE |
| [xxd-panel-011](https://github.com/nevertoday/xxd-panel-011) | ONE CORE IMAGE · ONE RELATION · CONTINUOUS BLACK LINE · ACTIVE SILENCE · ONE MEMORY COLOUR |
| [xxd-panel-012](https://github.com/nevertoday/xxd-panel-012) | DENSE EMERGENCE · SPARSE DIFFUSION · GEOMETRIC RESTRAINT · ONE VITAL COLOUR · BLACK-GREY MICROTYPE |
| [xxd-panel-013](https://github.com/nevertoday/xxd-panel-013) | ONE HORIZONTAL TICKET · 74/26 SPLIT · HEALING WATERCOLOUR · IVORY SPACE · LOCALISED INFORMATION STUB |
| [xxd-panel-014](https://github.com/nevertoday/xxd-panel-014) | FOLD AND FACET · LAYER AND NEST · SOURCE-LED WEIGHT · REAL PAPER FIBRE · READABLE PAPER TYPE |
| [xxd-panel-015](https://github.com/nevertoday/xxd-panel-015) | DECONSTRUCT–SELECT–DISTIL–RECONSTRUCT · FEW FORMS · STRICT COLOUR ROLES · IVORY SPACE · ART-BOOK MICROTYPE |
| [xxd-panel-016](https://github.com/nevertoday/xxd-panel-016) | ONE SUBJECT · ONE MOTION · A LARGE FIELD OF AIR |
| [xxd-panel-017](https://github.com/nevertoday/xxd-panel-017) | ROUNDED FORM · ROUGH BROKEN LINE · PURE FLAT FILL · BRIGHT FIELDS · LIVELY ASYMMETRY |
| [xxd-panel-018](https://github.com/nevertoday/xxd-panel-018) | ONE VISUAL ANCHOR · FEW DEPTH LAYERS · WARM-IVORY SPACE · MATTE PAPER · COMPLETE MICROTYPE |
| [xxd-panel-019](https://github.com/nevertoday/xxd-panel-019) | RECOGNISE FIRST · REDUCE WITH INTENT · COMPOSE WITH TYPE |
| [xxd-panel-020](https://github.com/nevertoday/xxd-panel-020) | IMPASTO ISLAND · DIMENSIONAL MINIATURE · REAL KNIFE MARKS · GENEROUS PAPER SPACE · RESTRAINED EDITORIAL TYPE |
| [xxd-panel-021](https://github.com/nevertoday/xxd-panel-021) | PURE-BLACK RECTANGLE · SUBJECT MOSTLY INSIDE · ONE FEATURE BREAKS OUT · JITTERY PHOTOCOPY LINE · WHITE NEGATIVE FORM |
| [xxd-panel-022](https://github.com/nevertoday/xxd-panel-022) | PURE-BLACK RECTANGLE · SUBJECT MOSTLY INSIDE · ONE FEATURE BREAKS OUT · CLEAN ELASTIC LINE · ONE COLOUR SIGNAL |
| [xxd-panel-023](https://github.com/nevertoday/xxd-panel-023) | SOURCE-CHOSEN WINDOW · PALE BREATHING GROUND · LIVING COLOURED LIGHT · SPRAY GRAIN · DIFFUSE PROJECTION |
| [xxd-panel-024](https://github.com/nevertoday/xxd-panel-024) | PHOTOGRAPHIC SUBJECT · NARROW PALE WINDOW · SOURCE-ADAPTIVE DIRECTION · EASTERN WHITESPACE · PREMIUM EDITORIAL TYPE |
| [xxd-panel-025](https://github.com/nevertoday/xxd-panel-025) | FIRST-GLANCE SUBJECT · SECOND-GLANCE IMAGE · FIGURE–GROUND REVERSAL · 2–4 MORANDI COLOURS · PHYSICAL SCREENPRINT |
| [xxd-panel-026](https://github.com/nevertoday/xxd-panel-026) | RECOGNISE QUIETLY · REDUCE GENTLY · LET THE PAPER BREATHE |
| [xxd-panel-027](https://github.com/nevertoday/xxd-panel-027) | HEAVY IVORY PAPER · EMBOSS AND DEBOSS · FINE INCISION · MATTE-GOLD FOCUS · MUSEUM ORDER |
| [xxd-panel-028](https://github.com/nevertoday/xxd-panel-028) | ORTHOGRAPHIC ISOMETRIC · SMALL PAPER BASE · SOURCE-DERIVED PALETTE · FINE INK · EDITORIAL MODEL |
| [xxd-panel-029](https://github.com/nevertoday/xxd-panel-029) | HORIZONTAL FIELD · LIGHT WAX PASTEL · ROUGH HANDMADE PAPER · RISOGRAPH GRAIN · RELAXED HANDWRITING |
| [xxd-panel-030](https://github.com/nevertoday/xxd-panel-030) | REAL BOTANICAL MATERIAL · RECTANGULAR FIELD · NATURAL CROSSING · MINIMAL BLACK LINE · EDITORIAL WHITESPACE |
| [xxd-panel-031](https://github.com/nevertoday/xxd-panel-031) | ONE CORE MOTIF · SOURCE-DERIVED GEOMETRY · FOLK CATALOGUE · ROUGH INTERNAL INK · CRISP ORDER |
| [xxd-panel-032](https://github.com/nevertoday/xxd-panel-032) | TEXT–IMAGE UNITY · NATIVE LETTERING · SOURCE FEATURE · OPTICAL SPACING · GENEROUS WHITESPACE |
| [xxd-panel-033](https://github.com/nevertoday/xxd-panel-033) | RECOGNISABLE MOTIF · LAYERED COLLAGE · SCALE CONTRAST · VIVID SOURCE COLOUR · COVER TYPE |
| [xxd-panel-034](https://github.com/nevertoday/xxd-panel-034) | SMALL STAMP · 2–4 SPOT INKS · HAND-CARVED LINE · WARM PAPER · FIELD ANNOTATION |
| [xxd-panel-035](https://github.com/nevertoday/xxd-panel-035) | ONE BLOCK SUBJECT · VIVID SOURCE COLOUR · MATTE ABS · QUIET FIELD · MODULAR TYPE |
| [xxd-panel-036](https://github.com/nevertoday/xxd-panel-036) | ONE RELATION · FINE LINE · 2–4 COLOUR FIELDS · WATERCOLOUR EDGE · BREATHING SPACE |
| [xxd-panel-037](https://github.com/nevertoday/xxd-panel-037) | ONE BADGE · SOURCE ENAMEL · WHITE-METAL RIM · GILDED DETAIL · REAL SHADOW |
| [xxd-panel-038](https://github.com/nevertoday/xxd-panel-038) | SOURCE FABRIC · FRAYED EDGE · HAND STITCH · ACTIVE WHITESPACE · HIDDEN FEELING |
| [xxd-panel-039](https://github.com/nevertoday/xxd-panel-039) | ONE IMAGE · ONE ESSENCE · SILK DIRECTION · CLEAN GROUND · EASTERN SILENCE |
| [xxd-panel-040](https://github.com/nevertoday/xxd-panel-040) | TRUTHFUL ANCHOR · BLACK-LINE FIGURES · MICRO-NARRATIVE · ACTIVE WHITESPACE |
| [xxd-panel-041](https://github.com/nevertoday/xxd-panel-041) | THEME METAPHOR · ISOMETRIC ORDER · PALE MANUSCRIPT · JAPANESE COLOUR · EASTERN SPACE |
| [xxd-panel-042](https://github.com/nevertoday/xxd-panel-042) | ORIGINAL VIEW · 2–5 TRUE LAYERS · STABLE ANCHOR · TRANSLUCENT WATERCOLOUR · EDITORIAL NOTE |
| [xxd-panel-043](https://github.com/nevertoday/xxd-panel-043) | REAL LATHER · FRONTAL FLAT-LAY · SOURCE-DARK GROUND · MICRO-BUBBLE EDGE · QUIET SPACE |
| [xxd-panel-044](https://github.com/nevertoday/xxd-panel-044) | THIN GOLD · FRONTAL PLANE · SOURCE-DARK GROUND · HAMMERED TRACE · QUIET ORDER |
| [xxd-panel-045](https://github.com/nevertoday/xxd-panel-045) | ROUNDED MODULE · SOURCE COLOUR · ISOMETRIC DEPTH · MATTE TOUCH · EDITORIAL MICROTYPE |
| [xxd-panel-046](https://github.com/nevertoday/xxd-panel-046) | BRIGHT GROUND · VIVID IMPASTO · MINIATURE VOLUME · DIAGONAL FIELD · WARM LIGHT |
| [xxd-panel-047](https://github.com/nevertoday/xxd-panel-047) | ISOMETRIC MINIATURE · THEMATIC IMPASTO · REAL CONTACT · WARM-WHITE PAPER · LUMINOUS COLOUR |
| [xxd-panel-048](https://github.com/nevertoday/xxd-panel-048) | TRANSPARENT STRUCTURE · SCIENTIFIC ILLUSTRATION · LUCID MONOCHROME · PRECISE ANNOTATION · EDITORIAL SPACE |
| [xxd-panel-049](https://github.com/nevertoday/xxd-panel-049) | LIMITED-COLOUR WOODCUT · HAND-CARVED MARKS · MATTE INK · WARM PAPER · BROKEN EDGES |
| [xxd-panel-050](https://github.com/nevertoday/xxd-panel-050) | BESPOKE TRAVEL SCENE · AIRY BLUE · MINIMAL FLAT VECTOR · EDITORIAL WHITESPACE · ONE IMAGE, ONE IDENTITY |
| [xxd-panel-051](https://github.com/nevertoday/xxd-panel-051) | MINIATURE PAPER CRAFT · HORIZONTAL FLOATING LANDSCAPE · HANDMADE EVIDENCE · AIRY BLUE · VAST WHITESPACE |
| [xxd-panel-052](https://github.com/nevertoday/xxd-panel-052) | PAPER-CRAFT MINIATURE · HORIZONTAL FLOATING STRIP · HANDMADE MATERIAL · AIRY COOL BLUE · GENEROUS SPACE |
| [xxd-panel-053](https://github.com/nevertoday/xxd-panel-053) | OBSERVATIONAL PEN · TRANSPARENT WASH · MUSICAL RHYTHM · NEAR-WHITE PAPER · ACTIVE WHITESPACE |
| [xxd-panel-054](https://github.com/nevertoday/xxd-panel-054) | SELECTIVE MEMORY · MAIN VISUAL · SIX STICKERS · MATTE PRINT · AIRY BLUE |
| [xxd-panel-055](https://github.com/nevertoday/xxd-panel-055) | SUBJECT NARRATIVE · HEALING PASTELS · LIGHT OIL TEXTURE · AIRY BLUE · EDITORIAL SPACE |
| [xxd-panel-056](https://github.com/nevertoday/xxd-panel-056) | CORE IMAGE · VAST WHITESPACE · WARM–COOL JUMPS · NAIVE HAND · VISUAL METAPHOR |
| [xxd-panel-057](https://github.com/nevertoday/xxd-panel-057) | GEOMETRIC COMPOSITION · INTELLIGENT MOSAIC · ARCHITECTURAL DIAGRAM · ART MAP · WARM–COOL FIELDS |
| [xxd-panel-058](https://github.com/nevertoday/xxd-panel-058) | SUBTEXT READING · GEOMETRIC MINIMALISM · CONCEPTUAL LANDSCAPE · SOFT HANDMADE TEXTURE · PALE SPACE |
| [xxd-panel-059](https://github.com/nevertoday/xxd-panel-059) | HAND-DRAWN STORYTELLING · CHILDLIKE METAPHOR · WARM PAPER · GENTLE HUMOUR · POETIC ASIDE |
| [xxd-panel-060](https://github.com/nevertoday/xxd-panel-060) | BLACK PRIMARY FORM · IMMENSE NEGATIVE SPACE · HALFTONE DISSOLUTION · ZEN REFLECTION · FRAGMENTS OF THOUGHT |
| [xxd-panel-061](https://github.com/nevertoday/xxd-panel-061) | SELECTIVE MEMORY · 3–6 FRAGMENTS · CUT-PAPER COLOUR · RISOGRAPH · IMPROVISED EDITORIAL LAYOUT |
| [xxd-panel-062](https://github.com/nevertoday/xxd-panel-062) | MINIMAL BLACK LINE · ONE ACCENT COLOUR · CLEVER AWKWARDNESS · PALE PAPER · PROFESSIONAL WHITESPACE |
| [xxd-panel-063](https://github.com/nevertoday/xxd-panel-063) | CORE MASK · PIXEL FORMS · NESTED NEGATIVE SPACE · SUBTLE GLITCH · LIMITED PALETTE |
| [xxd-panel-064](https://github.com/nevertoday/xxd-panel-064) | TORN PAPER · AGED COLLAGE · PENCIL AND INK · TYPEWRITER MICROCOPY · POETIC ARCHIVE |
| [xxd-panel-065](https://github.com/nevertoday/xxd-panel-065) | BLACK STRUCTURE · TWO SOURCE-COLOUR LINES · MISREGISTRATION · VINTAGE PRINT RHYTHM · MICROTYPE |
| [xxd-panel-066](https://github.com/nevertoday/xxd-panel-066) | CHILDLIKE NARRATIVE · AWKWARD BLACK LINE · 3–6 FLAT COLOURS · HEALING PALETTE · HANDWRITTEN OBSERVATION |
| [xxd-panel-067](https://github.com/nevertoday/xxd-panel-067) | FIXED RED–BLUE INK · HAND-DRAWN DUAL INK · CHILDLIKE HUMOUR · EVERYDAY OBSERVATION · PALE PAPER |
| [xxd-panel-068](https://github.com/nevertoday/xxd-panel-068) | CHINESE XIEYI PLACEMENT · WHITE AS INK · INK LINE AND PALE COLOUR · INSCRIPTION TYPE · MODERN EDITORIAL |
| [xxd-panel-069](https://github.com/nevertoday/xxd-panel-069) | BROAD-BRUSH WINDOW · VITAL SOURCE COLOUR · FINE CONTOURS · BOUNDARY CROSSINGS · WARM-WHITE SPACE |
| [xxd-panel-070](https://github.com/nevertoday/xxd-panel-070) | HAND-DRAWN CONTOURS · BRIGHT IMPASTO／TRANSLUCENT COLOUR · MINIATURE SUBJECT · WARM-WHITE SPACE · TYPEWRITER EDITORIAL TYPE |
| [xxd-panel-071](https://github.com/nevertoday/xxd-panel-071) | SOFT PASTEL · PASTEL CRAYON · SOLUBLE PENCIL · NEAR-WHITE PAPER · FLOATING MEMORIES · POETIC HANDWRITING |
| [xxd-panel-072](https://github.com/nevertoday/xxd-panel-072) | TRANSLUCENT FROSTED WINDOWS · REGIONAL SOFT FOCUS · MINIMAL GEOMETRY · RECOGNISABLE SILHOUETTE · MODERN TYPE |
| [xxd-panel-073](https://github.com/nevertoday/xxd-panel-073) | ISOMETRIC MINIATURE ARCHITECTURE · CUT CUBE · CONTINENTAL-SHELF SECTION · RATIONAL SCAFFOLDING · TEXTURED PAPER |
| [xxd-panel-074](https://github.com/nevertoday/xxd-panel-074) | STANDARD ROUNDED SQUARE · FRONT PSEUDO-3D／2.5D · SOURCE-SOUL EXTRACTION · MATTE SCULPTURE · BRAND ICON |
| [xxd-panel-075](https://github.com/nevertoday/xxd-panel-075) | DARK CRAYON · IVORY HANDMADE PAPER · SOFT IRREGULAR FIELD · RISOGRAPH GRAIN · WHITESPACE · PRIVATE TYPEWRITER NOTE |
| [xxd-panel-076](https://github.com/nevertoday/xxd-panel-076) | ROUGH DARK CRAYON · CHARCOAL · BRIGHT MACARON BLOCKS · 45% CONTINUOUS WHITESPACE · NATURAL PAPER · OBSERVATION NOTES |
| [xxd-panel-077](https://github.com/nevertoday/xxd-panel-077) | MINIMAL PAPER SCULPTURE · CLEAR CUT-PAPER CONTOUR · LAYERED PLANES · SOFT SHADOW · HUMANIST MACARON · TRAVEL EDITORIAL |
| [xxd-panel-078](https://github.com/nevertoday/xxd-panel-078) | IVORY COTTON PAPER · DEEP DEBOSS · RECESSED CHAMPAGNE FOIL · FINE-LINE MARK · BLIND PRESSURE · UNDERSTATED LUXURY |
| [xxd-panel-079](https://github.com/nevertoday/xxd-panel-079) | GEOMETRIC STRAIGHTS · FREE ORGANIC CURVES · PEN AND WASH · UNFINISHED QUALITY · BROAD PAPER WHITE · EDITORIAL TYPE |
| [xxd-panel-080](https://github.com/nevertoday/xxd-panel-080) | SOFT ORGANIC GEOMETRY · DIGITAL GOUACHE · CRAYON GRAIN · BOTANICAL COLOUR · SOURCE-BORN METAPHOR · EMOTIONAL SPACE |
| [xxd-panel-081](https://github.com/nevertoday/xxd-panel-081) | EVEN-WEIGHT COLOURED MONOLINE · OPEN CONTOUR · DENSITY HIERARCHY · 2–4 SPOT INKS · RISOGRAPH GRAIN · KEEPSAKE NARRATIVE |
| [xxd-panel-082](https://github.com/nevertoday/xxd-panel-082) | IRREGULAR WATERCOLOUR FIELD · NAÏVE + WONKY · ISOMETRIC／2.5D · CHILDLIKE CONTOUR · VIVID COLOUR · SPATIAL PROTAGONIST |
| [xxd-panel-083](https://github.com/nevertoday/xxd-panel-083) | UGLY-CUTE DOODLE · WONKY TREMBLING CONTOUR · CONTROLLED WRONGNESS · ONE COMIC PROTAGONIST · ROUGH CRAYON · SPARSE-STRANGE-CLUMSY-ACCURATE |
| [xxd-panel-084](https://github.com/nevertoday/xxd-panel-084) | MINIMAL URBAN LINEWORK · GEOMETRIC SCAFFOLD · DENSITY-BASED STIPPLING · LEADING LINES · RESTRAINED COLOUR · POETIC WHITESPACE |
| [xxd-panel-085](https://github.com/nevertoday/xxd-panel-085) | HANDMADE MINIATURE STAGE · COLLECTIBLE DIMENSIONAL COVER · CLAY AND FELT · CUT PAPER AND STRING · MATTE TACTILITY · ARTFUL WHITESPACE |
| [xxd-panel-086](https://github.com/nevertoday/xxd-panel-086) | mid-century modernist limited-colour screen print · silhouette geometry · 2–4 spot inks · dry-brush drag · one focus · generous whitespace |
| [xxd-panel-087](https://github.com/nevertoday/xxd-panel-087) | physical pin-and-string relationship map · vermilion thread · emergent geometry · handwritten notes · research-wall whitespace |
| [xxd-panel-088](https://github.com/nevertoday/xxd-panel-088) | experimental typographic image · text as image · deconstructed type · dot-matrix contour · density gradient · visual poetry |
| [xxd-panel-089](https://github.com/nevertoday/xxd-panel-089) | personal life-journal vignette · one protagonist · a few daily fragments · loose hand line · watercolour and coloured pencil · mature whitespace |
| [xxd-panel-090](https://github.com/nevertoday/xxd-panel-090) | schematic visual thinking map · concept centre · text nodes · geometric scaffold · trajectory arrows · visual notation · generous whitespace |
| [xxd-panel-091](https://github.com/nevertoday/xxd-panel-091) | monochrome blue-pen narrative sketch · cobalt／pen blue／ultramarine／indigo · directional hatching · searching lines · natural paper white |
| [xxd-panel-092](https://github.com/nevertoday/xxd-panel-092) | Expressive pen · loose contours · geometric and scribble hatching · negative-space composition |
| [xxd-panel-093](https://github.com/nevertoday/xxd-panel-093) | Independent original aesthetic · photo-grounded transformation · flexible multi-format delivery |
| [xxd-panel-094](https://github.com/nevertoday/xxd-panel-094) | Fine pen-and-ink · selective solid black · source-derived spot colour · vast negative space · vintage book illustration |
| [xxd-panel-095](https://github.com/nevertoday/xxd-panel-095) | Independent original aesthetic · photo-grounded transformation · flexible multi-format delivery |
| [xxd-panel-096](https://github.com/nevertoday/xxd-panel-096) | Independent original aesthetic · photo-grounded transformation · flexible multi-format delivery |
| [xxd-panel-097](https://github.com/nevertoday/xxd-panel-097) | Mid-century vernacular commercial graphic · schematic line drawing · two-colour spot printing · functional humour |
| [xxd-panel-098](https://github.com/nevertoday/xxd-panel-098) | faux-naïve watercolour picture-book illustration · loose ink line · flat watercolour／gouache · symbolic form · innocent perspective · mature narrative composition |
| [xxd-panel-099](https://github.com/nevertoday/xxd-panel-099) | flat vector brand mascot · bold black contour · rounded geometry · exaggerated proportion · 2–4 branded colours · oversized type background |
| [xxd-panel-100](https://github.com/nevertoday/xxd-panel-100) | naïve folk-inspired flat narrative · primitive forms · simplified silhouettes · flattened perspective · crayon／oil-pastel grain · warm paper · vivid limited colour |
| [xxd-panel-101](https://github.com/nevertoday/xxd-panel-101) | 3×3 memory icons · private-journal feeling · naïve doodles · retro candy colour · handwritten notes |
| [xxd-panel-102](https://github.com/nevertoday/xxd-panel-102) | soothing geometry · soft shapes · flat composition · warm healing colour · easy negative space |
| [xxd-panel-103](https://github.com/nevertoday/xxd-panel-103) | vivid abstract assembly · large colour blocks · abstract disassembly and recombination · bright palette · bold rhythm |
| [xxd-panel-104](https://github.com/nevertoday/xxd-panel-104) | halftone print · coloured linear interventions · one visual centre · contemplative negative space |
| [xxd-panel-105](https://github.com/nevertoday/xxd-panel-105) | intelligent aesthetic selection · one visual centre · poetic minimalist paper collage · monoprint／screen print／Risograph texture · soft limited palette · generous negative space |
| [xxd-panel-106](https://github.com/nevertoday/xxd-panel-106) | pastel pixel memory · 2–4 visual anchors · regular grid · modular colour blocks · local dithering · one visual core · generous negative space |
| [xxd-panel-107](https://github.com/nevertoday/xxd-panel-107) | image-word poetry · readable rebus sentence · modern hand-drawn image words · luminous soft blocks · exact 50:50 pairing · generous whitespace |
| [xxd-panel-108](https://github.com/nevertoday/xxd-panel-108) | contemporary folk paper-cut collage · simplified silhouettes · torn edges · vivid source colour · print texture · generous whitespace |
| [xxd-panel-109](https://github.com/nevertoday/xxd-panel-109) | restrained modernist geometric collage · large modules · soft colour · paper grain · editorial order |
| [xxd-panel-110](https://github.com/nevertoday/xxd-panel-110) | Japanese life-scene atlas · 4–7 factual fragments · acrylic collectible · dynamic routes · healing whitespace |
| [xxd-panel-111](https://github.com/nevertoday/xxd-panel-111) | textile collage chronicle · hand-sewn appliqué · visible stitches · 2–4 fabric colours · small seal · generous whitespace |
| **[xxd-panel-112](https://github.com/nevertoday/xxd-panel-112)** | gold-line paper chronicle · two-layer handmade paper · narrow horizontal field · dark wax-crayon line · restrained gold · Risograph grain |
<!-- xxd-panel-catalog:end -->

<!-- xxd-readme-ads:start -->
## About XXD

XXD is Xiaoxiaodong's abbreviated brand name. This project is created and maintained by [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## Xiaoxiaodong multi-platform membership · CNY 699/year

> **Advertising disclosure:** The QR code, membership, and paid-service links below are XXD promotional information. Scanning or purchasing is entirely optional and does not affect access to this open-source project.

One annual membership unlocks three benefits together: **Knowledge Planet + the XXD Member Prompt Library + membership for all General Skills**. They are included in one membership; no separate purchase is required.

<!-- xxd-panel-command-system:start -->

### How the Skills work together

| Level | Included | What it does |
|---|---|---|
| **General** | [`xxd-panel-all`](https://github.com/xiaoxiaodong-ai/xxd-panel-all) | Detects available numbered Skills, recommends them by image, theme, or use, and organizes multi-style and batch tasks. |
| **Soldier** | `xxd-panel-NNN` | Each numbered Skill follows its own original brief and aesthetic to complete the specific task assigned by the General. |

<!-- xxd-panel-command-system:end -->

### What you receive

1. **One-to-one WeChat AI learning and project support**
   Add Xiaoxiaodong on WeChat via the QR code below to discuss AI learning, tools, and real projects one to one, with practical guidance and answers. Representative questions may be organized into member resources.
2. **A growing member prompt library**
   The [XXD Member Prompt Library](https://vip.xiaoxiaodong.ai/) currently contains about 32,000 prompts and will keep expanding, with a goal of exceeding 100,000.
3. **All General Skills and usage support**
   One membership covers every General Skill, with usage guidance and Q&A when you need help.
4. **Priority for high-need requests**
   Frequently requested, high-need prompts and Skills are reviewed and developed first where appropriate.

### How to join

- [Activate membership on the member website](https://vip.xiaoxiaodong.ai/).
- Or scan the QR code below to add Xiaoxiaodong on WeChat for one-to-one activation support.

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="Contact Xiaoxiaodong" width="280"></a></p>
<!-- xxd-readme-ads:end -->

## License

This project is released under the **PolyForm Noncommercial License 1.0.0**. See [LICENSE](LICENSE) for the complete legal text and <https://polyformproject.org/licenses/noncommercial/1.0.0> for the official page.

- Personal, educational, research, testing, hobby, private-entertainment, and eligible public-interest use is allowed.
- Noncommercial users may use, copy, modify, create derivatives, and distribute, provided they include the license and every `Required Notice:` statement supplied by the author.
- Commercial products, services, paid delivery, selling access, or anticipated commercial use require separate written permission.
- Only the stated copyright and limited patent rights are granted; trademarks, brand names, and sublicensing are not included.
- A written violation notice allows 32 days to restore compliance and take practical corrective action before the license ends.
- The project is provided **as is**, without warranties; users accept the risk to the extent permitted by law.
