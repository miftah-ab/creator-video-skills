# Creator Video Skills

A story-first video production system for Claude. One repository is the source of truth for both channels.

## Purpose

Input:
- The final approved script.
- The matching voiceover audio.

Target output:
- A finished, narration-synchronized video when Claude's available tools can actually render one.
- Otherwise, a complete production package with an honest explanation of the missing capability. Never claim an MP4 was rendered when it was not.

Claude is the only AI decision-maker in this workflow. It may use necessary non-AI production utilities (for example FFmpeg) when they are available and permitted. It must not silently depend on paid AI APIs, another AI agent, or unavailable services.

## Repository map

- `skills/voiceover-to-video/SKILL.md` — main production skill
- `skills/voiceover-to-video/references/production-pipeline.md`
- `skills/voiceover-to-video/references/quality-control.md`
- `channels/american-wallet/STYLE.md`
- `channels/ninety-sense/STYLE.md`
- `workflows/production-workflow.md`
- `assets/README.md`

## Install and use

1. Keep this repository as the single source of truth.
2. Package the `skills/voiceover-to-video` folder using the skill-import format supported by your Claude account.
3. Upload/install the skill in Claude.
4. Start a production chat by attaching the final script and voiceover audio, then identify the channel and aspect ratio only if they are not already clear.

Claude capabilities and limits can change. The skill must inspect what tools and file operations are actually available in the current chat instead of assuming it can execute scripts, access the filesystem, browse, or render video.

## Non-negotiable rules

- Story first. No fixed visual template applied blindly.
- Voiceover is the timing authority.
- Make both 16:9 and 9:16 compositions intentionally; do not merely crop one master.
- Strong animated emphasis, deliberate sound effects, and purposeful background music are expected where they serve the story.
- Choose tools based on actual availability. Prefer free/local production utilities over paid services.
- Never fabricate source footage, tool execution, exports, or quality-control results.
- Keep channel identities separate.
- Improve this system from real video tests; do not add complexity without evidence.
