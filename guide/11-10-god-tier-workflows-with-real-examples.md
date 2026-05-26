## 10 god-tier workflows (with real examples)

> Sources: hands-on breakdowns from - [@aiwarts - 10 “god-tier” workflows](https://x.com/aiwarts/status/2022342787681939750) and [@realnyarime](https://x.com/realnyarime)

These are higher-level moves that the community has tested in real projects. You can copy them as-is.

### Quick overview

| # | Workflow | Difficulty | What it does |
| --- | --- | --- | --- |
| 1 | 3×3 storyboard → video | Medium | Director-style storyboard control |
| 2 | Action video reference remake | Easy | Reproduce actions precisely |
| 3 | Wuxia film style | Medium | Classic Shaw Brothers vibe |
| 4 | Camera-move remake | Medium | Often 70–80% similar |
| 5 | 4-panel comic → animation | Medium | A cheat code for short comics |
| 6 | VFX / transition remake | Hard | TikTok effect “replacement” |
| 7 | Logo / text animation | Easy | After-Effects-level vibes |
| 8 | Text screenshot → video | Easy | Visualize stories fast |
| 9 | Script table → video | Medium | A killer for ad pitches |
| 10 | Travel photos → vlog | Easy | One sentence to a finished clip |

---

### Workflow 1: 3×3 storyboard → a coherent video

**Why it works:** Generate a 3×3 storyboard image with Seedream 5.0, then turn it into a coherent clip with Seedance 2.0. The motion and camera transitions usually come out surprisingly smooth.

**Steps:**

1. **Generate a character + scene image** (Seedream 5.0 Lite)

1. **Generate the 3×3 storyboard grid:**

```Plain Text
Use this image as the first panel. Generate a single 3×3 storyboard grid showing a big-action fight between two characters.
Each panel should use a different shot size.
Design it like a film storyboard.
Put all nine panels into one image.
Make sure there are no physics errors in any panel.
```

1. **Storyboard → video prompt:**

```Plain Text
Based on this 3×3 storyboard grid, generate a very coherent, smooth video clip of an anthropomorphic giant cat fighting a red giant.
Make the action continuous and showcase a cool fight sequence.
```

---

### Workflow 2: Action video reference remake

**Why it works:** Give it an action clip + a character reference image + a background/scene image. The character will “perform” the same action in your target scene.

**Key points:**

- Your uploaded video must be **15 seconds or shorter**

- 720p-ish sources often work best

- Image-only reference usually costs **about half** compared to image + video

**Prompt structure:**

```Plain Text
Use the character in @image1 as the main character.
Use @image2 as the scene/background.
Copy the action and camera movement from @video1.
Have the main character perform the same actions as in @video1.
```

> Even if the original clip is just a 3D blocking/previz, you can still “re-skin” it into your own style.

---

### Workflow 3: Wuxia film-style fight

**What you get:** Classic Shaw Brothers-style wuxia vibes. Smooth fight motion while keeping the character style consistent.

**Example prompt:**

```Plain Text
Put the person from @image1 and the cat from @image2 into a Shaw Brothers-style wuxia film scene.
Create a smooth, flowing wuxia fight sequence.
Keep the original character visual style consistent.
Use cinematic camera movement.
```

---

### Workflow 4: Camera-move remake

**Why it works:** Upload the camera-move clip you want to imitate, then combine it with Seedream 5.0 images for character, mount, and scene.

**Prompt template:**

```Plain Text
Use the person in @image1 as the main character.
Use the big bird in @image2 as the mount.
Use @image3 as the scene/background.
Copy the camera moves and shot rhythm from @video1.
Generate a clip with a camera style consistent with the reference video.
```

> In practice you can often get 70–80% similarity, especially for “signature” camera moves.

---

### Workflow 5: 4-panel comic → animation

**Steps:**

1. **Generate a 4-panel comic with Seedream 5.0:**

```Plain Text
Please generate a vertical 4-panel comedy comic.
Panels are stacked top-to-bottom.
Style: clean Chinese webtoon style, big head + small body, round eyes, exaggerated expressions, clean linework.
Backgrounds are simple.
Colors are fresh and light.
Text must be in clear, readable speech bubbles (print-like legibility).

Characters
- Same male lead in all panels: an ordinary office worker, short black hair, gray hoodie or gray T-shirt, single-strap shoulder bag.
- Same boss in all panels: dark suit or shirt, serious expression.

Panels + dialogue
Panel 1 (office doorway): The lead peeks in, sweating. The boss stands by the door staring.
Lead bubble: “Sorry I’m late, traffic was crazy.”
Boss bubble: “Your home is three minutes from the office.”

Panel 2 (closer shot): The boss frowns. The lead explains seriously.
Lead bubble: “The elevator was broken, so I took the stairs.”
Boss bubble: “You’re on the first floor.”

Panel 3: The lead is more nervous, then gets an idea and gestures.
Lead bubble: “And I also did a good deed on the way here!”
Boss bubble: “Who did you save?”

Panel 4 (twist; downstairs garden): The lead chats with an old man. The old man says:
Old man bubble: “Hi, my name is Yi Yongwei.”

Visual requirements
- Clear panel borders.
- Speech bubbles must not cover faces.
- Text must be sharp (not blurry).
- Boss expression should have a “speechless pause” vibe.
- Overall pacing should feel light and comedic.
```

1. **Comic → animation prompt:**

```Plain Text
@image1 is a 4-panel comic.
@video1 is the reference animation style.
Turn the 4-panel comic into one coherent short animation.
Keep the comic’s art style and storyline.
```

---

### Workflow 6: VFX / transition remake

**Use case:** Remake popular TikTok/Douyin transition or VFX clips.

**Method:**

1. Download the effect clip you want to copy

1. Prepare a subject image you want to swap in

1. Upload the clip + the image to Seedance 2.0

**Prompt:**

```Plain Text
Copy the VFX and transitions from @video1.
Replace the main subject in the video with the character from @image1.
Keep the same effect timing and overall visual rhythm.
```

---

### Workflow 7: Logo / text reveal animation

**What you get:** After-Effects-style logo/text animations without needing AE.

**Example prompt:**

```Plain Text
@image1 is my logo.
Create a logo reveal animation where particles gather and form the complete logo.
Add light effects and dynamic elements.
Style it like a professional brand promo.
```

> Stuff that used to require AE can now be done with one prompt.

---

### Workflow 8: Text screenshot → video

**Use case:** Turn a screenshot of text (like a novel excerpt) into visual scenes.

**Key points:**

- Make sure the text can fit into a 15-second clip

- Don’t cram too much into one generation

**Prompt:**

```Plain Text
Generate visuals that match the text content shown in the image.
```

**What usually happens:**

- It detects environment, characters, and mood from the text

- It generates matching visuals

- It may auto-add captions in a non-broken way

---

### Workflow 9: Script table → video

**Use case:** A cheat code for ad-agency pitches.

**Method:** Create a table image that contains storyboard beats, shot types, and dialogue. Upload it to Seedance 2.0.

**Prompt:**

```Plain Text
Based on the storyboard/script table in this image, create a complete video.
Detect the shot types for each beat and the character dialogue.
Output a finished cut.
```

**Where it shines:**

- Generate a preview video for clients

- Rapid product-ad drafts

- Script visualization before production

---

### Workflow 10: Travel photos → vlog

**The easiest one:** Upload your travel photos. One sentence → a vlog.

**Prompt:**

```Plain Text
Turn these travel photos into a vlog-style video.
```

**What usually happens:**

- It keeps your original photos (no heavy edits)

- It auto-syncs to the beat

- It adds small effects

- It may **recognize locations** (world knowledge)

> Back from a trip and want motion? One prompt is enough.

---

### Practical quick tips

| Setting | What to do |
| --- | --- |
| Don’t want BGM | Add “no BGM” to your prompt |
| Don’t want captions | Add “no captions” to your prompt |
| Upload fails | Try ~720p and keep clips ≤ 15 seconds |
| Too many credits | Use image-only reference. Skip video reference. |
| BGM gets auto-added | That’s the default. Turn it off manually if you don’t want it. |

---

### How to remake viral YouTube Shorts

> Source: hands-on notes from [@realnyarime](https://x.com/realnyarime)

**Tools:**

- Video downloader: [https://v6.www-y2mate.com/](https://v6.www-y2mate.com/)

- Viral search: [https://www.shortsmonkey.com/zh/hot-today](https://www.shortsmonkey.com/zh/hot-today)

**Approach:**

1. **Find a viral clip:** Look for Shorts that blew up in the past 3 days

1. **Break down the structure:** Describe what you see in plain language

1. **Write the prompt:**

**Prompt structure:**

```Plain Text
Reference subject: `@video1`
Replacement subject: character in `@image1`
Camera reference: camera moves from `@video1`
Constraints: replace certain elements/scenes with XXX
```

**Core idea:** Change the subject or IP, but keep the creative structure (plus small twists).

---

[Previous](./10-advanced-prompt-guide-for-power-users.md)  
[Index](./README.md)  
[Next](./12-final-notes.md)
