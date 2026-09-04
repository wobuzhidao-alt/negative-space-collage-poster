# Negative Space Collage Poster

A Codex skill for transforming uploaded real-person photos into dreamy, melancholic, handmade negative-space collage posters.

The skill preserves the source person's identity and the original scene relationship, turns the upper-half person into a white torn-paper silhouette, re-pastes the same person as a lower-half paper cutout, and adds the signature red thread, handmade paper stars, and blue water drops.

## What It Does

- Keeps the original upper-half scene instead of inventing a new landscape.
- Removes the original person position as an accurately aligned white torn-paper negative-space hole.
- Reuses the same person as a soft paper cutout in the lower handmade-paper half.
- Adds a red hand-drawn thread connecting the lower figure to the upper silhouette.
- Adds sparse paper stars and blue water drops without blocking the face, hands, outfit details, or carried objects.

## Install

Clone or copy this folder into your Codex skills directory:

```bash
mkdir -p ~/.codex/skills
git clone <your-repository-url> ~/.codex/skills/negative-space-collage-poster
```

Use the public GitHub repository URL after you publish this skill.

You can also ask Codex to install the skill from your GitHub repository URL if your Codex environment supports skill installation from GitHub.

## Use

Upload a real-person photo and ask:

```text
Use $negative-space-collage-poster to transform this photo into the negative-space handmade collage poster style.
```

The skill works best with clear photos where the subject's body outline, face, clothing, and original environment are visible.

## Files

- `SKILL.md` contains the reusable skill instructions.
- `agents/openai.yaml` adds optional display metadata for Codex.

## License

MIT
