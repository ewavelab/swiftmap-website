# SwiftMap Homepage Design

## Goal
Create a one-page GitHub Pages homepage for SwiftMap that is minimal, clear, and faithful to the product direction in `docs/Design.md`.

## Content
- Brand header with the SwiftMap logo in the top-left.
- Hero section with a concise headline and short summary.
- Capability cards for:
  - plain-text format
  - keyboard-first editing
  - PNG export
- Trust/value cards below the capability row:
  - Your files stay private
  - Free for private and commercial use
  - Open source project
- Example section featuring:
  - `project-planning`
  - `personal-roadmap`
- Footer with a source link to the GitHub repository.

## Visual Direction
- Light background with cyan/teal accents.
- Large editorial headline, similar to the provided reference.
- Minimal page chrome, no navigation menu.
- Rounded cards, subtle borders, soft shadows, and plenty of whitespace.
- Decorative mind-map illustration on the right side of the hero.

## Typography
- Use a clean sans-serif stack with a slightly expressive, display-like feel.
- Headlines should use tight tracking and strong weight.
- Body copy should stay short and readable.

## Asset Usage
- Reuse the SwiftMap logo from `website/assets/logo.png`.
- Reuse example screenshots in `website/assets/`.
- Keep example `.swiftmap` files in `website/examples/` so the published page is self-contained.

## Implementation Notes
- The homepage must be static and GitHub Pages-ready.
- Keep all page-specific assets inside `website/`.
- Avoid external dependencies and runtime JavaScript unless it is strictly needed.
- Keep `docs/` limited to this design file plus the existing project specifications.
