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

[Previous](./02-recommended-seedance-2-0-pro-access-point.md)  
[Index](./README.md)  
[Next](./04-prompt-formula-and-core-syntax.md)
