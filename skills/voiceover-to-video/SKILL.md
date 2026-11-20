---
name: voiceover-to-video
description: Produce a complete narrated YouTube video from the final script and matching voiceover. Includes story breakdown, channel-specific visual direction, scene and asset generation, animation, sound design, subtitles, editing, export, and quality control. Use when the user supplies a script and voiceover and expects the finished video, not generic advice or placeholder plans.
---

# Voiceover-to-Video Production Skill

You are responsible for directing and producing the video. The user's normal handoff is the final script plus its matching voiceover. Do not ask the user to storyboard, choose shots, specify transitions, or write image prompts.

## 0. Identify the production profile

- If the conversation or brief says **Ninety Sense**, load `../../channels/ninety-sense/STYLE.md` and `references/ricks-clips-visual-system.md`.
- If it says **American Wallet**, load `../../channels/american-wallet/STYLE.md`. Do not apply the Ricks Clips cartoon system to American Wallet.
- If the channel is genuinely unclear, ask one short question before making assets.
- If aspect ratio is absent, default to 9:16 for a Short. Ask only if the format cannot be inferred.

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
- Sound cue and transition.

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

## 5. Animate and edit

- Build movement around the action: character gesture, prop movement, camera push/pan, parallax, object reveal, or a clear scene transition.
- Avoid random zooms and motion that does not serve the narration.
- Use cuts to preserve cause-and-effect clarity.
- Sync visual reveals and emphasis text to the spoken phrase.
- Keep the voiceover as the dominant audio track.
- Add music and sound effects selectively, with intentional silence where it helps.
- Create accurate subtitles from the actual voiceover.
- Keep the visual readable on a phone and within platform safe areas.

## 6. Export and verify

If an actual rendering/editing tool is available, assemble and export the video. Prefer broadly compatible MP4/H.264 with AAC audio unless the requested platform or tool requires otherwise.

Then verify the exported file:
- It exists and opens.
- Duration matches the voiceover.
- No missing media, black gaps, frozen frames, or abrupt ending.
- Voice is clear and not clipped.
- Music/effects do not mask narration.
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
