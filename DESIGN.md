# README design

How this profile README should look, and why. It's read by recruiters and engineers deciding in under a minute whether my work is worth a closer look, so every choice here is about making the work easy to find and easy to believe.

**Direction:** calm and technical. Dark navy, one blue accent, monospace details, plenty of space. No decoration that doesn't carry information.

## Color

GitHub controls the page colors, so these only apply to the images I make: the header and the buttons. The header is dark in both GitHub themes; on a white page it reads as a dark card, which is the look I want. Every color has one job.

| Token | Value | Role |
|---|---|---|
| `ink-950` | `#0b0d16` | Header background, text on the primary button |
| `navy-800` | `#1f2a5c` | Header border and divider, secondary button fill |
| `blue-400` | `#8ea2ff` | The accent: header label, status dot, primary button fill |
| `blue-500` | `#5566c0` | Button border, the only value that stands out on both GitHub themes |
| `text-strong` | `#eef1fb` | Name, status text, text on secondary buttons |
| `text-muted` | `#a3abc4` | The one line and the footer in the header |

One accent only. No gradients, no extra brand colors, no colored badges for every tool.

Contrast (WCAG): header text is 8:1 or higher. Button text is 8.1:1 (primary) and 12:1 (secondary). Button borders are 3.6:1 on GitHub dark and 5.2:1 on GitHub light, so the buttons read as buttons on either theme. There are no success, warning or error colors because a README has no states.

## Type

- **Body:** GitHub's own font and sizes. I don't fight them.
- **Header and buttons:** the system UI font for the name, the line and the buttons, and the system monospace font for the small labels. These are the same stacks GitHub uses, so the images feel native and stay tiny.
- **Header sizes (in a 1200 wide frame):** name 64, line 25, mono labels 17 to 18.
- **Markdown hierarchy:** `##` for sections, `###` for project names, nothing deeper. Sentence case headings.
- **Bold:** at most one bold phrase per bullet, and only on the result.
- **Code spans:** only for tech tags under a project, at most six per project.

## Spacing

- 8 point grid in the images: 64 side padding in the header, buttons 32 tall with 14 side padding.
- In markdown, one blank line between blocks. Sections are separated by their heading only, never by horizontal rules or divider images.
- A project card has a name, one line on what it is, at most three bullets and one tag row.

## Shape

- Header corners 12, button corners 6 (the same as GitHub's own buttons).
- 1 to 1.5 px borders. No shadows anywhere.

## Components

- **Header:** one dark SVG for both themes, left aligned: label, name, one line, divider, footer row with my status on the right. Alt text says the same thing in words.
- **Buttons:** Resume is the primary action (blue fill). LinkedIn and Email are secondary (navy fill). Text only, no logos.
- **About:** the YAML block, then one short paragraph.
- **Lead project card:** used for my two strongest projects only. A real screenshot linked to the repo, then the standard card.
- **Compact project card:** two per row, no image, at most two bullets.
- **More projects:** a table inside `<details>`, so it doesn't push experience down.
- **Experience, skills, certifications:** plain tables. Skills are words, not logo badges.

## Imagery

- Only real screenshots of my own apps, taken from each project's `docs/screenshots` folder, cropped to 16:10 so cards in a row line up, saved in `assets/` and always linked to the repo.
- No emoji as icons, no typing animations, no view counters, no third party stats cards and no wave banners.
- Every image has alt text that describes what it shows.

## Writing

- Plain English, short lines, no buzzwords.
- No hyphens or dashes in prose (tags and links are fine).
- Every number must match the project's own README, including its caveats.
- Lead with what the thing does, then the result, then the stack.

## Changing things

- New project: add it as a compact card, or move it to the lead row if it's stronger than one there. Keep the lead row at two.
- Header or button text: edit the SVG directly. If a button's text gets longer, widen its frame to match.
- New color: don't. If something needs emphasis, use position or bold.
