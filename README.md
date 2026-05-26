# testing-grok-code

> **This repository documents a failed attempt to build a fully self-contained, locally-renderable interactive website using Grok 4.3.**

## Original Task

The initial user prompt was:

> ## THE FELON — Interactive Website Build
>
> Build a visually stunning, fully interactive single-page website about the
> Sukhoi Su-57 stealth fighter — codename: "The Felon".
>
> Before writing any code:
> Research the Su-57 thoroughly — specs, history, stealth design, combat record,
> and how it compares to its rivals (F-22, J-20). Fetch real images with
> resolving URLs (Wikimedia Commons is a good source). No placeholders.
>
> The site should feel like a premium editorial experience.
> Design, structure, and content choices are yours — make it impressive.
> The only hard requirements are:
>
> - Pure HTML/CSS/JS, no build tools. CDN libraries are fine.
> - Must be interactive — go beyond static content, surprise me.
> - All factual claims grounded in open-source reporting.
>   Flag speculation explicitly in the UI where relevant.
>
> Git workflow:
> - git init → work on a dev branch
> - Decide your own milestones — commit on dev when each feels solid
> - Open and test the site in a browser at each milestone before committing
> - Merge to main only when a milestone passes its test
> - No remote push
>
> Show your research before writing code.
> Show your git log when done.

## What Happened

- Research was done thoroughly and committed first (`RESEARCH.md`).
- A detailed design plan was created (`DESIGN.md`).
- An ambitious single-file website was built following the strict milestone + browser testing + dev branch workflow.
- Multiple major features were implemented:
  - Cinematic hero with real Wikimedia images
  - Interactive development timeline
  - Live rival comparison tool with Chart.js radar charts and sliders
  - Custom Canvas RCS (radar cross section) visualizer
  - Filterable combat record with interactive SVG map
  - Masonry gallery with pure-JS lightbox
  - Various polish interactions

- **The core problem**: The site was initially built heavily around the Tailwind Play CDN (`https://cdn.tailwindcss.com`) for styling.

- When the user opened `index.html` directly (as a local file), the site did **not render** properly — it appeared as unstyled text. This happened on the first attempt.

- Multiple rounds of fixes were attempted:
  - Adding large fallback CSS blocks
  - Eventually removing the Tailwind CDN entirely and trying to make everything self-contained

- Despite these efforts, the user reported on a second attempt that it **still only showed text** with no proper rendering when opening the file locally.

## Conclusion

**This attempt failed to deliver a website that successfully renders when opened directly as a local `index.html` file.**

The combination of:
- Heavy initial reliance on external CDNs
- The complexity of the interactive components
- The strict requirement of "Pure HTML/CSS/JS, no build tools" while still wanting a premium design
- Difficulty making a complex Tailwind-heavy single file degrade gracefully to a fully self-contained version

...resulted in a project that did not meet the user's expectation of simply opening the file and seeing a properly styled, interactive website.

This repository is being published transparently as a record of the process and the failure.

## Repository Structure

- `main` branch: Final state after all work and fixes
- `dev` branch: Full development history with all milestone commits
- `index.html`: The (ultimately unsuccessful) website
- `RESEARCH.md`: Detailed research on the Su-57
- `DESIGN.md`: Original architecture and interaction plan

## Grok Version

Built using **Grok 4.3** (released by xAI in April 2026).

## License

This is a transparency / failure case study repository. All research content is based on open sources.

---

*Published as requested to document the outcome of the "THE FELON" website build task.*
