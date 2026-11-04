# Sources — scene-grammar demo (landscape)

Demo fixture for the scene-grammar library. The on-screen copy describes
Motion Studio itself, so every claim is sourced from this repository and no
third-party company, product or brand appears. The brand profile is `generic`.
All media are neutral placeholder SVGs drawn for this repository. Replace them
with media you have the right to use.

## Claim sources
| # | Description | URL | What it proves |
|---|-------------|-----|----------------|
| 1 | `VIDEO_WORKFLOW.md` (this repository) | VIDEO_WORKFLOW.md | One HTML composition per video on one GSAP timeline; visual-first rule; source verification, visual story and validation before render |
| 2 | `PRODUCTION.md` (this repository) | PRODUCTION.md | The gated pipeline: each stage passes or blocks the render |
| 3 | `templates/tech-news-ar/lib/grammars.json` (this repository) | templates/tech-news-ar/lib/grammars.json | The eight scene grammars, from full-bleed media to comparison and big number |

## Assets used
| file | type | origin path | direct asset URL | licensing/usage note |
|------|------|-------------|------------------|----------------------|
| `assets/placeholder-hero.svg` | SVG 1280x720 | this repository | — | Project-owned placeholder (Apache-2.0); stands in for a hero image |
| `assets/placeholder-chart.svg` | SVG 1680x945 | this repository | — | Project-owned placeholder (Apache-2.0); illustrative shapes, no data |
| `assets/placeholder-stack.svg` | SVG 1920x1080 | this repository | — | Project-owned placeholder (Apache-2.0); contains the detail board the demo zooms to |
| `assets/placeholder-logo.svg` | SVG | this repository | — | Project-owned placeholder (Apache-2.0); neutral logo slot, topbar only |
| `assets/fonts/Alexandria-{arabic,latin}.woff2` | WOFF2 (variable) | https://github.com/google/fonts/tree/main/ofl/alexandria | https://fonts.google.com/specimen/Alexandria | SIL Open Font License 1.1 (`assets/fonts/OFL-Alexandria.txt`); studio typography |

## Audio sources
None (silent demo).

## Notes
- The zoom/highlight region (`data-region="0.53,0.71,0.29,0.195"`) matches the detail board drawn in `placeholder-stack.svg`; update it when you swap the image.
- No tashkeel in any Arabic text.
