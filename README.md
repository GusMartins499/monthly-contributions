# Monthly Contributions

See any GitHub user's contribution graph for a specific month, styled like the profile calendar.

**Live:** https://gusmartins499.github.io/monthly-contributions/

- Month calendar with GitHub's contribution levels
- Total contributions, active days, longest streak and best day
- Light/dark theme toggle (follows your system by default)
- Month navigation and shareable links (`?user=<login>&month=YYYY-MM`)

A single static `index.html`, no build step. The UI is built with GitHub's
[Primer](https://primer.style/) design system: components and utilities from
`@primer/css`, colors and sizes from `@primer/primitives` design tokens, and
[Mona Sans](https://github.com/github/mona-sans) type. The data comes from
[github-contributions-api](https://github.com/grubersjoe/github-contributions-api).

## Running locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.
