# Creator Video Skills

A self-contained Claude skill for producing YouTube videos from a final script and matching voiceover.

## Installable skill structure

The repository root is the installable skill root:
- `SKILL.md` — production instructions, with required YAML frontmatter.
- `references/ninety-sense-style.md` — Ninety Sense visual and story profile.
- `references/american-wallet-style.md` — separate finance-documentary profile.
- `references/ricks-clips-visual-system.md` — actionable 3D scene + 2D expressive-face animation specification.
- `references/quality-control.md` — final export inspection.

**Important:** Keep `SKILL.md` directly at the top level. Do not place it inside `skills/voiceover-to-video/` or another nested directory. A ZIP or `.skill` package must contain `SKILL.md` at the archive root and the `references/` directory beside it.

Expected package layout:

```text
voiceover-to-video.zip
├── SKILL.md
└── references/
    ├── american-wallet-style.md
    ├── ninety-sense-style.md
    ├── ricks-clips-visual-system.md
    └── quality-control.md
```

## Workflow contract

Input: final script + matching voiceover. Claude directs the story, creates and checks real visual assets with available tools, edits, exports, and verifies the video. A prompt list is not a finished video. No placeholders may remain in a claimed final delivery.

If an essential generation or rendering capability is unavailable, Claude must name the exact blocker instead of pretending the video was produced.

## Reference

[Ricks Clips (@RicksClips3000)](https://www.youtube.com/@RicksClips3000)

Borrow broad production techniques only. Scripts, characters, exact artwork, footage, voice, music, and branding must be original.
