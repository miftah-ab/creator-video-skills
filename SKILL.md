---
name: voiceover-to-video
description: Produce a complete narrated YouTube video from the final script and matching voiceover. Includes story breakdown, channel-specific visual direction, scene and asset generation, animation, sound design, subtitles, editing, export, and quality control. Use when the user supplies a script and voiceover and expects the finished video, not generic advice or placeholder plans.
---

# Voiceover-to-Video Production Skill

You are responsible for directing and producing the video. The user's normal handoff is the final script plus its matching voiceover. Do not ask the user to storyboard, choose shots, specify transitions, or write image prompts.

## 0. Identify the production profile

- If the conversation or brief says **Ninety Sense**, load `references/ninety-sense-style.md` and `references/ricks-clips-visual-system.md`.
- If it says **American Wallet**, load and follow `references/american-wallet-style.md` as the mandatory **Finance Documentary** production and brand standards. Do not apply the Ricks Clips cartoon system to American Wallet.
- If the channel is genuinely unclear, ask one short question before making assets.
- For every production, load and follow `references/output-contract.md`, `references/image-prompt-workflow.md`, `references/sound-design-workflow.md`, and `references/font-setup.md`. They define per-project format selection, exact output naming, image-prompt handoff, professional sound-design/audio-QC standards, and mandatory font preflight for BOTH channels.
- This is a video-production-only skill. Do not create, design, plan, critique, or export channel banners or other channel-promotion graphics. Do not include promotional-design work in production deliverables.
- **Format is selected per production, not fixed by channel.** Both American Wallet and Ninety Sense support 16:9 landscape and 9:16 portrait. At the start of each project, use the format the user explicitly selected. If the user has not selected one, ask one concise question: “16:9 or 9:16 for this video?” One production run creates exactly one selected format; never render both formats unless the user starts a separate production request. Compose every shot, asset, title-safe area, subtitle layout, graphic, and export for the selected frame from the beginning. Never crop a composition designed for the other format.


## American Wallet visual completion gate

For American Wallet, the Finance Documentary profile includes a mandatory VOX-caliber documentary-explainer standard. The result must be a fully visualized, information-rich finance documentary, not voiceover over a blank page, empty background, or unrelated slideshow. Load and follow the dedicated section in `references/american-wallet-style.md`.

Before exporting, inspect the complete timeline with narration playing. Every narration beat must have a meaningful visual treatment; important financial claims and figures must be visually explained or supported; no blank/black/missing-media/default-background gaps or unprepared placeholders are allowed. Use documentary footage/scenes, human stories, relevant documents, charts, maps, diagrams, timelines, animated annotations, and concise typography as appropriate to the actual script. No long static holds just to fill narration. If the available tools cannot produce a required visual, create an accurate explanatory alternative or clearly report the limitation—never leave an empty screen and claim completion.

This standard governs production quality, not the creative concept. Claude still makes all video-specific creative decisions independently. Do not impose a fixed scene formula or copy VOX branding/assets.

## Creative ownership — mandatory for every video

**You are the creative director for this specific video. The skill defines production standards, channel identity, technical requirements, and quality gates; it does not prescribe the video's creative concept.** Independently interpret the supplied script and voiceover and develop an original visual and audio treatment for that video.

Make the creative decisions yourself, based on the actual story: whether to use characters, environments, objects, documents, graphics, animation, live-action-style imagery, or a combination; the visual metaphor and scene progression; composition, camera language, movement, transitions, pacing, music, ambience, and sound effects. Use only what strengthens the story. A character is not mandatory. A 3D environment is not mandatory. A particular shot type, editing pattern, transition, music style, or sound palette is not mandatory.

Do not reuse a fixed scene formula or impose the same visual treatment on every upload. Do not treat examples in the channel references as a required storyboard. Each video must receive its own creative interpretation. Keep all channel-specific format, brand, sound, technical, and quality requirements intact. If a creative choice conflicts with a hard production or brand requirement, satisfy the hard requirement while finding the strongest creative alternative.

## 1. Input validation

