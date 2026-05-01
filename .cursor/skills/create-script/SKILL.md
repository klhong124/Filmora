---
name: create-script
description: Create Filmora-ready AI storytelling video scripts for this Obsidian YouTube vault. Use when the user asks to create a script, generate a story video script, prepare a Filmora script, or mentions /create-script, Filmora, narration, scene prompts, or YouTube story videos.
---

# Create Script

## Purpose

Create a complete AI storytelling video script that can be passed into Filmora for video production and later uploaded to YouTube.

## Workflow

1. Choose or confirm the story idea, target length, genre, and emotional tone.
2. Create a new markdown note in `02-Stories/` using this filename pattern:
   `NNN-Short-Story-Title.md`
3. Use [[03-Video-Configs/Default-Video-Config]] as the baseline unless the user gives different settings.
4. Write the script in short narration blocks that are easy to paste into voice generation tools.
5. Break the story into Filmora-friendly scenes with timing, visuals, audio, and editing notes.
6. Add upload metadata so the note can move directly into production.

## Output Requirements

Every generated story script should include:

- Status block with target length, format, genre, emotion, and related config.
- Logline: one sentence.
- Hook: first 5-10 seconds.
- Characters with visual design notes.
- Filmora scene plan with estimated timestamps.
- Narration for each scene.
- Visual prompt for each scene.
- Sound and music notes for each scene.
- Image prompt bank.
- Upload metadata: title, alternate title, description, tags, thumbnail concept, pinned comment.
- Production notes for consistency and editing.

## Script Format

Use this structure:

````markdown
# [Story Title]

## Status

- Stage: draft ready
- Target length: [minutes]
- Format: cinematic narrated story
- Genre: [genre]
- Emotion: [emotion]
- Related config: [[03-Video-Configs/Default-Video-Config]]

## Logline

[One sentence story summary.]

## Hook

[First 5-10 seconds of narration or visual question.]

## Characters

- [Name]
  - Role:
  - Desire:
  - Fear:
  - Visual design:

## Filmora Scene Plan

| Scene | Time | Visual | Audio | Edit Notes |
|---|---:|---|---|---|
| 1 | 0:00-0:30 | [visual summary] | [sound/music] | [transition or pacing] |

## Script

### Scene 1: [Scene Name]

Time: 0:00-0:30

Narration:

[Short narration paragraphs.]

Visual prompt:

```text
[AI image/video prompt, 16:9, consistent style]
```

Sound:

- [ambient sound]
- [music direction]
- [effect]

Edit notes:

- [Filmora-specific note: zoom, pan, crossfade, overlay, subtitle, speed, etc.]

## Image Prompt Bank

```text
[Reusable character/location prompt.]
```

## Upload Metadata

- Title:
- Alternate title:
- Description:
- Tags:
- Thumbnail concept:
- Pinned comment:

## Production Notes

- [Consistency, voice, color, pacing, or editing notes.]
````

## Filmora Guidance

- Prefer 6-10 scenes for a 4-8 minute story.
- Give each scene a clear timestamp range.
- Include simple edit notes Filmora can execute: slow zoom, pan left, fade to black, cross dissolve, subtitle emphasis, light leak, film grain, or ambient overlay.
- Keep narration paragraphs short so they can be pasted into TTS tools.
- Keep visual prompts consistent across scenes by repeating character and location descriptors.
- Include one recurring sound motif for the story.

## Quality Checklist

Before finishing, verify:

- [ ] The first 10 seconds have a strong hook.
- [ ] The story has one main character, one desire, and one emotional turn.
- [ ] Every scene has narration, visual prompt, sound notes, and edit notes.
- [ ] The ending has a memorable final image or line.
- [ ] Upload metadata is complete.
- [ ] The note links to the default video config.
