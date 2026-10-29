# FM-PCC slides: hosting test

A **test** of hosting the thesis presentation ("Flow Matching Predictive Control with Constraints") with GitHub
Pages. The deck is one self-contained HTML file, so this repository only holds the built files.

| | |
| :-- | :-- |
| **Branches** | `master` holds only a minimal README. The site lives on `test`, which Pages publishes from. `bkp-v3.12-no-animation` keeps the last deck without the animations (v3.12, 2026-10-14) as a backup; it is not published. |
| **Site** | `index.html` = deck v4.2 (result slides on the thesis's own figures and tables; slide numbers n / End, then i, ii … in the supplement), the method told by animation beats (muted clips; each plays and holds, a click plays on) · `presentation.pdf` = its PDF backup (each beat as its last frame) · `.nojekyll` = serve the files as they are |
| **Source** | copied unchanged from `FM-PCC/logs_in_develop/Writing/Presentation/output/v4/v4.2/` on 2026-10-29, the hot update that changed only the speaker notes (the planned clock, start → end; Q&A lines) (sha256 `c8e647f9e7f916c3…` / `74d06b5c88e79d5d…`) |
| **Live** | https://ghubliming.github.io/fmpcc-slides/ |
| **Plan** | `FM-PCC/logs_in_develop/Writing/Presentation/plan/HOSTING.md`, section "Test setup" |

**Keys:** → / Space / scroll: next (on an animation slide: play to the next pause) · **S**: speaker view · **F**: fullscreen · **O**: overview.

**Note:** this test copy is the deck as built, so it **includes the speaker notes** (press S); the talk ends at the
"End" slide, and the slides after it are the supplement. A public release would strip the notes first. The page is
about 50 MB (25 embedded clips), so the first load takes a moment.