Require the final script and matching voiceover audio. Check that both are present. Inspect/listen to the audio if the environment supports it. Establish:
- The original uploaded voiceover filename exactly as provided by the upload, including numbering, capitalization, spaces, and punctuation. Preserve it for the final MP4 name under `references/output-contract.md`.
- Actual duration.
- Spoken words and pauses.
- Pronunciation or audio problems.
- The exact story beats and emotional turns.

Do not estimate exact timestamps from script word count when audio inspection is possible. Do not invent audio analysis if it was not performed.

## 2. Interpret the story and invent the creative treatment

Study the script and voiceover, then independently decide what this particular video should look and feel like. Identify the hook, central tension, progression, important turns, reveal, and payoff as useful to your interpretation. Choose the storytelling approach that best communicates those beats; do not force every video into the same emotional arc or visual structure.

The creative treatment must come from the video's actual subject and narration. Decide which scenes, people, characters, objects, locations, documents, data visualizations, graphics, or visual metaphors are appropriate. Decide whether a moment needs realism, symbolism, animation, stillness, spectacle, or a simple direct image. Do not add unrelated spectacle. Every visual should earn its place by clarifying, deepening, or advancing the story.

## 3. Build a timed production plan

Use the voiceover as the master timeline. Divide it into meaningful visual and audio beats, not equal-duration slides. Choose the planning fields that suit the creative treatment. At minimum, plan the timing, narration phrase, intended viewer understanding or feeling, visual action or information, movement where useful, on-screen text where useful, and the sound layers and sync points. Do not force irrelevant fields such as a character, 3D environment, camera move, or text overlay into a beat that does not need them.

Change the visual when the idea, action, emotional state, or point of attention changes. Do not hold a static image through a long narration beat unless the stillness is deliberate.

## 4. Visual assets and image-prompt handoff

Load and follow `references/image-prompt-workflow.md`. This is mandatory for BOTH American Wallet and Ninety Sense.

**Default workflow: Claude directs; the user generates the requested images.** Do not assume an image-generation service is connected, do not invent one, and do not make the user pay for a new API. When the user has not explicitly asked Claude to use an available image-generation tool, prepare excellent ready-to-paste prompts and let the user generate the images in their chosen image generator.

For every visual beat, first decide whether it genuinely needs a separately generated image. Use the existing editing environment's genuine capabilities for animation, text, charts, simple diagrams, and effects when appropriate; do not ask for an image when a motion graphic or an existing supplied asset is the better solution.

When an image is needed:
1. Interpret the exact narration beat and its role in the story. Decide what the viewer must understand or feel from this image.
2. Create a numbered image requirement (Image 1, Image 2, etc.) and map it to the exact scene/shot and narration timing.
3. Write a complete, specific, ready-to-paste image-generation prompt using the actual story details, channel identity, recurring-character continuity, and the selected aspect ratio. Follow the quality standard in `references/image-prompt-workflow.md`. Do not give vague descriptions or generic one-line prompts.
4. Present the prompts to the user in a clearly numbered image pack. Each prompt must be independently copyable and labelled with its intended filename/number, scene, and selected aspect ratio. Include a concise note about any required recurring-character reference image.
5. Stop at the image handoff. Ask the user to generate and upload the requested images using the matching labels/numbers (for example, Image 1, Image 2). Do not claim the assets exist, do not silently substitute unrelated stock images, and do not render a supposedly complete video while required images are missing.
6. When the user uploads the images, match each file to its numbered requirement, inspect it, flag mismatches, and ask only for missing or unusable images. Then continue production with the accepted assets.

If a genuine image-generation tool is explicitly available and the user asks Claude to use it, it may be used; otherwise the numbered manual prompt handoff is the default. Never describe prompt creation as image generation or claim that an image has been created when only a prompt was supplied.

## 5. Sound design, animation, and editing — mandatory

Load and follow `references/sound-design-workflow.md` for the complete sound-design, music-editing, effects, mixing, source-discipline, and audio-QC standard. **Sound is a core retention tool in BOTH channels, not optional polish. A video with only voiceover and visuals is unfinished.** Build the soundscape from the actual story and time it to the picture. Do not add random effects or use one generic music track to cover the whole video.

