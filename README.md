# Seedance 2.0 Ultimate Guide + Selected Tips

---

## Introduction

Still tearing your hair out over video creation? Want AI-generated videos to be more "obedient"?

**Seedance 2.0 is here!** This upgrade is nothing short of explosive—it supports a free combination of four input methods: images, videos, audio, and text. You can play with it however you want.

Simply put: **You imagine it, and it makes it happen.**

> "Seedance 2.0 is the world's strongest video model right now, bar none." —— @op7418

---

## Table of Contents

1. [Understanding Seedance 2.0 in One Minute](./guide/01-understanding-seedance-2-0-in-one-minute.md)
2. [Recommended Seedance 2.0 Pro Access Point](./guide/02-recommended-seedance-2-0-pro-access-point.md)
3. [Quick Start Guide](./guide/03-quick-start-guide.md)
4. [Prompt Formula and Core Syntax](./guide/04-prompt-formula-and-core-syntax.md)
5. [8 Core Use Cases](./guide/05-8-core-use-cases.md)
6. [Camera Language Cheat Sheet](./guide/06-camera-language-cheat-sheet.md)
7. [Practical Templates You Can Copy](./guide/07-practical-templates-you-can-copy.md)
8. [Advanced Tips and How to Save Credits](./guide/08-advanced-tips-and-how-to-save-credits.md)
9. [FAQ Plus Common Pitfalls](./guide/09-faq-plus-common-pitfalls.md)
10. [Advanced Prompt Guide for Power Users](./guide/10-advanced-prompt-guide-for-power-users.md)
11. [10 God-Tier Workflows With Real Examples](./guide/11-10-god-tier-workflows-with-real-examples.md)
12. [Final Notes](./guide/12-final-notes.md)
13. [References](./guide/13-references.md)
14. [Curated Prompt Library](./guide/14-curated-prompt-library.md)
15. [Prompt Sources](./guide/15-prompt-sources.md)

---

## Understanding Seedance 2.0 in One Minute

### What can it do?

| Capability | Description |
| --- | --- |
| 🖼️ Image reference | Use an image to lock in the visual style, character look, and scene mood. |
| 🎬 Video reference | Copy camera moves, actions, and transition effects. Want to “trace the homework”? No problem. |
| 🎵 Audio reference | Let the rhythm drive the edit. Music, SFX, and vocals can all be referenced. |
| ✍️ Text prompt | Tell it what you want in plain language. |
| 🔊 Built-in audio | The generated video can include sound effects and background music. |

### Basic parameters at a glance

| Item | Limit |
| --- | --- |
| Images | Up to 9 images(Currently, uploading real photos is restricted) |
| Videos | Up to 3 videos, total length ≤ 15 seconds |
| Audio | Up to 3 MP3s, total length ≤ 15 seconds |
| Generation length | Choose 4–15 seconds |
| Total files | Up to 12 files |
| Output quality | Native 1080p / 2K, cinema-level quality |

**Key point**: More materials are not always better. Upload the ones that most affect visuals and rhythm first.

---

## Recommended Seedance 2.0 Pro access point

**Link**: [https://kinovi.ai/](https://kinovi.ai/)

- The easiest way to try Seedance 2.0
- Supports both “All-in-one reference” and “First & last frame” modes
- No sign-up needed. Open it and start generating.
- Supports multimodal inputs: images, video, and audio
- Join the community: [https://discord.com/invite/rzTfv5KFrK](https://discord.com/invite/rzTfv5KFrK)

![image.png](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/55a707dd-d154-400d-8076-be1d159c4411/image.png?table=block&id=30bd38a8-50fc-81d2-becc-f51c17b74cc1&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=vVXcj_7zj_hxaXy0MMl7BSS5MuFYoHiNpKk_bgoHZsg)

---

## Quick Start Guide

### Step 1: Choose a mode

Seedance 2.0 has four modes:

- **Text-to-video**: Type your idea in natural language and turn words into a polished, cinematic video.
- **Image-to-video**: Use a first-frame image to lock the character and vibe, then use prompts to bring the still image to life(Currently, real facial images are not supported).
- **First & last frame**: Upload a start frame and an end frame plus a prompt. Your prompt should focus on **motion trends** (like spinning, dissolving, growing, or light flowing), not static details. The frames already lock the details.
- **All-in-one reference**: Combine video, audio, and image inputs for deep multimodal control and remixing.

> 💡 Want to do something fancy? Pick “All-in-one reference” and you’re good to go.

### Step 2: Upload materials

1. Click the upload button to add your files
1. Your materials will be added to the input box automatically
1. Hover to preview and make sure you picked the right files

### Step 3: Use @ to assign each material’s role (very important)

Choose the reference mode. This is the “secret sauce” of All-in-one reference in Seedance 2.0. Use `@` to tell the model exactly how to use each material:

```Plain Text
Use @image1 as the first frame.
Use the woman in @image2 as the main character.
Copy the camera moves and actions from @video1.
Use @audio1 as the background music.
```

**How to trigger @:** Type `@` in the input box and it will automatically show the material list.

⚠️ **Note**: Materials that are not explicitly labeled may be misused by the model. Always label them clearly.

### Step 4: Write the prompt and generate

Describe the video you want in natural language, hit Generate, and wait for the result.

---

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

## More

- More chapters continue in [guide/05-8-core-use-cases.md](./guide/05-8-core-use-cases.md)
- [Final Notes](./guide/12-final-notes.md)
- [References](./guide/13-references.md)
- [Curated Prompt Library](./guide/14-curated-prompt-library.md)
