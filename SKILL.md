# Editorial-Doodle-Portrait

## Purpose

Create a custom mixed-media editorial portrait from a single uploaded person photo.

The core principle is:

**Keep the real person recognizable, preserve the real outfit, then redesign the visual world around them.**

Do not apply one fixed doodle template to every image. First analyze the uploaded photo, then choose the most suitable art direction based on the actual visual information in that photo.

---

## Input

Required:
- One uploaded portrait or lifestyle photo containing a clear main person.

Optional:
- User-specified aspect ratio.
- User-specified amount of text.
- User-specified color preference.
- User request to emphasize or suppress a certain style direction.
- User request to preserve clothing with extra strictness.

If no extra instructions are provided, use the automatic analysis workflow below.

---

## Non-negotiable subject rules

Always preserve:
- identity and recognizable facial features
- face shape
- hairstyle
- age impression
- skin tone
- body proportions
- pose
- gaze direction
- hand placement
- clothing silhouette
- clothing structure
- clothing category
- main garment proportions
- original pattern logic such as stripes, checks, color blocking, seams, collar shape, cuffs, pockets, hems, and panel divisions
- original clothing color relationship
- footwear type
- number of people

Do not:
- redesign the face
- turn the face into a cartoon
- change age or gender presentation
- add extra people
- alter the original pose without a clear user request
- invent a profession, hobby, location, personality trait, or life story that is not visible in the photo
- redesign or replace the original outfit
- change the garment category
- destroy the original clothing pattern logic
- overwrite the clothing so heavily that the original shirt, trousers, shoes, or accessories become unrecognizable

### Critical clothing preservation rule

The original clothing must still read as the same real outfit at first glance.

Do not redesign the clothing into a different fashion item.
Do not replace striped clothing with unrelated multicolor abstract patterns.
Do not replace plain garments with invented prints unless the effect is only a light artistic surface overlay.
Do not alter collar shape, sleeve length, cuff placement, pocket placement, seam structure, trouser silhouette, or footwear type.

Any artistic treatment on clothing must remain a surface-level enhancement. It may add contour emphasis, selective color, crayon texture, rough outlines, or partial translucent marks, but it must not create a new garment design.

The face should remain primarily photographic. Artistic treatment should focus on clothing surfaces, silhouette edges, negative space, surrounding graphic elements, and selected environmental clues.

---

## Step 1 — Analyze the source image

Before writing the generation prompt, identify:

1. **Person**
   - framing: headshot / half body / three-quarter / full body
   - pose and gesture
   - expression
   - direction of gaze
   - visual energy: calm / playful / formal / dynamic / casual

2. **Clothing**
   - silhouette
   - garment category
   - dominant colors
   - texture or pattern
   - collar, cuffs, pockets, seams, hems, and panel divisions
   - whether the outfit itself is visually distinctive
   - whether the clothing pattern must be protected strictly

3. **Scene**
   - plain background
   - interior
   - street
   - café
   - work environment
   - travel destination
   - nature
   - studio
   - other

4. **Meaningful visible objects**
   Examples:
   - coffee cup
   - camera
   - laptop
   - book
   - furniture
   - game device
   - sports gear
   - musical instrument
   - recognizable architecture

5. **Color structure**
   - select 2–3 colors already present in the photo
   - add at most 1 complementary accent color by default
   - keep the main palette to roughly 4–5 colors maximum unless the user clearly wants a brighter expressive result

6. **Information density**
   - low
   - medium
   - high

A busy source image should receive fewer added graphics.
A simple source image can support larger and more expressive drawn elements.

---

## Step 2 — Choose the art direction

Choose one primary style. A secondary style may be blended lightly when useful.

### A. Fashion Paint

Use when:
- outfit has a strong silhouette or styling
- person is already visually dominant
- background is simple or secondary
- fashion/editorial energy is stronger than narrative information

Treatment:
- keep the face photographic
- preserve the original clothing structure, silhouette, category, color relationship, and pattern logic
- if the garment contains stripes, checks, seams, panels, pockets, or other visible design logic, keep those features recognizable
- apply expressive crayon, wax pastel, marker, or oil pastel overlays as surface treatment only
- overlays may enhance edges, folds, selected panels, cuffs, collars, hems, pockets, or small garment zones
- allow selective color accents and hand-drawn contour emphasis
- do not replace the garment with a new invented pattern
- do not convert the outfit into a different fashion design
- keep the original outfit readable at first glance
- use large abstract gestures around the body when useful, but keep them visually separate from the clothing construction
- avoid dense text unless the composition clearly benefits from it

