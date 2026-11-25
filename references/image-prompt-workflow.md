# Shared image-prompt workflow

This workflow is mandatory for **American Wallet and Ninety Sense**. Claude is the visual director and prompt writer. The user generates the images in their chosen image-generation tool and uploads them back to the project. Do not require a connected image-generation API or a new paid subscription.

## Core principle: prompt quality is the job

Do not produce generic prompts that merely repeat a sentence from the script. First understand the story, then design a specific image that communicates the intended moment. Every prompt must be detailed enough to paste directly into an image generator without the user having to rewrite it.

A good prompt translates the story beat into a visual scene. It specifies:
- The exact subject, action, and story context.
- What the viewer should notice or feel.
- Setting, period, time of day, and environmental details when relevant.
- Character appearance, age range, clothing, expression, body language, and continuity when needed.
- Composition and subject placement for the selected aspect ratio.
- Camera viewpoint, shot size, lens/visual perspective, depth, and focal point.
- Lighting, atmosphere, material detail, and channel-specific visual language.
- A coherent color treatment consistent with the channel.
- What must not appear: unwanted text, watermarks, logos, fake interfaces, distorted anatomy, irrelevant objects, or contradictory details.

Do not overload every prompt with irrelevant cinematic jargon. Choose details that materially improve this particular image. Keep the intended image-generator instruction in one self-contained prompt block.

## 1. Understand the script before writing prompts

1. Read the complete final script and use the actual voiceover as the timing reference when available.
2. Identify the narrative beats, not just individual sentences.
3. Determine the visual purpose of each beat: establish, humanize, explain, contrast, reveal, show consequence, or transition.
4. Decide whether the beat needs a generated still image, supplied footage/image, a reusable character asset, or a graphic/animation that the editing environment can create directly.
5. Request a generated image only when it adds meaningful story value. Avoid unnecessary image volume, repeated compositions, and images that do not add anything beyond the narration.
6. Group adjacent narration into a single visual when one well-designed image can cover the beat; create a new image when the subject, action, location, time, or meaning materially changes.

## 2. Numbering and handoff format

Create a sequential image list: **Image 1, Image 2, Image 3...** Numbers must remain stable from the prompt pack through upload, storyboard, and edit.

For each required image, show:
- **Image number and short scene name**
- **Narration / scene timing** (use real voiceover timing when available; otherwise label timing as pending)
- **Why this image is needed** (one short sentence)
- **Selected format** (16:9 or 9:16)
- **Ready-to-paste prompt** in its own copyable code block
- **Continuity note**, only if a recurring character, location, or prop must match another image

Write prompts individually, not as one giant prompt that asks the generator to create a collage or multiple numbered panels. Each image prompt should request exactly one finished image unless a deliberate storyboard/contact sheet is explicitly requested.

Use simple matching filenames when guiding the user, such as `Image 1.png`, `Image 2.png`. Do not require the user to rename the final video; the separate exact voiceover filename contract still applies to the MP4.

After presenting the image pack, pause and ask the user to upload the generated images with the matching image numbers. Do not proceed as if the requested images are already available. If the user uploads images in a batch, map them by filenames/order and confirm any ambiguity rather than guessing.

## 3. Prompt construction requirements

Each prompt must be:
- **Story-specific:** name the actual subject, action, and context from the script. Avoid vague language such as “a dramatic scene about money” or “a person feeling worried.”
- **Visually decisive:** specify one clear focal subject/action and a readable composition.
- **Production-ready:** include framing, camera perspective, lighting, environment, texture, and mood where relevant.
- **Format-aware:** explicitly state 16:9 landscape or 9:16 portrait and describe how the frame should be composed. Do not just append an aspect-ratio label to an otherwise unadapted prompt.
- **Brand-aware:** follow the relevant channel profile. Do not mix channel styles.
- **Continuity-aware:** reuse the same detailed character description and reference-image instructions for recurring fictional characters. State when the user should provide a previously generated character reference to the image generator.
- **Generator-friendly:** use clear natural-language instructions, not hidden parameters or unsupported syntax. Do not claim a prompt guarantees exact output.
- **Clean:** explicitly prohibit unintended text, captions, watermarks, logos, signatures, UI elements, and gibberish when they are not part of the intended image.

