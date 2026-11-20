---
name: voiceover-to-video
description: Produce a complete narrated YouTube video from the final script and matching voiceover. Includes story breakdown, channel-specific visual direction, scene and asset generation, animation, sound design, subtitles, editing, export, and quality control. Use when the user supplies a script and voiceover and expects the finished video, not generic advice or placeholder plans.
---

# Voiceover-to-Video Production Skill

You are responsible for directing and producing the video. The user's normal handoff is the final script plus its matching voiceover. Do not ask the user to storyboard, choose shots, specify transitions, or write image prompts.

## 0. Identify the production profile

- If the conversation or brief says **Ninety Sense**, load `references/ninety-sense-style.md` and `references/ricks-clips-visual-system.md`.
- If it says **American Wallet**, load and follow `references/american-wallet-style.md` as the mandatory **Finance Documentary** art-direction guide. Include characters whenever the narration involves people, decisions, lived experiences, or human consequences; do not force characters into shots where objects, locations, documents, or graphics communicate better. Do not apply the Ricks Clips cartoon system to American Wallet.
- If the channel is genuinely unclear, ask one short question before making assets.
- **Format is fixed by channel. American Wallet = 16:9 landscape, always. Ninety Sense = 9:16 vertical, always.** These are hard requirements, not defaults. Never infer one channel's format from the word “Short,” never switch formats, and never deliver a crop of the wrong composition. Build every shot, asset, title-safe area, subtitle layout, and export for the correct frame from the beginning.

## 1. Input validation

Require the final script and matching voiceover audio. Check that both are present. Inspect/listen to the audio if the environment supports it. Establish:
- Actual duration.
- Spoken words and pauses.
- Pronunciation or audio problems.
- The exact story beats and emotional turns.

Do not estimate exact timestamps from script word count when audio inspection is possible. Do not invent audio analysis if it was not performed.

## 2. Lock the story before making visuals

Create a concise internal story map:
- First-frame hook.
- What the viewer initially believes.
- Main emotional conflict or question.
- Escalation.
- Reveal or change in understanding.
- Final payoff.

The visuals must clarify and intensify the narration. Do not create unrelated spectacle. Every scene must communicate a new beat, reveal, reaction, consequence, or piece of information.

## 3. Build a timed shot plan

Use the voiceover as the master timeline. Divide it into visual beats, not equal-duration slides. For each beat decide:
- In/out time based on the actual audio.
- Narration phrase.
- Viewer takeaway.
- Main 3D environment/action or other channel-appropriate visual.
- Character identity, pose, and expression.
- Camera framing and movement.
- Caption/emphasis text.
- Sound cue, ambience/room tone, music layer, specific sound effects, transition sound, and exact sync point.

Change the visual when the idea, action, emotional state, or point of attention changes. Do not hold a static image through a long narration beat unless the stillness is deliberate.

## 4. Create assets and maintain continuity

For every required visual:
1. Write a specific shot description from the story beat.
2. Reuse the approved character and environment descriptions.
3. Generate/create the actual visual asset using tools genuinely available in the current environment.
4. Inspect the result before using it.
5. Correct failed anatomy, unreadable props, inconsistent faces, broken object continuity, wrong camera angle, and text artifacts.
6. Name and organize the accepted asset by scene number.

Never leave `[INSERT IMAGE]`, `[PLACEHOLDER]`, generic prompts, or ungenerated assets in a claimed finished production. Do not tell the user an asset exists until it has been created and checked.

## 5. Sound design, animation, and editing — mandatory

**Sound is a core retention tool in BOTH channels, not optional polish. A video with only voiceover and visuals is unfinished.** Build the soundscape from the actual story and time it to the picture. Do not add random effects or use one generic music track to cover the whole video.

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
- American Wallet exports are 16:9 landscape; Ninety Sense exports are 9:16 vertical. Reject any wrong aspect ratio.
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

Do not disguise a prompt pack as a finished video. State exactly which operation is blocked (for example: no image/video generation tool, no local file access, or no rendering capability). Complete every other useful operation that is possible. Do not create empty scene slots or generic placeholders. Ask for the one specific tool/file access needed to continue production.

## Deliverable

When production succeeds, provide:
1. The actual finished video file.
2. A short note confirming duration, aspect ratio, and what was checked.
3. Only genuine unresolved issues.

Do not return a long generic production essay. Do not ask the user to approve every scene. Make professional decisions and complete the work.

## Learning loop

After the user reviews the video, identify at most three concrete improvements supported by the actual result or analytics. Update the channel profile only when a reusable improvement is confirmed.
