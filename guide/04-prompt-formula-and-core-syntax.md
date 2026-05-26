## Prompt formula & core syntax

### The “works-in-most-cases” prompt formula

```Plain Text
[Subject] + [Action] + [Setting] + [Lighting] + [Camera] + [Style] + [Quality] + [Constraints]
```

### Breaking it down

| Part | Description | Example |
| --- | --- | --- |
| Subject | Who or what | A young woman, an orange tabby cat, a red sports car |
| Action | What is happening | Walking slowly on the beach, sipping coffee, running fast |
| Setting | Where it happens | Under cherry blossoms, a cyberpunk city, a traditional courtyard |
| Lighting | Light and mood | Warm dusk light, backlit silhouette, neon glow |
| Camera | How it’s shot | Slow push-in, orbit follow, top-down view |
| Style | Overall vibe | Cinematic, clean Japanese style, cyberpunk |
| Quality | Resolution / sharpness | 4K, cinema-grade |
| Constraints | What to avoid / enforce | Stable footage, clear faces without distortion |

### Full example

```Plain Text
An elegant man turns back on a rainy street after the rain. Neon lights reflect in puddles as he looks into the distance.
Deep night atmosphere. Close-up with rack focus. 8K ultra-clear, detailed skin texture.
Extremely smooth motion. Soft natural bokeh. Strong facial features with no flicker.
```

### @ syntax (how to reference inputs)

| `@audio1 as the background music` | Use this audio as the background music |
| --- | --- |
| `Reference transitions from @video1` | Copy the transition effects from the video |
| `Reference actions from @video1` | Copy the character’s actions from the video |
| `Reference camera movement from @video1` | Copy the camera movement from the video |
| `Use the person in @image1 as the main character` | Use the person in the image as the main character reference |
| `@image1 as the last frame` | Use this image as the last frame |
| `@image1 as the first frame` | Use this image as the first frame |
| Syntax | Meaning |
| `@image1 as the first frame` | Use this image as the first frame |
| `@image1 as the last frame` | Use this image as the last frame |
| `use the person in @image1 as the main character` | Use the person in the image as the main character reference |
| `reference camera moves from @video1` | Copy the camera movement from the video |
| `reference actions from @video1` | Copy the character’s actions from the video |
| `reference transitions from @video1` | Copy the transition effects from the video |
| `use @audio1 as background music` | Use this audio as the background music |
| `sync to the rhythm of @audio1` | Sync the visuals to the audio rhythm |
| `Reference rhythm from @audio1` | Sync the visuals to the audio rhythm |

### Timecoded prompts (advanced)

Describe the video in time segments so the model follows you more closely:

```Plain Text
0–3s: The male lead raises a basketball and says, “I just wanted a drink… am I about to time travel or what?”
4–8s: The scene cuts to a rainy night in an old mansion. The female lead looks at the camera with an icy stare.
9–13s: An official yells angrily, “Guards! Take this monster down, now!”
14–15s: Cut to black. Title card: “Drunken Dream, Sudden Glory”.
```

### Emotional arc prompts (advanced)

```Plain Text
0–2s: Soft and gentle, character smiles.
2–5s: Emotions build, tension and anticipation rise.
5–10s: Peak moment, intense and impactful.
10–15s: Calm down, a relieved and satisfied expression.
```

---

[Previous](./03-quick-start-guide.md)  
[Index](./README.md)  
[Next](./05-8-core-use-cases.md)
