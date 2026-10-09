---
name: photo-sketch-story
description: Create one refined image in which a real uploaded photograph naturally opens into a sparse illustrated micro-story.
---

Photo Sketch Story
Create one refined image in which a real uploaded photograph naturally opens into a sparse illustrated micro-story. Do not use a fixed top/bottom template.
Inputs
Require one uploaded photograph. Accept these optional choices:
- Atmosphere: automatic (default), healing, funny, travel, holiday, playful.
- Aspect ratio: automatic (default), 9:16, 1:1, or 16:9.
- Caption mode: none (default), external caption ideas, or print in image.
- Extra intent: a short preference such as “quiet,” “more childlike,” or “make the dog the hero.”
When the user gives only a photograph, proceed with automatic choices. Do not ask follow-up questions unless no photo is available or the user requests a result that conflicts with the photo.
Workflow
1. Inspect and decide before generating
Read the uploaded photograph and make these decisions silently:
1. Identify the main subject(s), essential geometry, lighting, and photographic details that must remain recognizable.
2. Identify natural negative space, strongest leading lines, and a potential paper-expansion direction: up, down, left, right, diagonal, or from a local material edge.
3. Select a narrative anchor, in this order: portable object (flower, fruit, ball, umbrella, toy) → structure (door, window, path, bridge, fence, vehicle) → natural motion (wind, rain, cloud, water, leaves, shadow) → subject outline, footprint, sightline, or gesture.
4. Choose the image ratio that protects the subject and creates the cleanest story space. Never crop the main subject merely to fit a preferred ratio.
5. Choose one instantly readable action for the illustration: carry, catch, climb, release, shelter from rain, chase, gather, celebrate, build, float, or share.
Before generating, briefly tell the user the decision in one or two Chinese sentences: photo placement/extension direction, anchor, and story action. Do not ask for confirmation unless requested.
2. Compose the photo and sketch world
- Preserve the photo's main subject, meaningful object identity, clothing or fur when relevant, major architecture, perspective, and lighting logic.
- Let the photo occupy roughly 40%–70% of the final image. Keep more when the original composition is strong.
- Use a natural transition rather than a rigid straight split: ground, wall edge, rooftop, branch, waterline, road, cloud, shadow, flower stem, door, window, or material texture.
- Use a light warm ivory handmade-paper area for the illustrated world. The paper can expand in any direction selected from the photo.
- Make the anchor visibly cross between the real and illustrated zones. If no physical anchor exists, bridge them with the outline, shadow, footprints, falling leaves, rain, wind, or the subject’s gaze.
- Draw only small generic picture-book figures or animals. Based on the photo's scene extension, narrative needs, and overall visual beauty, independently decide the number, placement, and each character's or animal's clear action. Do not add decorative crowds without narrative purpose.
3. Visual language
- Keep the photograph genuinely photographic; do not redraw the whole image.
- Use delicate, sparse black pencil/ink linework with a little natural irregularity. Avoid anime, thick comic outlines, polished commercial cartoon style, or imitation of named artists and characters.
- Retain the photo’s anchor color in a few illustration elements. Keep everything else mostly black, white, soft gray, and restrained pale color.
- Keep a calm, warm, observant visual balance. “Funny” may be playful but not slapstick or crowded.
- Never add watermarks, borders, QR codes, interface elements, logos, or default text.
4. Generate and check
Use the built-in image-generation tool in edit mode, treating the uploaded photo as the edit target. Write a production prompt that explicitly includes:
- preservation invariants from the original photo;
- selected composition and aspect ratio;
- natural transition direction and paper texture;
- narrative anchor and one-action story;
- sparse pencil/ink visual language and color restraint;
- no-text and no-watermark constraints.
After generating, inspect the result. Regenerate once with a targeted correction if any of these fail:
- The photographic subject or place is no longer recognizable.
- The story has no clear action or connection to the photo.
- The photo/sketch boundary is a hard, arbitrary pasted split.
- The illustration overwhelms the original photo.
- Architecture, perspective, face, pet features, or object identity drift materially.
- Unrequested text, watermark, or busy extra characters appear.
For dense photos with little empty space, favor a side, edge, or material-driven expansion. For water, roads, paths, stairs, branches, or roofs, follow their leading line into the sketch. For photos without an obvious object, use motion or silhouette as the transition.
Captions
- None: generate no text in the image and do not add suggestions.
- External caption ideas: keep the image text-free and give three short Chinese titles/captions after the result.
- Print in image: use only 2–8 Chinese characters or a very short English handwritten phrase on an uncluttered paper area. If legibility is not reliable, keep the image text-free and provide external caption ideas instead.
Example requests
- “用 $photo-sketch-story 做这张狗狗照片，搞笑一点，自动构图。”
- “把这张旅行照做成温暖小故事，横版，不要文字。”
- “给这张孩子照片加手绘延展，童趣，给我三个图外标题。”





编辑在聊天中试用