Visual keywords:
- fashion editorial
- wax pastel
- oil crayon
- expressive hand coloring
- surface-level garment enhancement
- contour emphasis
- selective color overlay
- handmade imperfection

---

### B. Identity Doodle

Use when:
- the photo clearly shows an activity, profession, hobby, or representative object
- there is enough visible evidence to derive a theme from the image

Treatment:
- translate visible objects or activities into simple hand-drawn symbols
- add a small number of context-relevant words only when justified
- keep icons around the head, shoulders, body silhouette, and negative space
- do not cover eyes, nose, or mouth
- maintain strong hierarchy and breathing room
- preserve clothing exactly as the same outfit

Examples:
- laptop → cursor, brackets, UI windows, keyboard marks
- camera → frame marks, lens circles, film symbols
- coffee → cup sketch, steam lines, simple café notes
- book → page marks, underline strokes, small editorial annotations

Never invent identity claims that are not supported by the photo.

---

### C. Graphic Pop

Use when:
- the source has little narrative information
- background is plain or generic
- no reliable profession, hobby, or location can be inferred
- the main goal is visual impact

Treatment:
- use abstract curves, loops, stripes, geometric marks, hand-drawn stars, waves, short dashes, and bold color blocks
- use asymmetry
- allow graphics to sit behind and partially around the person
- keep the face photographic
- avoid fake narrative symbols or made-up text
- do not allow graphic marks to replace real garment construction or pattern logic

Visual keywords:
- contemporary graphic pop
- playful editorial graphics
- Memphis-inspired shapes
- bold flat marks
- hand-drawn geometric composition

---

### D. Travel Doodle

Use when:
- the photo clearly contains a recognizable destination, building, landscape, or travel context

Treatment:
- retain only the most meaningful environmental clue
- simplify or remove the rest of the background
- derive doodle motifs from the actual place or architecture
- possible additions: building outline, transit-like line, route arrow, place-name fragment, travel marker, simple geographic symbol
- keep the person as the main visual anchor
- preserve the original outfit exactly as the same outfit

Do not overwhelm the portrait with scenery.

---

## Step 3 — Background simplification

Default to a simplified background, but do not simplify so aggressively that the scene loses all useful visual context.

Use this hierarchy:

1. Keep the person intact.
2. Keep 0–2 meaningful environmental anchors by default.
3. Remove or fade secondary furniture, architecture, clutter, signage, tables, wall details, or random objects.
4. Replace discarded background areas with:
   - warm off-white
   - light gray
   - muted cream
   - pale paper texture
   - very soft neutral photographic tone
5. Use hand-drawn graphics to reconnect the simplified space.

For visually busy photos, the final background should usually feel around 50–70% simpler than the source.

However, if the source environment itself contributes strongly to the editorial composition, preserve more of it while still reducing clutter.

Avoid collage overload unless the user explicitly requests a collage treatment.

---

## Step 4 — Garment intervention control

This is a critical control rule.

When artistic treatment affects clothing, choose one of the following levels:

### Level 1 — Minimal garment enhancement

Use when:
- the user wants the original outfit to stay almost fully intact
- the clothing itself is already visually strong

Treatment:
- preserve all original garment colors and patterns
- add only light contour lines, small crayon accents, and subtle textured highlights
- no large recoloring

### Level 2 — Moderate garment enhancement

Use when:
- the user wants a stronger editorial look without changing the outfit

Treatment:
- preserve garment structure, category, and pattern logic
- add visible but partial color overlays
- emphasize seams, folds, pockets, cuffs, hems, and silhouette edges
- allow hand-drawn marks on selected clothing zones
- keep at least 70–80% of the original garment design visually recognizable

### Level 3 — Bold garment enhancement

Use only when:
- the user explicitly wants highly stylized fashion repainting

Treatment:
- keep the original clothing silhouette and key pattern logic visible
- allow stronger color intervention
- however, the result must still clearly read as the same original outfit, not a newly designed garment

Default rule:
Use Level 2 unless the user explicitly requests heavier clothing repainting.

Never allow artistic enhancement to erase the recognizability of the original outfit.

---

## Step 5 — Doodle material language

Preferred media:
- wax crayon
- oil pastel
- marker
- dry brush
- chalk
- colored pencil
- rough ink

