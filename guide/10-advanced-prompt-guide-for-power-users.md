## Advanced prompt guide (for power users)

This section collects advanced tricks from the community so you can level up from “AI video beginner” to “AI director.”

### The “golden” prompt formulas

### Basic formula

```Plain Text
[Subject] + [Action] + [Scene] + [Style] + [Emotion]
```

### Full formula (pro)

```Plain Text
Subject + Action + Scene + Lighting + Camera language + Style + Quality + Constraints
```

### What each part means

| Dimension | Description | Example |
| --- | --- | --- |
| **Subject** | Specific description of the character or object | “a young swordsman wrapped in golden lightning” |
| **Action** | The motion or event that happens | “draws the sword and becomes lightning instantly”, “turns slowly and smiles” |
| **Scene** | Location + environment mood | “an old mansion at night”, “in a thunderstorm”, “a battlefield filled with blood mist” |
| **Lighting** | Lighting and shadow style | “warm dusk light”, “neon lighting”, “volumetric light piercing fog” |
| **Camera language** | Camera movement | “slow push-in”, “orbit shot”, “handheld follow” |
| **Style** | Visual style | “Japanese hot-blood anime”, “cinema-grade color”, “cyberpunk” |
| **Emotion** | Emotion and pacing | “tense and thrilling”, “high-energy”, “cold and oppressive”, “healing and fresh” |

---

### Advanced @ usage

`@` is the core syntax in Seedance 2.0. It tells the model exactly how to use each asset:

### Basic usage

```Plain Text
@image1 as the first frame                 # lock the look + starting frame
Use the person in @image2 as the main character  # assign the character
Reference @video1 camera moves             # targeted camera-move imitation
@audio1 as the music, align to the rhythm  # audio sync
```

### Advanced usage

```Plain Text
Use @image1 as the scene background, and have the person in @image2 enter the frame.
Sync the action rhythm from @video1 with the beats of @audio1.
Keep the character look from @image1 and perform the actions from @video1.
```

> **Key reminder:** When you upload multiple assets, you *must* use `@` to assign roles. Otherwise the model may interpret them randomly.

---

### Image-to-video prompting formula

**Basic structure:**

```Plain Text
[Subject] + [Motion], [Background] + [Motion], [Camera] + [Motion]
```

### Core rules

- Keep wording simple. The model will “fill in” the details.

- **Negative prompts do not work**, so don’t use them.

- Describe motion more than static details.

- Add distinguishing features (for example, “a woman wearing sunglasses”).

- Make sure your prompt matches what’s actually in the image.

### Chaining multiple actions

```Plain Text
Subject1 + Action1 + Action2
Subject1 + Action1, then Subject2 + Action2
```

---

### Text-to-video prompting formula

**Basic structure:**

```Plain Text
[Subject] + [Action] + [Scene] + [Camera], [Style]
```

### Best practices for descriptions

| Dimension | What to describe | Example |
| --- | --- | --- |
| Character details | Looks, clothing, posture | “a long-haired girl in a red trench coat, hands in pockets” |
| Environment | Nature or architecture details | “Tokyo streets after rain, neon reflected in puddles” |
| Emotional motion | Character state plus environmental motion | “looks sadly into the distance, leaves drift in the wind” |
| Mood / atmosphere | Lighting words | “warm dusk light”, “dim lighting”, “cool tones” |

---

### Camera movement terms (quick list)

| Handheld | Handheld | 轻微晃动，增加真实感 |
| --- | --- | --- |
| Follow | Follow shot | 镜头跟随主体移动 |
| Tilt | Tilt | 镜头固定位置上下转动 |
| Pan | Pan | 镜头固定位置左右转动 |
| Orbit | Orbit shot | 镜头绕主体半圆或全圆运动 |
| Truck | Stable lateral move | 镜头水平移动跟随主体 |
| Pull Back | Gentle pull-back | 镜头缓缓后退，展现全景 |
| Dolly In | Slow push-in | 镜头平滑向主体靠近 |
| Term | Chinese | What it means |
| Dolly In | slow push-in | Camera smoothly moves toward the subject. |
| Pull Back | gentle pull-back | Camera slowly moves backward to reveal more of the scene. |
| Truck | stable lateral move | Camera moves horizontally to follow the subject. |
| Orbit | orbiting shot | Camera circles around the subject (partial or full orbit). |
| Pan | pan | Camera rotates left/right from a fixed position. |
| Tilt | tilt | Camera tilts up/down from a fixed position. |
| Follow | follow shot | Camera follows the subject’s movement. |
| Handheld | handheld | Slight shake for a more realistic feel. |
| Aerial | aerial | Shot from above. |
| Aerial | Aerial | 从空中俯瞰 |