Never ask an image generator to render essential financial text, exact numbers, charts, labels, logos, or readable documents as pixels. For American Wallet, create those elements in the video editor as editable graphics using only wording and values already present in the supplied script/assets. A generated illustrative prop document must be generic and must not imitate an authentic government or financial record.

## 4. American Wallet prompt direction

Load and follow `references/american-wallet-style.md`.

Prompts should create cinematic, photorealistic American finance-documentary imagery:
- Believable American people, homes, workplaces, stores, banks, public environments, and everyday financial situations.
- Specific observable action rather than posed stock-photo expressions.
- Naturalistic documentary lighting, realistic materials, nuanced emotion, restrained grading, and visual depth.
- Channel graphic identity: Deep Navy `#14263D` and Warm Ivory `#F5F1E8`. These are brand colors for designed graphics and selected visual accents; do not force every real-world photograph into an artificial two-color treatment.
- Use financial objects only when relevant to the exact story beat. Avoid generic piles of cash, floating dollar signs, random calculators, and meaningless paperwork.
- Never fabricate legible government forms, official seals, named institutions' documents, account statements, exact figures, headlines, quotations, or logos. Prefer neutral, non-readable illustrative props when a document is only atmospheric.
- Do not create a photorealistic depiction of a real public figure or imply an invented scene is authentic archival evidence. If a real person is discussed, use a generic illustrative person unless the user supplies an approved image/reference for that person.

## 5. Ninety Sense prompt direction

Load and follow `references/ninety-sense-style.md` and `references/ricks-clips-visual-system.md`.

Prompts must follow Ninety Sense's own stylized mixed-media visual identity:
- Stylized 3D environments, props, lighting, and character bodies.
- Integrated flat 2D expressive face/head graphics, not generic photorealistic human faces.
- Strong readable physical action that makes the psychological or emotional beat visible.
- Original recurring characters with consistent body proportions, outfits, identifying colors, and face treatment.
- Emotionally expressive staging, deliberate composition, and cinematic lighting without drifting into generic live-action imagery.
- Never recreate identifiable third-party channel characters or copy a creator's exact designs.

## 6. Selected aspect ratio is mandatory

Use the one format selected for this production, as defined in `references/output-contract.md`.

**For 16:9 landscape:** describe a widescreen composition with deliberate horizontal staging, environmental context, layered foreground/midground/background, and subject placement that uses the frame. Do not simply put a vertical portrait in the center of a wide canvas.

**For 9:16 portrait:** describe a vertical composition with a clear primary subject, deliberate top-to-bottom staging, appropriate headroom/footroom, and space for any planned captions or graphics. Do not simply crop a landscape scene.

The prompt pack must repeat the selected format for every image so the user can generate the correct composition. One project uses one selected format only.

## 7. Image count and quality control

- Request the minimum number of distinct images needed for a strong edit, not one image per sentence.
- Do not pad the prompt pack with near-duplicate angles or variations unless the edit genuinely needs them.
- Prefer a few carefully designed, high-value images over a large collection of generic filler.
- If a scene can be created more clearly with motion graphics, typography, a chart, or an existing supplied asset, do not request a generated image for it.
- Before handing over prompts, review every prompt against the actual script, selected format, channel profile, character continuity, and intended edit use.
- If a prompt contains an unprovided fact, invented exact text, or unsupported visual claim, remove it.
- If an image result uploaded by the user does not match its prompt or scene, explain the mismatch and request a correction or decide whether it can be repurposed honestly.

## 8. Required completion behavior

When the image-generation tool is not available or the user has not asked Claude to use it:
1. Finish the storyboard and identify only the images that are truly needed.
2. Produce the complete numbered ready-to-paste prompt pack.
3. Clearly state that these are prompts, not generated images.
4. Pause for the user's generated image uploads.
5. Resume editing after the required images are received and inspected.

Never claim the video is complete while required images are still pending. Never make a paid image-generation API a prerequisite for this workflow.
