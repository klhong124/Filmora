---
name: create-script
description: Create Filmora-ready AI storytelling video scripts for this Obsidian YouTube vault. Use when the user asks to create a script, generate a story video script, prepare a Filmora script, or mentions /create-script, Filmora, narration, scene prompts, or YouTube story videos.
---

# Create Script

## Purpose

Generate only a Filmora-ready prompt for an AI story video.

## Core Rule

When creating or regenerating a story, output the Filmora prompt only. Do not include status blocks, loglines, hooks, character sections, scene-plan tables, upload metadata, image prompt banks, production notes, explanations, or checklists unless the user explicitly asks for them.

## Language And Length

- Write in Traditional Chinese unless the user requests another language.
- Keep the complete Filmora prompt 2000 words or fewer.
- Aim to use most of the 2000-word cap for richer, more accurate prompts. Do not produce a short prompt when more useful production detail can be added.
- Only stay far below the cap when the user explicitly asks for a very short video, a tight word count, or a minimal prompt.
- The saved story note should contain only the prompt text needed for Filmora.

## Prompt Requirements

The Filmora prompt must be accurate and directly usable:

- Build each text-to-video scene prompt with this formula: Subject + Action + Scene + Camera Movement + Lighting + Style.
- Name the exact characters in every scene.
- Repeat important visual identifiers for consistency, such as species, clothing, accessories, colors, and props.
- Describe visible actions, setting, camera movement, mood, lighting, sound effects, and music.
- Do not add any text on the video. Do not include titles, title cards, subtitles, captions, labels, lower thirds, or text overlays unless the user explicitly asks for on-screen text.
- Prefer detailed, production-ready scene prompts that get close to the word cap while staying clear, specific, and usable.
- Expand each scene with concrete production details: foreground, background, character position, facial expression, body posture, prop placement, camera angle, lens distance, transition, pacing, lighting direction, color palette, and sound cue.
- Keep character continuity explicit by repeating signature traits every time a character appears, especially colors, accessories, face shape, clothing, props, and emotional expression.
- Use clear timestamps or numbered scene beats when useful.
- Avoid vague filler. Do not rely on words like "beautiful", "cinematic", or "emotional" unless paired with concrete visual details.
- Keep narration short and paste-ready for voice generation.
- Include one recurring sound motif when it helps continuity.

## Effective Video Prompt Formula

For every scene, make the prompt concrete enough that Filmora can generate the intended video without guessing:

- Subject: Describe who or what is in focus, including appearance, facial expression, body posture, clothing, accessories, species, color, and key props.
- Action: State the visible action clearly. Use simple, physical actions that can plausibly happen in the scene.
- Scene: Describe the foreground, background, location, environment, and any important objects.
- Camera Movement: Specify the shot and movement, such as close-up, wide shot, slow push-in, zoom in, zoom out, pan left, tracking shot, handheld subtle shake, aerial shot, or focus shift.
- Lighting: Describe the light source and mood, such as warm window light, moonlight, soft backlight, spotlight, cold blue dawn, or golden sunrise.
- Style: State the visual style only when useful, and pair it with concrete details. Avoid style-only prompts.

When the prompt is too short, add detail in this order:

1. Character continuity: repeated visual traits, accessories, expression, posture, and scale.
2. Action clarity: exact physical movement, start position, end position, and reaction.
3. Environment: foreground props, background elements, surface textures, weather, and time of day.
4. Camera: framing, angle, movement, speed, focus, and transition into the next shot.
5. Lighting and color: direction of light, contrast, warmth or coolness, shadow behavior, and palette.
6. Sound: sound effects, music change, silence, and recurring motif.

## Prompt Quality Rules

- Prefer simple words and direct sentence structure. Break complex actions into smaller scene beats.
- If the scene changes, explicitly write "切到" or "switch to" and describe the new scene again.
- Keep movement physically consistent. Do not ask for impossible movement unless the story intentionally needs fantasy logic.
- Make the prompt match the actual visible content. Do not introduce characters, locations, props, or backgrounds that are not meant to appear.
- Avoid exact counts when visual consistency may be difficult, unless the number is important to the story. Use "幾個", "一排", or "許多" when exact count is not critical.
- Use degree words for action intensity when helpful, such as slowly, gently, quickly, subtly, or dramatically.
- If using image-to-video or reference images, describe only motion, background movement, and camera movement that fit the starting image.
- Mention sound effects and music separately from visual generation when needed, because some AI video models may not generate sound directly.
- Do not pad with generic adjectives. Extra length should improve generation accuracy, continuity, timing, or editability.
- For short videos, use fewer scenes but make each scene dense with exact visual, camera, and sound instructions.

## Output Format

Use plain markdown containing only the Filmora prompt. A concise structure like this is allowed:

```markdown
1. 0:00-0:10 [Subject + Action + Scene + Camera Movement + Lighting + Style. Sound/music.]

2. 0:10-0:25 [Subject + Action + Scene + Camera Movement + Lighting + Style. Sound/music.]

...
```

Do not add separate metadata or notes after the prompt.
