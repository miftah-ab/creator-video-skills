# Creator Video Skills

A self-contained Claude skill for producing finished YouTube videos from a final script and its matching voiceover.

## Installable skill structure

The repository root is the installable skill root:
- `SKILL.md` — core production instructions and workflow orchestration.
- `PROJECT_STATUS.md` — implementation status and validation still required.
- `references/american-wallet-style.md` — American Wallet finance-documentary identity, Barlow Condensed ExtraBold + Inter typography, and Deep Navy/Warm Ivory brand rules.
- `references/ninety-sense-style.md` — Ninety Sense story identity, Oswald + Manrope typography, and its dark editorial color palette.
- `references/ricks-clips-visual-system.md` — original 3D scene + expressive 2D face production guidance for Ninety Sense.
- `references/image-prompt-workflow.md` — script-led image prompt creation and manual asset handoff for both channels.
- `references/output-contract.md` — per-production aspect ratio selection and exact voiceover-basename MP4 naming.
- `references/sound-design-workflow.md` — story-specific music, ambience, foley, effects, transitions, mixing, and audio QC.
- `references/font-setup.md` — one-time font installation guidance and per-project font-availability checks.
- `references/quality-control.md` — final export and playback inspection for both channels and both supported formats.

**Important:** Keep `SKILL.md` directly at the top level. Do not place it inside `skills/voiceover-to-video/` or another nested directory. A ZIP or `.skill` package must contain `SKILL.md` at the archive root and the `references/` directory beside it.

Expected package layout:

```text
voiceover-to-video.zip
├── SKILL.md
├── PROJECT_STATUS.md
└── references/
    ├── american-wallet-style.md
    ├── ninety-sense-style.md
    ├── ricks-clips-visual-system.md
    ├── image-prompt-workflow.md
    ├── output-contract.md
    ├── sound-design-workflow.md
    └── quality-control.md
```

## Scope

This skill produces videos only. Channel banners and promotional graphics are out of scope.

## Production workflow

Input: the final script and matching voiceover. Claude directs the creative treatment, creates story-specific image prompts and maps uploaded assets, uses available tools to create visuals and edit the timeline, designs sound, exports, and performs quality control.

Both American Wallet and Ninety Sense support **16:9 landscape and 9:16 portrait**. Select exactly one format for each production. Do not assume a permanent format based on channel or content type, and do not automatically render both.

The final MP4 basename must exactly match the uploaded voiceover basename. Change only the audio extension to lowercase `.mp4`; preserve numbering, capitalization, spaces, and punctuation.

The user may generate prompted images in their chosen image generator and upload them manually. A paid image-generation API is not required. A prompt list alone is not a finished video.

## Production truth

No placeholders may remain in a claimed final delivery. Do not claim that rendering, playback review, audio measurement, or quality checks happened unless they were actually performed. If an essential generation, editing, or rendering capability is unavailable, state the exact blocker rather than pretending the video was produced.

## Reference

[Ricks Clips (@RicksClips3000)](https://www.youtube.com/@RicksClips3000)

Borrow broad production techniques only. Scripts, characters, exact artwork, footage, voice, music, and branding must be original.
