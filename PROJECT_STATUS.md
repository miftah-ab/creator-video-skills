# Project status

## Current production contract

- Both Ninety Sense and American Wallet support 16:9 landscape and 9:16 portrait.
- Exactly one format is selected per production. Never assume a permanent channel format or automatically render both.
- Final MP4 basename must exactly match the uploaded voiceover basename; replace only the final audio extension with lowercase `.mp4`. Preserve numbering, capitalization, spaces, and punctuation.
- Claude interprets the complete script/story and creates specific, ready-to-paste image prompts for images genuinely needed by that story.
- The user may generate images in their chosen image generator and upload them using stable Image 1, Image 2, etc. labels. No paid image-generation API is required.
- Both channels use the shared story-first sound-design workflow. Claude should execute sound design in the actual timeline when the available environment supports it and must report limitations honestly.
- Ninety Sense and American Wallet retain separate creative identities and channel references.

## Implemented in the repository

- Execution-focused voiceover-to-video skill with input validation, creative ownership, and production truth requirements.
- Separate Ninety Sense and American Wallet channel profiles, each with a locked typography and color system.
- American Wallet typography: Barlow Condensed ExtraBold (800) for headlines/major figures; Inter for supporting copy, captions, labels, and subtitles. Deep Navy `#14263D` and Warm Ivory `#F5F1E8` remain the brand foundation. Claude may use muted red/green semantic signals only when the actual script's financial meaning warrants them; color must reflect context, not decoration.
- Ninety Sense typography: Oswald Bold (700) for short hooks/key phrases; Manrope for captions, subtitles, and supporting copy. Palette: Deep Ink `#111827`, Slate `#374151`, Warm Ivory `#F7F4EE`, Muted Vermilion `#C94B3C`, Soft Sand `#E8DED0`, and White `#FFFFFF`. Vermilion is a rare accent; no purple, neon blue/cyan, gradients, glow, rainbow colors, or excessive red.
- Typography rules are reflected in channel profiles, image-prompt guidance, and final quality control.
- Font availability is checked before editing; missing fonts are reported and any fallback is documented rather than silently substituted.
- Original Ninety Sense visual-system guidance; it borrows broad visual grammar only, not another creator's protected characters, artwork, footage, music, or branding.
- American Wallet finance-documentary visual standard, including information-rich visual explanation and no empty-screen narration coverage.
- Shared image-prompt workflow and manual asset handoff.
- Shared output contract for per-production format selection and exact voiceover-basename MP4 naming.
- Shared story-first sound-design workflow.
- Font preflight and installation guidance for the four required font families; the actual fonts must be available on the machine that renders the video.
- Thumbnail and channel-promotion graphics explicitly removed from project scope; this repository covers video production only.
- Updated quality-control checklist covering both channels, both formats, filename verification, picture, sound, and final playback.
- README now documents all required references and the current production contract.

## Not yet validated in real production

These are runtime tests, not documentation tasks:
- End-to-end production using the user's actual Claude tools and available editing/rendering environment.
- Image prompt quality, manual image upload mapping, and visual consistency across a complete Ninety Sense video.
- American Wallet documentary coverage, financial graphic clarity, and brand compliance across a complete video.
- Actual timeline sound-design execution, final MP4 export, exact filename preservation, and full playback review.
- Successful separate tests in 16:9 and 9:16.

## Next validation sequence

1. Produce one complete Ninety Sense video from its final script and voiceover. Select one format, generate prompts, upload the resulting images, edit, sound-design, export, and inspect the actual MP4.
2. Produce one complete American Wallet video separately and inspect its documentary visuals, financial explanations, brand compliance, sound, and export.
3. Run a second production in the other aspect ratio to verify native composition and export behavior.
4. Record only observed failures and fix those. Do not add architecture or features without evidence from these production tests.

## Completion rule

The skill instructions and repository documentation are implemented. The production system is **not end-to-end validated** until real videos from both channels have been exported and reviewed. Never describe the project as fully production-proven before those tests pass.
