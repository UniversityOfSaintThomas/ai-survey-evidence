# ai-survey-evidence

St. Thomas AI Survey Evidence: how University of St. Thomas students, faculty, and staff use and view generative AI, from the 2025 and 2026 AI surveys. A companion to [student-ai-evidence](https://universityofsaintthomas.github.io/student-ai-evidence/).

The site is a single `index.html` with no build step. Each section asks the reader to guess a number, reveals the survey result, and links the finding to university supports (Access, Capability, Culture).

## Publish on GitHub Pages

1. Create the repository `universityofsaintthomas/ai-survey-evidence`.
2. Push `index.html` and this README to `main`.
3. In Settings → Pages, set the source to `main` and the root folder.
4. The site appears at `https://universityofsaintthomas.github.io/ai-survey-evidence/`.

## Data

All figures are computed from the cleaned survey files (students 310 and 925; faculty 281 and 254; staff 281 and 347 valid responses in 2025 and 2026). Respondents who answered fewer than half of the non-demographic questions are excluded, matching the published student analysis. Methods, wording changes, and caveats are listed on the page under Sources and methods. No individual responses are included; the page carries only aggregate percentages.

## Accessibility

Built to WCAG 2.2 AA: text and essential marks meet contrast minimums in light and dark modes; every chart prints its values and has a table view; year and guess markers differ by shape, not color alone; all controls work by keyboard with a visible focus state; motion respects `prefers-reduced-motion`. Guesses are stored only in the reader's browser.

## Updating

Numbers live in the `DATA` object near the end of `index.html`. Prepared by STELAR, October 2026. Contact: Jonathan Keiser.
