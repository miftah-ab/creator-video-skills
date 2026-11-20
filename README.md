# Creator Video Skills

A self-contained Claude skill for producing YouTube videos from a final script and matching voiceover.

## Installable skill folder
`skills/voiceover-to-video/`

It contains the complete skill and all references required at runtime:
- `SKILL.md` — production instructions.
- `references/ninety-sense-style.md` — Ninety Sense visual and story profile.
- `references/american-wallet-style.md` — separate finance-documentary profile.
- `references/ricks-clips-visual-system.md` — actionable 3D scene + 2D expressive-face animation specification.
- `references/quality-control.md` — final export inspection.

## Workflow contract
Input: final script + matching voiceover. Claude directs the story, creates and checks real visual assets with available tools, edits, exports, and verifies the video. A prompt list is not a finished video. No placeholders may remain in a claimed final delivery.

If an essential generation or rendering capability is unavailable, Claude must name the exact blocker instead of pretending the video was produced.

## Reference
[Ricks Clips (@RicksClips3000)](https://www.youtube.com/@RicksClips3000)

Borrow broad production techniques only. Scripts, characters, exact artwork, footage, voice, music, and branding must be original.

## Claude skill package requirements

The installable skill is the `skills/voiceover-to-video/` directory. Its `SKILL.md` must remain at the root of that directory and begin with YAML frontmatter containing both required fields:

```yaml
---
name: voiceover-to-video
description: Produce a complete narrated YouTube video from the final script and matching voiceover, using the correct channel-specific visual direction.
---
```

When creating a ZIP or `.skill` package for Claude, package the **contents of** `skills/voiceover-to-video/` so that `SKILL.md` is at the archive root, with the `references/` directory beside it. Do not zip the entire repository as the skill package, and do not place `SKILL.md` one extra folder deep.

Expected archive layout:

```text
voiceover-to-video.zip
├── SKILL.md
└── references/
    ├── american-wallet-style.md
    ├── ninety-sense-style.md
    ├── ricks-clips-visual-system.md
    └── quality-control.md
```
