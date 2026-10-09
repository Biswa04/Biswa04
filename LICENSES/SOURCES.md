# Third-party assets embedded in the SVGs

## Fonts (base64 WOFF2, Latin subset, SIL Open Font License 1.1)
| Font | Use | Source | License file |
|---|---|---|---|
| Unbounded ExtraBold (800) | display type | `@fontsource/unbounded@5.3.0` (github.com/googlefonts/unbounded) | `OFL-Unbounded.txt` |
| JetBrains Mono Regular (400) and SemiBold (600) | mono type | `@fontsource/jetbrains-mono@5.3.0` (github.com/JetBrains/JetBrainsMono) | `OFL-JetBrainsMono.txt` |

## Icons (Simple Icons, CC0 1.0 for the artwork; the marks remain trademarks of their owners)
Paths come from the Simple Icons npm releases listed below. `SimpleIcons-LICENSE.md` is the CC0 text.

| Icon | Brand colour | Source file |
|---|---|---|
| C | #A8B9CC | `simple-icons@11.15.0 (c.svg)` |
| C++ | #00599C | `simple-icons@11.15.0 (cplusplus.svg)` |
| Python | #3776AB | `simple-icons@11.15.0 (python.svg)` |
| Spring Boot | #6DB33F | `simple-icons@11.15.0 (springboot.svg)` |
| HTML | #E34F26 | `simple-icons@11.15.0 (html5.svg)` |
| CSS | #1572B6 | `simple-icons@11.15.0 (css3.svg)` |
| JavaScript | #F7DF1E | `simple-icons@11.15.0 (javascript.svg)` |
| Bootstrap | #7952B3 | `simple-icons@11.15.0 (bootstrap.svg)` |
| Tailwind CSS | #06B6D4 | `simple-icons@11.15.0 (tailwindcss.svg)` |
| React | #61DAFB | `simple-icons@11.15.0 (react.svg)` |
| Node.js | #5FA04E | `simple-icons@11.15.0 (nodedotjs.svg)` |
| Express.js | #000000 | `simple-icons@11.15.0 (express.svg)` |
| PostgreSQL | #4169E1 | `simple-icons@11.15.0 (postgresql.svg)` |
| MySQL | #4479A1 | `simple-icons@11.15.0 (mysql.svg)` |
| Google Cloud | #4285F4 | `simple-icons@11.15.0 (googlecloud.svg)` |
| AWS | #232F3E | `simple-icons@11.15.0 (amazonaws.svg)` |
| Docker | #2496ED | `simple-icons@11.15.0 (docker.svg)` |
| GitHub | #181717 | `simple-icons@11.15.0 (github.svg)` |
| VS Code | #007ACC | `simple-icons@11.15.0 (visualstudiocode.svg)` |
| Git | #F05032 | `simple-icons@11.15.0 (git.svg)` |
| Git Bash | #4EAA25 | `simple-icons@11.15.0 (gnubash.svg) - GNU Bash mark used for Git Bash; no official Git Bash mark in Simple Icons` |
| Postman | #FF6C37 | `simple-icons@11.15.0 (postman.svg)` |
| Gmail | #EA4335 | `simple-icons@11.15.0 (gmail.svg)` |
| LinkedIn | #0A66C2 | `simple-icons@11.15.0 (linkedin.svg)` |
| Java | #007396 | `simple-icons@5.23.0 (java.svg)` |
| APIs | #247BFF | `custom neutral glyph (no brand mark exists for the generic term APIs)` |

Notes
- Current Simple Icons releases no longer include the Java, AWS or LinkedIn marks. Those three come from the last npm releases that still shipped them: Java from simple-icons 5.23.0, AWS and LinkedIn from simple-icons 11.15.0. Every other icon is from 11.15.0 as well.
- I could not reach the brands' own asset portals from the build environment, so no mark came from an official brand kit. Check each owner's brand guidelines if you reuse the marks outside a personal profile.
- Git Bash: Simple Icons has no Git Bash mark, so the GNU Bash mark (simple-icons 11.15.0) is used for it.
- VS Code, Git, Postman and Gmail marks: simple-icons 11.15.0 (the current release dropped VS Code). APIs has no brand mark, so it uses a neutral custom braces glyph drawn for this project.
- The portrait and pointing images are your own files, resized with Lanczos (premultiplied alpha) to 800 px and 1000 px wide. Nothing was redrawn or re-masked.
