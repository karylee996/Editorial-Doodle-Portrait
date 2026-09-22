# Editorial-Doodle-Portrait

A portrait-generation Skill for turning a single uploaded photo into a custom **photography × hand-drawn doodle × editorial design** artwork.

## Core behavior

The Skill does not apply one fixed visual template.

It first analyzes the uploaded image, then automatically selects the most suitable direction:

- **Fashion Paint** — clothing-led wax crayon / oil pastel treatment
- **Identity Doodle** — context-driven hand-drawn symbols based on visible objects or activity
- **Graphic Pop** — abstract editorial graphics for visually simple portraits
- **Travel Doodle** — place-aware graphics when a recognizable travel context exists

It may lightly blend two directions, but one style must remain dominant.

## Key rule

> Preserve the real person. Simplify the world. Add only art that belongs to the photograph.

The face stays primarily photographic and recognizable. The background is intentionally simplified, with only meaningful environmental clues retained.

## Usage

Upload one portrait or lifestyle photo and ask:

> 使用 Editorial-Doodle-Portrait，根据这张照片自动判断最适合的风格并生成。

Or:

> Use Editorial-Doodle-Portrait. Analyze this photo, choose the strongest visual direction automatically, simplify the background, and create the final artwork.

See `SKILL.md` for the full workflow and prompt rules.
