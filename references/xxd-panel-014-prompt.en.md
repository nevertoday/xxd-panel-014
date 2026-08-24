# XXD Panel 014 | Contemporary Folded-Paper Sculpture Production Prompt

## Runtime complete-canvas contract — highest priority

- `TOP_BOTTOM` and `LEFT_RIGHT` default to one complete finished generation using the current source as a high-fidelity edit/reference input. Do not pre-split the job into photographic and design halves.
- Top-bottom keeps the faithful source in approximately the upper 50% and performs this style transformation below; left-right uses the faithful source in approximately the left 50% and the transformation on the right. Unify both regions through colour, light, rhythm, typography, and meaning.
- `DESIGN_ONLY` and `WALLPAPER_PACK` use the complete canvas while the source remains an invisible identity/content reference. Recompose every wallpaper separately for its device.
- `FINAL CANVAS` means the ratio/pixels of the whole finished artwork and must be explicitly resolved before generation; never apply source dimensions silently. `DESIGN FRAME` is used only if a failed complete-canvas retry triggers deterministic composition fallback.
- Retry a failed complete canvas once against the failed constraint only. Scripted composition is allowed only after that retry still fails, when pixel-identical source preservation is explicitly required, when the active route cannot realise the canvas, or for lossless pixel calibration.

### Model priority and credentials

- **Prefer GPT Image 2.** When GPT Image 2 is available through the current built-in image tool or a configured compatible route, use it first for the high-fidelity reference/edit and complete-canvas generation required by this prompt.
- Also support Seedance 5.0 Pro, Nano Banana Pro (Gemini Image Pro), Nano Banana 2 (Gemini Image Flash), or another compatible bitmap model only when the actual route can preserve the source, realise the whole finished canvas, render the target-language text, and accept the multiple references needed by a linked wallpaper pack.
- An alternative model changes only the generation route. It must not change this prompt's modes, canvas, source visibility, copy, locale, wallpaper relationship, or complete-canvas-first / composition-fallback-only logic. Do not silently downgrade a hard requirement.
- If no suitable route is available, ask the user to enable an image-generation tool or provide an API key. User-provided credentials may be used for the current task, but never echo, display, log, or expose their value in chat, prompts, or diagnostics. Do not persist them or modify global route configuration unless explicitly requested.
- Judge availability by actual image capability, not by a provider name or one missing environment variable.

Process only the one source photograph explicitly supplied for this current task. Lock the principal subject or inseparable relation, silhouette, pose, action, structure, scale, negative shape, direction, and distance. Preserve at least three source-specific recognition cues. Never borrow a subject, paper construction, palette, copy, or composition from old outputs, samples, or another input.

## Fold, cut, layer, and nest

Rebuild the subject as tactile folded-paper sculpture and paper-cut collage instead of mechanically reproducing photographic detail. Establish a fold map: which contour becomes a cut edge, which mass becomes a folded plane, which occlusion becomes layered paper, which opening becomes negative space, and which relation becomes nesting, interweaving, or foreground/background overlap.

People retain pose, orientation, clothing mass, and relational distance; animals retain body rhythm and head direction; plants retain growth gesture; architecture retains skyline and defining openings; objects and vehicles retain functional silhouette and negative shape; landscapes retain a source-specific horizon, terrain, or spatial relation.

Build volume with a limited number of large structural planes, then add only the small paper pieces required for recognition and depth. Creases change direction at plausible joints; cut edges reveal paper thickness; joins and nests feel physically credible; layers cast soft natural contact shadows. Reject airborne confetti, excessive accordion folds, unsupported floating pieces, and complex piling that erases the silhouette.

## Source-led composition

Read the source's centre of gravity, contour trajectory, mass ratio, and action direction before placing the sculpture. Do not default to centring. The form may be offset, locally cropped, extended toward one edge, or suspended, but must retain at least three identity cues and the principal action or relation.

Use primary/secondary hierarchy, scale contrast, axis relationships, triangular stability, diagonal tension, foreground/background overlap, and positive/negative space to organise one focal sculpture. Auxiliary paper shards, strips, arcs, or planes support weight, direction, depth, or scale and never form a second subject.

Use ivory, light grey, soft pastel, or a source-compatible pale ground with generous breathing space. Recompose sculpture scale, weight, extension direction, and safe regions for every device and aspect ratio; never mechanically centre or crop another result.

## Source-derived paper palette and real material

Extract the source's most recognisable and vital colours, translating them into a coordinated, vivid paper group. Use same-hue value steps, neighbouring hues, and only a small source-supported contrast to distinguish facets, layers, and spatial relation. Never impose a fixed palette or uncontrolled rainbow.

Use soft diffuse light to reveal paper fibre, crease, score, cut edge, thickness, layer separation, and natural shadow. Material reads as clean, matte, refined paper rather than plastic, metal, clay, foam board, smooth CG, or cheap card.

Reject muddy ageing, flat single-value facets, glossy laminate highlights, fake bevels, hard product lighting, low-poly rendering, cinematic volumetric glow, and default 3D materials.

## Folded-paper typography

Obey the resolved automatic, exact-user, or text-free copy mode and target language or locale. Preserve exact user wording verbatim. In text-free mode render no letter, character, number, folded-paper word, text, or pseudo-text.

Automatic copy distils one short source-specific word or title from identity, theme, action, emotion, relation, or supported symbolism. Add only a very small number of indexes, places, state words, or micro-notes when useful. Places, dates, provenance, and factual numbers must be user-supplied or reliably established and are never fabricated.

The main title becomes readable paper structure: arch around the form, extend along an axis, hug a contour, support above or below, interweave through layers, overlap in depth, or suspend in negative space according to the subject. Build it from folded, cut, layered, or lightly printed matte paper with real crease, edge, thickness, and soft shadow. Never use a pasted digital headline, extruded plastic word, or foam-board lettering.

Use a native paper-construction logic for the target script. Preserve natural Chinese, Japanese, Korean, Arabic, and Latin proportions, joining, direction, and legibility rather than forcing Latin folded block letters onto every writing system. Keep supporting type minimal and editorially restrained.

## Mode and acceptance


Hard gate: at least three source cues and the principal action or relation; one dominant paper sculpture with no competing auxiliary subject; physically credible folds, cut facets, layers, nesting, interweaving, occlusion, and negative space; composition follows weight, contour, mass, and direction rather than fixed centring; source-derived paper palette, pale ground, and generous whitespace; soft diffuse light clearly reveals fibre, crease, cut edge, thickness, and natural shadow; the main title is readable folded-paper spatial structure; no cartoon origami, children's craft, average symmetry, fragment pile, plastic 3D, smooth CG, low-poly render, ecommerce display, cheap card, photo fragment, or pseudo-text.

If any hard condition fails, correct the generated asset. Never fake the artwork with programmatic drawing, SVG, HTML, Canvas, or a post-composited type overlay.
