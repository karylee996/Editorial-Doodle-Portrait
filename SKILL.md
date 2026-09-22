# Editorial-Doodle-Portrait

## Purpose

Create a custom mixed-media editorial portrait from a single uploaded person photo.

The core principle is:

**Keep the real person recognizable, then redesign the visual world around them.**

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
- number of people

Do not:
- redesign the face
- turn the face into a cartoon
- change age or gender presentation
- add extra people
- alter the original pose without a clear user request
- invent a profession, hobby, location, personality trait, or life story that is not visible in the photo

The face should remain primarily photographic. Artistic treatment should focus on clothing, silhouette edges, negative space, surrounding graphic elements, and selected environmental clues.

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
   - dominant colors
   - texture or pattern
   - whether the outfit itself is visually distinctive

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
   - add at most 1 complementary accent color
   - keep the main palette to roughly 4–5 colors maximum

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
- repaint clothing surfaces with expressive crayon, wax pastel, marker, or oil pastel overlays
- add rough color blocks and imperfect contour lines
- use large abstract gestures around the body
- avoid dense text
- preserve garment construction and shape

Visual keywords:
- fashion editorial
- wax pastel
- oil crayon
- expressive hand coloring
- oversized naïve strokes
- loose floral scribbles
- handmade imperfection

---

### B. Identity Doodle

Use when:
- the photo clearly shows an activity, profession, hobby, or representative object
- there is enough visible evidence to derive a theme from the image

Treatment:
- translate visible objects or activities into simple hand-drawn symbols
- add a small number of context-relevant words only when justified
- keep icons around the head, shoulders, and negative space
- do not cover eyes, nose, or mouth
- maintain strong hierarchy and breathing room

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

Do not overwhelm the portrait with scenery.

---

## Step 3 — Background simplification

This is a critical rule.

**Default to a simplified background.**

Do not preserve the entire original environment unless it is essential to the story.

Use this hierarchy:

1. Keep the person intact.
2. Keep 0–2 meaningful environmental anchors.
3. Remove or fade secondary furniture, architecture, clutter, signage, tables, wall details, or random objects.
4. Replace discarded background areas with:
   - warm off-white
   - light gray
   - muted cream
   - pale paper texture
   - very soft neutral photographic tone
5. Use hand-drawn graphics to reconnect the simplified space.

For visually busy photos, the final background should usually feel at least **50–70% simpler** than the source.

Avoid collage overload.

---

## Step 4 — Doodle material language

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

---

## Step 5 — Text policy

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

Avoid invented personal biography, job titles, names, dates, achievements, or personality claims.

---

## Step 6 — Prompt construction

Build the final image-generation prompt in this order:

### 1. Preservation block

"Strictly preserve the uploaded person's identity, recognizable facial features, hairstyle, age impression, skin tone, body proportions, pose, hand placement, gaze direction, and clothing silhouette. Keep the face primarily photographic and realistic."

### 2. Scene simplification block

"Greatly simplify the background. Preserve only the environmental details that materially support the image story. Remove visual clutter and convert most of the background into clean warm off-white / neutral paper-like negative space."

### 3. Selected style block

Insert the treatment for Fashion Paint, Identity Doodle, Graphic Pop, or Travel Doodle.

### 4. Color block

"Extract 2–3 dominant colors from the source photograph and add at most one complementary accent color. Limit the main palette to approximately 4–5 colors."

### 5. Material block

"Use expressive wax crayon, oil pastel, marker, dry-brush and rough pencil textures with visible grain, uneven pressure, imperfect edges, and handmade irregularity."

### 6. Composition block

"Keep the person as the dominant visual anchor. Place added graphics mainly in negative space and around the body silhouette. Maintain a clear visual hierarchy and generous breathing room."

### 7. Negative constraints

"Do not cartoonize the face, do not change identity, do not add extra people, do not invent professions or hobbies, do not overfill the background, do not use polished vector graphics, do not create glossy 3D rendering, and do not turn the entire image into an illustration."

---

## Default master prompt

Use this when the user asks to automatically choose the style:

> Analyze the uploaded portrait before stylizing it. Identify the person's pose, expression, clothing silhouette, scene type, meaningful visible objects, dominant colors, and the overall information density. Based only on visible evidence, choose the strongest primary direction from Fashion Paint, Identity Doodle, Graphic Pop, or Travel Doodle. A subtle secondary influence may be blended in only when it improves the image.
>
> Strictly preserve the uploaded person's identity, recognizable facial features, hairstyle, age impression, skin tone, body proportions, original pose, hand placement, gaze direction, and clothing silhouette. Keep the face primarily photographic and realistic.
>
> Greatly simplify the background. Preserve only 0–2 meaningful environmental anchors that support the image story. Remove secondary furniture, architectural clutter, signage, wall details, and random objects. Convert the remaining space into warm off-white, light gray, muted cream, or softly textured neutral negative space. The final background should feel significantly cleaner than the original.
>
> If the outfit is the strongest feature, use Fashion Paint: expressive wax-crayon and oil-pastel overlays on the clothing, rough hand-drawn contour lines, partial color fills, and a few oversized abstract gestures around the body.
>
> If the photo clearly shows a meaningful activity, object, or context, use Identity Doodle: convert those visible clues into a small number of simple hand-drawn symbols and, when useful, 0–4 short contextual phrases. Do not invent identity information that is not visible.
>
> If the source lacks narrative clues, use Graphic Pop: abstract curves, loops, stars, waves, geometric marks, irregular stripes, and bold hand-drawn color blocks with an editorial, contemporary graphic feel.
>
> If the image clearly contains a recognizable travel setting, use Travel Doodle: retain only the key place cue and transform its real visual information into simplified hand-drawn motifs around the portrait.
>
> Extract 2–3 dominant colors from the source photograph and add at most one complementary accent color. Limit the main palette to approximately 4–5 colors.
>
> Use expressive wax crayon, oil pastel, marker, dry brush, chalk, and rough pencil textures with visible grain, uneven pressure, broken edges, partial fills, overlapping strokes, and slight handmade misregistration.
>
> Keep the person as the dominant visual anchor. Place most added artwork in the negative space and around the body silhouette. Maintain strong visual hierarchy, clear breathing room, and a polished contemporary editorial composition.
>
> The result should feel custom-designed for this exact photograph rather than like a fixed doodle template.
>
> authentic portrait photography × expressive hand drawing × contemporary editorial design.
>
> Do not cartoonize the face. Do not alter identity. Do not add extra people. Do not invent biography, profession, hobby, or location. Do not preserve excessive background clutter. Do not use overly smooth vector graphics. Do not make the entire image look like an illustration.

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
- secondary: Graphic Pop
- simplify café background heavily
- retain cup + one table or architectural cue
- use coffee cup sketch / steam / small handwritten phrase
- do not fill the page with café furniture

### Example: plain fashion portrait

Visible clues:
- visually strong outfit
- clean pose
- minimal background

Recommended:
- Fashion Paint
- no need for text
- let the clothing carry most of the artwork

### Example: travel portrait with landmark

Recommended:
- Travel Doodle
- keep person + landmark
- remove most secondary tourists / shops / clutter
- derive line motifs from landmark geometry

---

## Output goal

The final image should feel:
- personal to the source photo
- editorial rather than cartoonish
- expressive but controlled
- hand-made rather than vector-perfect
- visually simplified
- recognizably photographic at the face
- unique to the subject and scene

The most important final rule:

**Preserve the real person. Simplify the world. Add only art that belongs to the photograph.**
