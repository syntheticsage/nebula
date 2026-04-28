# Nebula

A deep-plum Obsidian theme with a warm coral accent and a subtle radial glow. Minimal, focused, and built around typography — Inter for the interface, Newsreader italic for serif emphasis, JetBrains Mono for code.

![Nebula theme screenshot](screenshot.png)

## Highlights

- **Deep plum background** (`#1A1527`) with a layered radial glow — gentle, not noisy
- **Warm coral accent** (`#FF5C45`) used sparingly for active file, links, tags, and callout rails
- **Round accent-filled task checkboxes** with strikethrough on completion
- **Wikilinks** styled with a dashed accent underline; external links get a muted underline that warms on hover
- **Tag pills** in soft-coral, rounded
- **Callouts** with a left accent rail and a subtle gradient top
- **Serif italic emphasis** via Newsreader for in-line `_em_` text and blockquotes
- **Syntax-token palette** for code: coral strings, lavender keywords, cool blue functions
- **Dark and light modes** — light mode is a warm paper tone with a darker coral accent

## Install

### From the community gallery (recommended, once approved)

Settings → Appearance → Manage → Browse → search **Nebula** → Install & use.

### Via BRAT (for early builds)

1. Install the [BRAT](https://github.com/TfTHacker/obsidian42-brat) community plugin.
2. BRAT → Add beta theme → paste this repo's URL.

### Manually

1. Download `manifest.json` and `theme.css` from the latest release.
2. Place them in `<YourVault>/.obsidian/themes/Nebula/`.
3. Settings → Appearance → select **Nebula**.

## Fonts

Nebula uses system fonts by default. For the exact designed look, install these on your OS:

- [Inter](https://rsms.me/inter/) — interface and body text
- [Newsreader](https://fonts.google.com/specimen/Newsreader) — serif italics
- [JetBrains Mono](https://www.jetbrains.com/lp/mono/) — code

The theme does not fetch fonts over the network.

## Customize

Nebula exposes its palette as CSS variables under `.theme-dark` and `.theme-light`. To tweak, drop a snippet in `<vault>/.obsidian/snippets/nebula-overrides.css`:

```css
.theme-dark {
  --nebula-bg-0: #120820;           /* darker background */
  --nebula-accent: #FF8A5B;         /* warmer accent */
  --nebula-glow: #3A1E4D;           /* purple glow */
}
```

Then enable the snippet under Settings → Appearance → CSS snippets.

## Compatibility

- Requires Obsidian **1.4.0** or newer
- Supports both dark and light modes

## Credits

Designed and built by **Yogesh Patil**. All CSS in `theme.css` is original
and does not copy code from other Obsidian themes. Aesthetic direction
inspired by minimal, plum-accented note-taking interfaces.

Bundled fonts are licensed separately under the SIL OFL — see
[`fonts/LICENSES.md`](fonts/LICENSES.md) for attribution.

## License

[MIT](LICENSE)