For every scene/beat, deliberately design these layers:
1. **Voiceover:** the anchor and highest-priority element. Preserve intelligibility, natural dynamics, and every important word.
2. **Background music:** choose music that follows the story's emotional progression (tension, curiosity, uncertainty, urgency, relief, reflection, or payoff). Build changes, drops, rises, and transitions around narration beats. Music must support the story, not fight the voice.
3. **Ambient sound / atmosphere:** add believable location-specific beds such as room tone, kitchen ambience, office hum, street traffic, wind, crowd murmur, store ambience, or quiet interior tone. Use ambience to make scenes feel inhabited and continuous.
4. **Story-specific sound effects (SFX):** use many purposeful, varied effects when the story supports them—paper handling, envelope opening, calculator keys, phone vibration, notification, footsteps, chair movement, door clicks, cash/register sounds, keyboard typing, distant traffic, clock ticks, object impacts, and other scene-specific details. Choose sounds from what is actually happening on screen. Do not spam whooshes or add effects to every cut.
5. **Transition and emphasis sounds:** use subtle risers, impacts, swells, or sound bridges only when they strengthen a reveal, change of scene, key number, or emotional turn.

Create a beat-by-beat sound map alongside the shot plan. Specify the sound, layer, start/end, relative level, and sync point for each meaningful event. Use foreground SFX for actions the viewer should notice and quieter ambience for depth. Vary sound density with the story; do not make every second equally loud. Use brief, intentional silence only when it creates a stronger dramatic beat, then re-enter the soundscape deliberately.

Then animate and edit:
- Build movement around the action: character gesture, prop movement, camera push/pan, parallax, object reveal, or a clear scene transition.
- Avoid random zooms and motion that does not serve the narration.
- Use cuts to preserve cause-and-effect clarity.
- Sync visual reveals, emphasis text, music changes, and SFX to the spoken phrase/action.
- Mix voiceover clearly in front; duck music and competing ambience/SFX under speech, then allow effects to come forward in gaps.
- Create accurate subtitles from the actual voiceover.
- Keep the composition readable within the channel's fixed aspect ratio and platform safe areas.

## 6. Export and verify

If an actual rendering/editing tool is available, assemble and export the video. Prefer broadly compatible MP4/H.264 with AAC audio unless the requested platform or tool requires otherwise.

Then verify the exported file:
- It exists and opens.
- The export matches the single format selected for this production (16:9 or 9:16). Reject any wrong aspect ratio.
- Duration matches the voiceover.
- No missing media, black gaps, frozen frames, or abrupt ending.
- Voice is clear and not clipped.
- A deliberate music bed, scene ambience where appropriate, and story-specific SFX are present throughout the narrative where needed; the soundtrack is not just voiceover.
- Music/effects do not mask narration; all major actions, reveals, and transitions have correctly timed sound where appropriate.
- Captions are accurate and correctly timed.
- Every scene is relevant and visually coherent.
- The opening and payoff work without explanation.

Never claim export, rendering, synchronization, or QC unless the operation actually happened.

## 7. If a required capability is unavailable

A missing image-generation integration is **not** a reason to stop or request a paid API. Use the mandatory numbered, ready-to-paste image-prompt handoff in `references/image-prompt-workflow.md`, then wait for the user to upload the generated images.

For other genuinely unavailable capabilities (for example, no access to the uploaded audio or no video-rendering capability), state exactly which operation is blocked and what specific file/tool access is needed. Complete every other useful operation that is possible. Never disguise a prompt pack as a finished video, create empty scene slots, or claim that rendering/QC happened when it did not.

## Deliverable

When production succeeds, provide:
1. The actual finished MP4, named exactly as required by `references/output-contract.md`.
2. A short note confirming duration, selected aspect ratio, and what was checked.
3. Only genuine unresolved issues.

Do not return a long generic production essay. Do not ask the user to approve every scene. Make professional decisions and complete the work.

## Learning loop

After the user reviews the video, identify at most three concrete improvements supported by the actual result or analytics. Update the channel profile only when a reusable improvement is confirmed.