### Stability keywords

If you want a stable result, add keywords like: “static camera”, “stabilized handheld”, “no shake”, “silky smooth”.

---

### Motion intensity words

Use intensity words so the model doesn’t guess how fast or strong the motion should be:

| Intensity | Keywords |
| --- | --- |
| Low | slow, gentle, soft, slightly |
| Medium | natural, smooth, stable, continuous |
| High | fast, intense, violent, crazy |
| Very high | burst, instant, ultra-fast, berserk |

> **Tip:** A bit of exaggeration can make the motion feel more impactful.

---

### Copy-ready pro templates

### Template 1: Character short

```Plain Text
A young girl walks slowly through a forest. A breeze lifts her hair. She smiles naturally.
Medium shot. Slow push-in. 4K. Face is clear with no distortion.
```

### Template 2: Scenic footage

```Plain Text
Sunset at the seaside. Waves gently lap the beach. The camera pans slowly.
Warm orange tones. Calm and healing vibe. 4K ultra-clear.
```

### Template 3: Image-to-video

```Plain Text
Keep the character’s appearance based on the reference image.
Action: slowly raise a hand and turn around.
Natural and smooth motion. Stable camera movement.
```

### Template 4: Cinematic scene

```Plain Text
Cyberpunk city night. Neon pierces through rainy mist.
The main character in a black trench coat walks forward slowly.
Orbit follow shot. Cinema-grade color grading. 2K resolution.
```

### Template 5: Action scene

```Plain Text
A samurai draws a sword in a bamboo forest.
A flash of blade light cuts a bamboo stalk. Bamboo leaves fly everywhere.
Slow-motion capture. Fast-cut transitions. Epic visuals.
```

---

### Advanced technique roundup

### Timestamp anchors

Add timestamps in your prompt to control pacing more precisely:

```Plain Text
0:03 Mist slowly rolls in
0:07 Eyes glance left
0:12 Neon lights flicker
```

### Multi-angle hinting

Describe multiple angles to reduce face warping:

```Plain Text
Show the left side first, then turn to the front
```

> Tests show this can reduce face drift during quick head turns by ~22%.

### Physical details

Add physical details to make the motion feel real:

```Plain Text
Tires smoking, the car drifts 90 degrees
Volumetric light piercing fog
```

### Audio texture words

If you want a specific audio texture:

```Plain Text
Low, deep reverb
Creaking footsteps
```

---

### Common mistakes (and how to avoid them)

| Mistake | Description | Better approach |
| --- | --- | --- |
| Complex multi-person interactions | The model struggles with precise interaction among many people | Simplify to a 1–2 person scene |
| Vague wording | “A nice scene” is meaningless | Be specific: “a Japanese courtyard under cherry blossoms” |
| Contradictory requirements | “fast but moving slowly” | Keep the logic consistent |
| Wrong asset labels | Labels get mixed up when you upload many files | Verify every `@` label matches the right file |
| Duration mismatch | Picking the wrong length for extensions | Double-check the original clip length |
| Relying on negative prompts | Negative prompts don’t work | Use positive constraints instead |

---

### How to iterate (without wasting credits)

**Rule: change one variable at a time**

1. Keep everything else fixed

1. Change only one thing (for example, camera movement)

1. Compare results

1. Once it’s better, move to the next variable

This helps you diagnose what actually caused the improvement instead of guessing.

---

[Previous](./09-faq-plus-common-pitfalls.md)  
[Index](./README.md)  
[Next](./11-10-god-tier-workflows-with-real-examples.md)
