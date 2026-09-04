---
name: negative-space-collage-poster
description: Transform uploaded real-person photos into dreamy vertical negative-space handmade collage posters while preserving identity and original scene relationships.
metadata:
  short-description: Dreamy negative-space photo collage posters
---

# Negative Space Collage Poster

Use this skill when the user wants to turn an uploaded real-person, documentary, street, travel, portrait, or candid photo into a dreamy, melancholic handmade collage poster with a negative-space cutout. The expected output is a vertical 3:4 image.

This skill is for image editing from a supplied real photo. If no usable source photo is available, ask the user to upload one before generating the poster.

## Core Transformation

Create a vertical 3:4 handmade collage art poster with an upper/lower split composition:

- The upper half keeps the original real scene from the uploaded photo. Preserve the original background, buildings, street, railings, sky, natural environment, spatial perspective, lighting relationships, and the person's original placement context. Apply only a low-saturation blue-gray or cyan-green grade, mist, slight defocus, old-photo grain, paper fiber, dust scratches, and faded film texture. Do not replace the upper half with a new landscape.
- At the person's original position in the upper half, remove the person and leave a clean white torn-paper negative-space hole. The hole must match the original person's actual silhouette, placement, scale, and pose, including hair, head, body, arms, clothing outline, and carried objects.
- The lower half becomes rough handmade paper in pale gray-white, light cyan-white, or very subtle mint. Add paper fibers, grain, aged-paper noise, and faint water stains.
- Paste the person cut from the original photo into the lower half, preferably slightly right or lower in the frame. The lower figure should feel like a soft translucent paper cutout, while preserving facial likeness, hairstyle, expression, clothing colors, pose, body proportions, and carried objects.
- Give the lower figure warm off-white torn-paper edges, a subtle cast shadow, and enough tonal separation from the paper background. Avoid hard outlines, cartoon rendering, or repainting the person into a different identity.

## Signature Motifs

Add a thin red hand-drawn thread or yarn line that begins near the lower figure's hand, wrist, bag strap, or body, travels upward through the center, and connects to the white negative-space hole in the upper half.

The red line should curve naturally, include a few irregular circular loops, and look like red pencil, embroidery thread, or hand stitching with uneven thickness and real handmade imperfections. The top may resolve into a tiny feather, plant twig, or stitched knot.

Add a few handmade paper stars and blue water drops near the red line and on the lower paper area. Keep them sparse. Stars need readable paper-cut or sparkle shapes. Water drops should use rain blue or blue-cyan that is more saturated than the background, with a light dark edge or soft paper shadow so they remain visible in thumbnails.

Decoration must not cover the person's face, eyes, hands, key clothing details, or carried objects.

## Prompting Guidance

When invoking an image editing model, include these priorities explicitly:

1. Preserve the source person's identity and scene relationship.
2. Keep the upper scene from the original photo; only grade and texture it.
3. Replace the upper person with an accurately aligned white torn-paper silhouette.
4. Reuse the same person as a lower-half paper cutout.
5. Add the red thread connection, sparse paper stars, and blue drops without blocking important body or face details.

Use "negative space", "torn paper cutout", "handmade paper collage", "melancholic dreamy film texture", and "vertical 3:4 poster" as stable style anchors. Avoid instructions that introduce a new location, new outfit, fantasy character, cartoon style, heavy painting, hard vector edges, or dense decoration.

## Reusable Edit Prompt

Use or adapt this prompt when the user asks directly for the transformation:

```text
Transform the uploaded real-person photo into a dreamy, melancholic handmade negative-space collage art poster, vertical 3:4.

Preserve the person's main identity, facial likeness, hairstyle, pose, clothing silhouette, carried objects, and original scene relationship. Use a split composition. In the upper half, keep the original real scene from the photo, including the original background, buildings, street, railings, sky, natural environment, perspective, and lighting. Apply only a low-saturation blue-gray/cyan-green color grade, mist, slight defocus, old-photo grain, paper fibers, dust scratches, and faded film texture. Do not replace the upper half with a new landscape.

At the person's original position in the upper half, remove the person and leave a clean white torn-paper negative-space hole. The hole must strictly match the original person's real cutout position, scale, and pose, including hair, head, body, arms, clothing, and carried-object contours.

Make the lower half a pale gray-white, light cyan-white, or subtle mint rough handmade paper background with fibers, grain, aged-paper noise, and faint water stains. Paste the person cut from the original photo into the lower half, slightly right or slightly lower in the frame, as a soft translucent paper cutout. Preserve the same face, hairstyle, expression, clothing colors, pose, proportions, and carried objects. Add warm off-white torn-paper edges, a subtle shadow, and clear separation from the paper background. Do not use hard outlines, cartoon style, or a different identity.

Add one thin red hand-drawn thread or yarn line from the lower figure's hand, wrist, bag strap, or body, extending upward through the center to connect to the white negative-space hole in the upper half. The line should curve naturally, include a few irregular circular loops, and look like red pencil, embroidery thread, or handmade stitching with uneven thickness and real imperfections. The top can become a tiny feather, plant twig, or stitched knot.

Add a small number of handmade paper stars and blue water drops near the red line and on the lower paper area. Stars should have clear paper-cut or sparkle shapes. Water drops should be rain blue or blue-cyan, more saturated than the background, with a light dark edge or soft paper shadow so they are visible in thumbnails. Do not cover the person's face, eyes, hands, important clothing details, or carried objects.
```
