# Shared production output contract

This reference is mandatory for **American Wallet and Ninety Sense** on every production.

## 1. Select exactly one format per production

Both channels support both formats:

- **16:9 landscape**
- **9:16 portrait**

At the start of each project:
1. Use the format the user explicitly selected for this video.
2. If no format has been selected or established for this project, ask one concise question: **“16:9 or 9:16 for this video?”**
3. Render exactly one selected format per production run. Do not automatically create both formats from the same script/voiceover.
4. Do not infer the format from the channel name, a previous upload, or the word “Short.”

The selected format applies to the entire project: storyboard, scene framing, generated/source assets, graphics, captions, subtitles, camera movement, safe areas, and export.

### Format-specific composition

**16:9 landscape**
- Compose for a widescreen frame from the beginning.
- Use horizontal staging, environmental context, layered depth, and landscape-friendly graphic layouts.
- Keep titles, captions, charts, and important action readable within landscape-safe areas.

**9:16 portrait**
- Compose for a vertical frame from the beginning.
- Prioritize a clear primary subject and vertically organized information.
- Re-layout charts, documents, character blocking, and graphics instead of cropping a landscape composition.
- Keep faces, important props, captions, and subtitles inside portrait-safe areas.

Never stretch, letterbox, or blindly crop a composition designed for the other format. Recompose the scene and redesign the graphic when needed.

## 2. Exact MP4 filename — hard requirement for both channels

The final rendered MP4 must use **the exact original filename of the uploaded voiceover, with only the audio extension replaced by `.mp4`**.

Example:

- Uploaded voiceover: `11-Congress found a way to collect taxes from.mp3`
- Required final render: `11-Congress found a way to collect taxes from.mp4`

Rules:
- Read the original uploaded filename from the upload metadata. Do not use a temporary/internal renamed copy as the source of truth.
- Preserve the complete basename exactly: numbering, capitalization, spaces, punctuation, hyphens, underscores, and wording.
- Remove only the final audio-file extension and use lowercase `.mp4`.
- Do not rename the file to the video title, script title, channel name, date, or a generated slug.
- Do not add suffixes such as `final`, `edited`, `16x9`, `9x16`, `v2`, or a timestamp.
- Apply this rule identically to American Wallet and Ninety Sense.
- If the original uploaded filename cannot be determined, ask the user for it. Never guess or silently substitute a name.
- If a file with that exact name already exists in the destination, use a separate project output folder or ask before overwriting. Never alter the required basename to avoid a collision.
- Before delivery, verify that the exported MP4 filename exactly matches the required name.

The filename rule does not change when the user selects a different aspect ratio. The selected format changes the video composition; it does not change the output basename.
