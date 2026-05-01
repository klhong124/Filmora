---
name: create-character
description: Create consistent AI video character configuration notes for this Obsidian YouTube vault. Use when the user asks to create a character, character config, character sheet, reusable protagonist, or mentions /create-character, consistent character, Filmora, AI video, image prompts, or visual continuity.
---

# Create Character

## Purpose

Create a detailed character configuration note that keeps an AI-generated character visually consistent across 15-second vertical Filmora scenes, clips, and thumbnails.

## Workflow

1. Confirm or infer the character's role, story genre, age range, tone, and visual style.
2. Create a new markdown note in `06-Characters/` using this filename pattern:
   `Character-Name.md`
3. If the character belongs to a specific story, link the story note in `02-Stories/`.
4. Define stable identity anchors first: face, body, hair, clothing, palette, props, silhouette, and recurring expression.
5. Add reusable positive prompts, negative prompts, and scene variation prompts.
6. Include continuity rules that scripts must reuse when the character appears.

## Output Requirements

Every character config should include:

- Status block with role, genre, related story, and visual style.
- Core identity summary in one paragraph.
- Fixed visual anchors that should not change between scenes.
- Wardrobe and prop rules.
- Facial expression and body language notes.
- Color palette.
- Voice and personality notes if the character speaks.
- Master prompt for image/video generation.
- Negative prompt.
- Scene variation prompts for common shot types.
- Filmora continuity notes for editing.
- Consistency checklist.

## Character Note Format

Use this structure:

````markdown
# [Character Name]

## Status

- Stage: character locked
- Role:
- Story:
- Genre:
- Visual style:
- Related config: [[03-Video-Configs/Default-Video-Config]]

## Core Identity

[One paragraph that describes who the character is and what must remain recognizable.]

## Fixed Visual Anchors

- Face:
- Age range:
- Body:
- Hair:
- Eyes:
- Skin:
- Silhouette:
- Clothing:
- Props:
- Color palette:
- Recurring expression:

## Personality And Voice

- Personality:
- Desire:
- Fear:
- Speaking style:
- Voice direction:

## Master Character Prompt

```text
[Character name], [age range], [face details], [hair], [eyes], [body/silhouette], wearing [fixed outfit], carrying [fixed prop], [color palette], [genre/style], cinematic storybook realism, consistent character design, high detail, soft film grain, vertical 9:16, 720x1280
```

## Negative Prompt

```text
different face, different hairstyle, different outfit, changed age, extra fingers, distorted face, bad anatomy, low quality, blurry, watermark, logo, unreadable text
```

## Shot Prompts

### Close-Up

```text
[Master character details], close-up portrait, emotional eyes, cinematic lighting, shallow depth of field, vertical 9:16, 720x1280
```

### Medium Shot

```text
[Master character details], medium shot, visible outfit and prop, atmospheric background, cinematic composition, vertical 9:16, 720x1280
```

### Wide Shot

```text
[Master character details], full body visible, clear silhouette, environment establishes scale, cinematic wide shot, vertical 9:16, 720x1280
```

### Thumbnail Shot

```text
[Master character details], strong readable emotion, dramatic lighting, clean background separation, YouTube Shorts thumbnail composition, vertical 9:16, 720x1280
```

## Filmora Continuity Notes

- Reuse the same character image as reference whenever possible.
- Keep outfit, hair, eye color, and key prop unchanged unless the story explicitly changes them.
- Use short vertical close-ups, fast reaction cuts, and simple transitions for 15-second Shorts.
- Avoid cutting between two shots where the face changes too much.

## Consistency Checklist

- [ ] Face shape is stable.
- [ ] Hair style and color are stable.
- [ ] Outfit is stable.
- [ ] Key prop is present when needed.
- [ ] Color palette matches the story.
- [ ] Character still reads clearly in thumbnail size.
- [ ] Prompts can be reused in story scene notes.
````

## Prompting Guidance

- Keep the master prompt compact enough to reuse in every scene.
- Repeat identity anchors exactly across prompts.
- Avoid vague descriptors like "beautiful" unless paired with concrete features.
- Use one fixed outfit for most videos; create a separate "alternate outfit" section only when needed.
- For AI video tools, describe motion separately from identity so the model does not redesign the character.
