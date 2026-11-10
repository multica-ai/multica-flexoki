# Flexoki for Multica

[Flexoki](https://stephango.com/flexoki), the inky colour scheme for prose and code by Steph Ango, as a [Multica](https://multica.ai) theme. Warm paper and black ink in light mode, its dark counterpart in dark mode, Flexoki's colours for status, priority and code, and a choice of accent.

Install it from **Settings → Appearance → Manage** in Multica, or download `theme.zip` from the latest release and import it.

## Options

- **Accent**: blue (default), cyan, green, orange, red, purple or magenta. It colours primary buttons, links, checkboxes and focus rings.

Flexoki pairs its 600 accents with paper and its 400 accents with black. Where a pair falls short of WCAG AA for text, the theme uses the next shade: cyan and green 700 in light mode, blue and red 300 in dark mode.

## Develop

From a checkout of [multica-ai/multica](https://github.com/multica-ai/multica):

```bash
pnpm theme:check ../multica-flexoki     # validator and contrast checks
pnpm theme:preview ../multica-flexoki   # light.png and dark.png
```

To release, bump `version` in `manifest.json`, tag the commit with the same version (`v1.1.0`), and push the tag. The release workflow attaches `theme.zip`; the [theme store](https://github.com/multica-ai/multica-themes) picks it up within the hour once it passes the checks.

## License

MIT. The Flexoki palette is © Steph Ango, MIT, from [kepano/flexoki](https://github.com/kepano/flexoki).