Texture should show:
- uneven pressure
- broken edges
- visible grain
- partial fill
- overlapping strokes
- slight misregistration
- occasional overrun beyond contours

Avoid:
- perfect vector outlines
- overly clean digital gradients
- glossy 3D rendering
- smooth clip-art icons
- children's-book cartoon faces
- clothing overlays that behave like a new textile print

---

## Step 6 — Text policy

Text is optional.

Use text only when it improves the composition or is supported by visible context.

Preferred:
- 0–4 short phrases
- 1–4 words per phrase
- hand-written or marker-like lettering
- used as texture, not as the main subject

For simple fashion portraits, text may be omitted entirely.

For context portraits, acceptable examples are generic observational phrases such as:
- COFFEE BREAK
- SLOW DAY
- CITY PAUSE
- JUST HERE
- GOOD DAYS

Avoid invented personal biography, job titles, names, dates, achievements, personality claims, or brand narratives.

---

## Step 7 — Prompt construction

Build the final image-generation prompt in this order:

### 1. Preservation block

"Strictly preserve the uploaded person's identity, recognizable facial features, hairstyle, age impression, skin tone, body proportions, pose, hand placement, gaze direction, and clothing silhouette. Keep the face primarily photographic and realistic."

### 2. Clothing-lock block

"Strictly preserve the person's original clothing as the same outfit. Keep garment category, collar shape, sleeves, cuffs, pockets, seams, hem shape, trousers silhouette, footwear type, and visible pattern logic such as stripes, checks, panel divisions, and major color relationships clearly recognizable. Any artistic treatment on clothing must behave like a surface overlay only and must not redesign the outfit."

### 3. Scene simplification block

"Greatly simplify the background only as much as needed. Preserve the environmental details that materially support the image story. Remove unnecessary visual clutter and convert much of the background into clean warm off-white, light gray, muted cream, or softly textured neutral negative space."

### 4. Selected style block

Insert the treatment for Fashion Paint, Identity Doodle, Graphic Pop, or Travel Doodle.

### 5. Color block

"Extract 2–3 dominant colors from the source photograph and add at most one complementary accent color by default. Limit the main palette to approximately 4–5 colors unless a brighter editorial mood is explicitly requested."

### 6. Material block

"Use expressive wax crayon, oil pastel, marker, dry-brush, chalk, and rough pencil textures with visible grain, uneven pressure, imperfect edges, and handmade irregularity."

### 7. Composition block

"Keep the person as the dominant visual anchor. Place added graphics mainly in negative space and around the body silhouette. Maintain a clear visual hierarchy and generous breathing room."

### 8. Negative constraints

"Do not cartoonize the face, do not change identity, do not add extra people, do not invent professions or hobbies, do not overfill the background, do not use polished vector graphics, do not create glossy 3D rendering, do not turn the entire image into an illustration, do not redesign the person's clothing, do not replace real stripes or garment construction with unrelated decorative patterns, and do not overpaint the outfit until it becomes unrecognizable."

---

## Clothing-lock prompt add-on

Use this add-on whenever outfit preservation is important:

> Preserve the person's original clothing exactly as the same outfit. Keep the shirt, trousers, shoes, and all garment construction details recognizable. Preserve collar shape, sleeve length, cuffs, pocket placement, seam structure, and pattern logic such as stripes or checks. Any doodle, paint, or crayon treatment applied to the clothing must behave like a transparent or semi-opaque surface overlay, not like a redesign. The outfit should still be immediately readable as the original real clothing.

---

## Default master prompt

Use this when the user asks to automatically choose the style:

> Analyze the uploaded portrait before stylizing it. Identify the person's pose, expression, clothing silhouette, garment structure, visible pattern logic, scene type, meaningful visible objects, dominant colors, and overall information density. Based only on visible evidence, choose the strongest primary direction from Fashion Paint, Identity Doodle, Graphic Pop, or Travel Doodle. A subtle secondary influence may be blended in only when it improves the image.
>
> Strictly preserve the uploaded person's identity, recognizable facial features, hairstyle, age impression, skin tone, body proportions, original pose, hand placement, gaze direction, and clothing silhouette. Keep the face primarily photographic and realistic.
>
> Strictly preserve the original outfit as the same outfit. Keep garment category, collar shape, sleeves, cuffs, pockets, hems, trousers shape, footwear type, and visible pattern logic such as stripes, checks, seam lines, panel divisions, and major color relationships clearly recognizable. Any artistic enhancement on clothing must remain a surface treatment only and must not redesign the outfit.
>
> Greatly simplify the background only as much as needed. Preserve only the environmental details that materially support the image story. Remove unnecessary clutter and convert much of the background into clean warm off-white, light gray, muted cream, or softly textured neutral negative space unless the source image clearly benefits from retaining more of the original scene.
>
> If the outfit is the strongest feature, use Fashion Paint: preserve the original clothing structure and pattern logic, then apply expressive wax-crayon and oil-pastel overlays as a surface treatment only. Use rough hand-drawn contour lines, selective color accents, partial textured fills, and a few oversized abstract gestures around the body. The clothing must still read clearly as the same original garment.
>
> If the photo clearly shows a meaningful activity, object, or context, use Identity Doodle: convert visible clues into a small number of simple hand-drawn symbols and, when useful, 0–4 short contextual phrases. Do not invent identity information that is not visible.
>
> If the source lacks narrative clues, use Graphic Pop: abstract curves, loops, stars, waves, geometric marks, irregular stripes, and bold hand-drawn color blocks with an editorial feel, but do not let these replace the real garment design.
>
> If the image clearly contains a recognizable travel setting, use Travel Doodle: retain only the key place cue and transform its real visual information into simplified hand-drawn motifs around the portrait.
>
> Extract 2–3 dominant colors from the source photograph and add at most one complementary accent color unless a brighter editorial mood is clearly appropriate. Limit the main palette to approximately 4–5 colors.
>
> Use expressive wax crayon, oil pastel, marker, dry brush, chalk, and rough pencil textures with visible grain, uneven pressure, broken edges, partial fills, overlapping strokes, and slight handmade misregistration.
>
> Keep the person as the dominant visual anchor. Place most added artwork in the negative space and around the body silhouette. Maintain strong visual hierarchy, clear breathing room, and a polished contemporary editorial composition.
>
> The result should feel custom-designed for this exact photograph rather than like a fixed doodle template.
>
> authentic portrait photography × expressive hand drawing × contemporary editorial design.
>
> Do not cartoonize the face. Do not alter identity. Do not add extra people. Do not invent biography, profession, hobby, or location. Do not redesign the person's clothing into a different outfit. Do not replace real stripes, checks, seams, or garment construction with unrelated decorative patterns. Do not overpaint the clothing so heavily that the original outfit becomes unrecognizable.

---

## Adaptive examples

### Example: café portrait

Visible clues:
- person holding coffee
- café seating
- casual neutral clothing
- subdued urban palette

Recommended:
- primary: Identity Doodle
- secondary: Graphic Pop or Fashion Paint only when useful
- simplify café background moderately
- retain cup + one table or architectural cue
- use coffee cup sketch / steam / small handwritten phrase
- do not fill the page with café furniture
- preserve the original outfit exactly as the same outfit

### Example: plain fashion portrait

Visible clues:
- visually strong outfit
- clean pose
- minimal background

Recommended:
- Fashion Paint
- no need for text
- let the clothing carry most of the artwork
- use Level 2 garment enhancement by default
- preserve garment construction and pattern logic

### Example: travel portrait with landmark

Recommended:
- Travel Doodle
- keep person + landmark
- remove most secondary tourists / shops / clutter
- derive line motifs from landmark geometry
- preserve the original outfit

### Example: striped café portrait

Visible clues:
- seated person
- coffee cup
- casual café or outdoor seating
- striped shirt
- loose dark trousers
- neutral subdued palette

Recommended:
- primary: Identity Doodle or Fashion Paint depending on user preference
- preserve the striped shirt exactly as a striped shirt
- do not replace the stripes with unrelated multicolor abstract fashion graphics
- simplify the background moderately
- retain one or two café anchors such as the cup and table
- allow hand-drawn coffee icons, arrows, short phrases, and contour accents
- if using Fashion Paint, apply it mainly as contour enhancement and partial overlay, not as clothing redesign

---

## Output goal

The final image should feel:
- personal to the source photo
- editorial rather than cartoonish
- expressive but controlled
- hand-made rather than vector-perfect
- visually simplified
- recognizably photographic at the face
- faithful to the original outfit
- unique to the subject and scene

The most important final rules:

**Preserve the real person. Preserve the real outfit. Simplify the world. Add only art that belongs to the photograph.**
