# Claude Code Master Class — Project Instructions

## What This Is
A single-page personal knowledge hub for Claude Code. All content lives in `index.html` — no build step, no framework, no dependencies to install.

## Tech Stack
- Tailwind CSS v3 via CDN (`cdn.tailwindcss.com`)
- Iconify icons via CDN
- Google Fonts: Manrope (headings), Inter (body), JetBrains Mono (code)
- Vanilla JavaScript (inline)

## Design System
- **Accent color**: `#ef233c` (red)
- **Background**: Black (`#000`) with gradient to `#1a0505`
- **Text**: White for headings, `zinc-400` for body, `zinc-500` for secondary
- **Borders**: `white/10` default, `white/20` on hover
- **Cards**: `bg-black` or `bg-zinc-900/50` with border and hover glow
- **Code inline**: `.cmd-code` class — JetBrains Mono, red-tinted bg, red border

## How to Preview
Open `index.html` directly in a browser. No server required.

## Content Guidelines
- Keep command references accurate to current Claude Code CLI
- Use `cmd-code` class for inline code/commands
- Topic cards have `data-topic` attributes for search filtering — update these when adding content
- All sections have anchor IDs for navbar navigation

## Sections (in order)
1. Hero (`#hero`)
2. Topics Bento Grid (`#topics`)
3. Quick Reference (`#quick-ref`)
4. Pro Tips Banner (`#tips`)
5. Workflows (`#workflows`)
6. Config Cheat Sheet (`#config`)
7. Permission Modes (no anchor, between config and footer)
8. Footer
