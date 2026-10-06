# Borozdov Recess

A theme from the Borozdov collection. Two faces — light **Schoolyard**, a schoolyard
notebook on cream paper in soft afternoon light, and dark **Homework**, the same notebook at
the desk after dark. Rounded lowercase headlines, charcoal ink, outlined pills and a marker-
orange underline.

![Borozdov Recess in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/recess/main/screenshots/light.png)

![Borozdov Recess in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/recess/main/screenshots/dark.png)

## Principles

- **A child's notebook at full volume.** The title and the largest heading in Recess Sans
  Bold, in lowercase with normal tracking; the platform's own sans for everything else.
- **Charcoal is the only ink.** Text, borders and button strokes are charcoal, headlines a
  warm cocoa; buttons are never filled, only outlined.
- **A marker in the margin.** Marker orange is the highlighter swipe across the lower part
  of the words, a checked task, the caret and the quote rule; burnt sienna carries links.
- **Name labels.** Tags, the open file and the plain note look like sticker-laminated name
  labels: white, a charcoal outline, pill corners.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- The highlighter as a marker swipe across the lower part of the words
- Tags as sticker-laminated name labels
- Callouts as dew-drop cards; the plain note as a white label with a charcoal outline
- Buttons as outlined pills; the main one draws its outline thicker
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory, as a variant:** this theme ships inside **Borozdov
Palette**. Install Borozdov Palette under Settings → Appearance → Themes → Manage, then
the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin, and
choose **Recess** under Style Settings → Borozdov Palette → Variant. The variant brings
this theme's palette, type and corners; its own layout, and its embedded font if it has
one, come with the full theme below.

**The full theme, by hand:** download `manifest.json` and `theme.css` from the [latest
release](https://github.com/borozdov-obsidian-themes/recess/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Recess/`, then choose Borozdov Recess under Settings →
Appearance → Themes.

## Font

Recess Sans is embedded in `theme.css` as base64 WOFF2 under the SIL Open Font License
1.1 — see [`fonts/OFL.txt`](fonts/OFL.txt). It is a Latin and Cyrillic subset of Comfortaa
Bold (© 2011 The Comfortaa Project Authors), renamed because a modified copy may not use the
original's Reserved Font Name. One weight, for the title and the two largest headings only.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «Школьный двор» — школьная
тетрадь на кремовой бумаге в мягком дневном свете, и тёмный «Домашка» — та же тетрадь за
столом вечером. Округлые заголовки строчными буквами (Recess Sans), угольные чернила, пилюли
с обводкой и мазок оранжевого маркера. В каталоге тема живёт вариантом Borozdov Palette: установите Borozdov Palette и плагин Style Settings, затем выберите Recess в Style Settings → Borozdov Palette → Variant. Целиком, со своей вёрсткой, тема ставится вручную из последнего релиза репозитория.
