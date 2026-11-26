# Font setup and production preflight

This repository defines the typography; it does not automatically install fonts. The required font families must be installed and available on the actual computer or editing environment that renders the MP4. Installing fonts on a different device, or merely listing them in this repository, does not make them available to the renderer.

## Required fonts

| Channel | Role | Required family and weight |
|---|---|---|
| American Wallet | Headlines and major financial figures | Barlow Condensed ExtraBold (800) |
| American Wallet | Supporting copy, chart labels, captions, subtitles | Inter (400, 500–600, selective 700) |
| Ninety Sense | Short hooks and key phrases | Oswald Bold (700) |
| Ninety Sense | Subtitles, captions, labels, supporting copy | Manrope (400, 500–700) |

## One-time setup

1. On the computer used for video editing/rendering, install the four families from their official Google Fonts pages or another trusted source that provides the original SIL Open Font License files.
2. Install the required weights, not just the regular style. In particular, verify Barlow Condensed ExtraBold 800 and Oswald Bold 700 are available.
3. Restart the editing application after installation. Some editors cache their font list until restarted.
4. Create or open a test title using each required family and confirm the editor renders the intended face and weight. Do not rely only on a font name appearing in a dropdown.

Do not commit font binaries to this repository by default. The fonts belong on the rendering machine; adding binaries to GitHub is unnecessary unless a later deployment environment specifically requires packaged assets and licensing/redistribution has been reviewed.

## Mandatory check at the start of every production

Before building titles, captions, subtitles, charts, or other text graphics:

1. Identify the channel profile.
2. Check that both required font families and their required weights are actually available in the current editing environment.
3. Use the exact fonts and weights when available.
4. If a required face is missing, do not silently substitute. Use a close, consistent fallback only if production can continue safely, and record the missing font, chosen fallback, and affected text elements in the handoff/QC notes.
5. Never claim the required font was used unless it was verified in the rendered project.

If the environment does not expose font inspection, say that availability could not be verified. Do not pretend the check passed.

## Production scope

Typography rules in this document apply to video frames only. Channel banners and promotional graphics are not part of this skill.
