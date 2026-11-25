# Project status

## Current direction
Ninety Sense uses an original animated visual system informed by the broad visual grammar of Ricks Clips: stylized 3D environments/actions combined with expressive flat 2D face graphics. This is not a request to copy its scripts, characters, footage, music, or branding.

## Implemented
- Replaced generic core instructions with an execution-focused voiceover-to-video skill.
- Added a detailed Ninety Sense visual-system reference.
- Updated the Ninety Sense channel profile to use the visual system.
- Kept American Wallet separate.
- Added explicit rules against placeholder assets and false claims of rendering or quality control.

## Not yet validated
- End-to-end production using the user's actual Claude tools.
- Character continuity and scene quality across a complete Short.
- Successful final video export and playback review.

## Validation target
Run one Ninety Sense Short using only its final script and voiceover. Review the actual MP4, then improve the instructions based on observed failures. Do not add more architecture until this test passes.


## Image-prompt workflow update
- Added a shared image-prompt workflow for American Wallet and Ninety Sense.
- Claude must interpret the complete script/story and produce specific, ready-to-paste image prompts for each genuinely required image.
- The user generates images in their chosen image generator and uploads them by stable Image 1, Image 2, etc. labels.
- No connected image-generation API or new paid subscription is required.
- End-to-end prompt quality and manual asset handoff still require validation with actual Claude tools and user-generated images.
