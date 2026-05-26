## 8 core use cases

### Use case 1: Character + look consistency

**The problem:** Faces change between shots, product details disappear, or the scene randomly jumps.

**What to do:** Upload a reference image and describe the character features clearly.

**Example prompt:**

```Plain Text
Use the man in @image1 as the main character.
After work, he walks down a hallway looking exhausted. His steps slow and he stops at his front door.
Close-up on his face. He takes a deep breath, resets his mood, and relaxes.
Close-up of him searching for his keys, inserting the key, and opening the door.
He enters a warm, cozy home. His young daughter and a pet dog run over happily to hug him.
Natural dialogue throughout.
```

![consistency-row1-ref.png](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/9d536216-8a32-4ebc-a520-ccfbb0d0a3c2/consistency-row1-ref.png?table=block&id=30bd38a8-50fc-814b-a12e-d83fb3b8e7b0&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=d8PiLa_V73heZrmBHnjVCifAS2T2kajj9c4cLzyqvjY)

Video: [consistency-row1-result.mp4](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/06585824-bf52-4b97-8a7c-295690fbf8d7/consistency-row1-result.mp4?table=block&id=30bd38a8-50fc-819b-98fe-ea1b6385970d&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=shGteq4_UBR5U2KB1fprlSYiqJMPgG-UYitiWZczX_w)

**Tip:** The clearer you describe the character features in the prompt, the more consistent the result. You can often reach 95%+ consistency.

---

### Use case 2: Copy camera moves and actions

**The problem:** You want cinematic camera moves, but you don’t know the “proper” filmmaking terms.

**What to do:** Upload a reference video and let the model copy it.

**Example prompt:**

```Plain Text
Use the man from @image1 as the character reference.
Place him in the hallway scene from @image2.
Fully copy ALL camera moves from @video1, including the main character’s facial expressions.
The camera follows him running around the corner in @image2.
In the corridor scene from @image3, start from a follow-behind angle, then orbit from a low angle to the front of the character.
Then pan right 90° to show the forked hallway in @image4.
After a sudden stop, pan right 180° and push in to a face close-up: the character is panting.
From the character POV, look around the environment.
Copy the fast left-right orbiting camera move from @video1 to show the scene.
Then pull back into the scene from @image5 and keep tracking the character from a side-follow angle as he runs.
```

![image.png](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/754fec69-f8d8-475a-9dcf-64c15c206958/image.png?table=block&id=30bd38a8-50fc-81be-857b-f8c904db1681&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=H6BMuSAtVx3Lq30v84lU7MxV6O-G4JSe5INK3Qn2BDw)

![image.png](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/afbf0ae9-2998-4985-8f41-4cea8fb55bf2/image.png?table=block&id=30bd38a8-50fc-81b0-a8fb-e3ad8bce291a&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=smx-sr3PN60YSoWy783xj3NUFucl3b2ZJfBstwZ7twM)

![image.png](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/b13ef4b0-d9e4-494e-9665-f04c0ae43b19/image.png?table=block&id=30bd38a8-50fc-8171-bbba-ecd145ec6d0f&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=0d7ViUcWe-8IEqN8LdHx2BhVrsq9W4D7tGiEzJWD4go)

![image.png](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/44e737fb-864c-4b68-9762-2da9743774b3/image.png?table=block&id=30bd38a8-50fc-8131-a992-efc2ce3f3728&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=DJcC4tuv8iWUeCcYT_aHPedSX6IhHdEY7ogRwO26J2A)

![image.png](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/86fe30d2-bfd3-4dfc-83cb-631afeb235cc/image.png?table=block&id=30bd38a8-50fc-81d4-8984-e40fd38d6ad4&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=HZHSn-m4l1eLFHO_GJvURhgTIOh0_2nfgLmlsJ6L2Qs)

Video: [camera-motion-video-03.mp4](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/32bb79e3-b4a3-4d92-a3c2-1d01291dfea3/camera-motion-video-03.mp4?table=block&id=30bd38a8-50fc-81b8-a8e2-d93a59f54d33&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=hFavt45S2gvHwlXL9jNuLihWlEnz7AHKMXBP7s8PK4I)

Video: [camera-motion-video-04.mp4](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/aecdb3a6-05c6-4fc0-96e5-a29c99f169e3/camera-motion-video-04.mp4?table=block&id=30bd38a8-50fc-816b-85f7-fa5da2ba58fd&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=Pquz8igaCsIv7EnUn4QZHEFucbDr5Gy6DGJaJYk55ng)

**What it can copy:**

- Camera moves (push in, pull back, pan, tilt, track, etc.)

- Character actions and facial expressions

- Complex motion like dancing and fighting

- Product spins and close-ups

---

### Use case 3: Copy VFX and transitions

**The problem:** You see cool transitions and effects, but you can’t recreate them.

**What to do:** Upload the reference clip and let the model “copy the homework.”

**Example prompt:**

```Plain Text
Replace the person in @video1 with the character from @image1.
Use @image1 as the first frame.
Put a futuristic sci-fi AR headset on the character.
Copy the camera movement from @video1, including close orbit shots.
Switch from a third-person view to the character’s POV, as if traveling inside the AR headset.
Transition into the deep blue universe from @image2.
Several spaceships fly into the distance. The camera follows them.
Transition into the pixel world from @image3. Fly low over the pixel forest. Show stylized tree growth forms.
Then tilt up and rapidly travel into the pale green textured planet from @image4.
Fly past and skim over the planet’s surface.
```

![image.png](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/1b7d2abb-8afc-4fec-9c0e-d2aa8e37d857/image.png?table=block&id=30bd38a8-50fc-818e-bb99-f7de4624f6af&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=BqJf4klL0rFaXMGMOQOIIJfR696W-_rhpPdms9O0fGw)

![image.png](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/cd3c6af4-c943-4403-8ed5-50fdafc3e16c/image.png?table=block&id=30bd38a8-50fc-812c-9481-d9032f8b52c2&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=rXFxuNDV7Yjq3wUhCm3SVwMKXMfGBpZhTdv6HOQZE-4)

![image.png](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/588e15d1-22d4-459f-a717-18211a33ac24/image.png?table=block&id=30bd38a8-50fc-8111-b1a9-d0caaf36ab83&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=P-yXAX0hOUJptWfBC-9JP1cyebomrcWIZBleWS1B7Y8)

![image.png](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/718b8b18-1e23-4c19-b398-7e9264e38925/image.png?table=block&id=30bd38a8-50fc-81b1-a9dc-d5c9c1543674&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=KYvPboHmnYCdaXmzwlS9AoC0zpVaBeumksGPlOHhlkg)

Video: [creative-effects-video-04.mp4](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/789ad9fd-b3f3-452e-9a9c-b9872c36fcdc/creative-effects-video-04.mp4?table=block&id=30bd38a8-50fc-81c8-bd88-c0582cb7b663&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=xzAbFcgnJ3dnZ_W0Ofbs8TX5SANRpLNUAcWw05StSG8)

**Effects it can often copy:**

- Particle dissolve / gather

- Creative transitions (through a pupil, shattering puzzle, etc.)

- Ink-wash looks

- Beat-synced outfit changes

---

### Use case 4: Extend a video

**The problem:** The video is too short and you want it to continue.

**What to do:** Upload the original video and describe what happens next.

**Example prompt:**

```Plain Text
Extend the video forward by 10 seconds.
In warm afternoon light, start with the row of awnings at the street corner fluttering in the breeze.
Slowly tilt down to a few small daisies peeking out near the base of the wall.
Then the main character’s red sneakers enter frame.
He squats by a flower stand, smiling as he pulls a big bunch of sunflowers into his arms. Petals brush against his white T-shirt.
As he steps onto his skateboard, the vendor laughs and shouts, “Watch out, petals are flying!”
He waves back, then starts to skate away.
A few golden petals break free first and land on the skateboard deck.
```

Video: [video-extension-video-07.mp4](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/d97ed7db-7774-4fc9-a36a-cee5c14a6a64/video-extension-video-07.mp4?table=block&id=30bd38a8-50fc-81b4-b6a2-e6435737f38c&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=sP2qfA59FxsFhNrsWD68m3hsLriX1Bdyc1kqIlHW7Ro)

Video: [video-extension-video-08.mp4](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/0a953ec0-17f1-445a-b439-103af0384484/video-extension-video-08.mp4?table=block&id=30bd38a8-50fc-819e-a1de-d09c4fedf88f&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=wR0zwpPfLSHZrtjeb0ejY8aUQUkLf4kLoZk3fZEitvE)

**Notes:**

- The generation length equals the *extra* seconds you want to add

- For example, to add 5 seconds, set generation length to 5 seconds

- Both forward and backward extension are supported

---

### Use case 5: Edit an existing video (story remix)

**The problem:** You have a video and want tweaks, but don’t want to redo it from scratch.

**What to do:** Edit specific parts of the existing clip.

**Example prompt:**

```Plain Text
Replace the female singer in video 1 with the male singer from image 1.
Copy the original actions exactly.
No cuts. One continuous shot.
Keep the band performing music.
```

![image.png](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/8df2a309-76be-4b2a-b2e0-fa99e93eef53/image.png?table=block&id=30bd38a8-50fc-8133-9782-e410292a0444&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=ij793dmyjGsWXFtfVfBpnHdGm7dmWN9ntYQCoWclEI8)

Video: [video-editing-video-05.mp4](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/a84d03a7-8f4d-4aed-8b4f-3fd8600c0774/video-editing-video-05.mp4?table=block&id=30bd38a8-50fc-81fd-9bdd-e6582acf2f19&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=rOhUxi5f9lFLDEd5viZPBMcMJWxC_ayDW3VlXAl3SXY)

Video: [video-editing-video-06.mp4](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/a470413f-6ec1-44c5-9567-9d78a7170031/video-editing-video-06.mp4?table=block&id=30bd38a8-50fc-8143-853a-e7cd24174dd7&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=XwEVkAvKa-alOsBwLe5HTAvyE1g27YIfXk25JfqM8uI)

**What you can edit:**

- Replace characters (swap A with B)

- Change hair or outfits

- Flip the story

- Add new elements (like a shark behind the character)

**Reference vs. Edit:**

- **Reference:** Borrow the style or motion and generate something new

- **Edit:** Modify the original asset directly

---

### Use case 6: Audio + voice

**The problem:** Your video has no sound, or the sound feels off.

**What to do:** Upload an audio reference, or write dialogue directly in your prompt.

**Example prompt:**

```Plain Text
Static camera.
A centered fisheye lens looks downward through a circular opening.
Use video 1 as the fisheye reference.
Make the horse from @video2 look into the fisheye lens.
Copy the speaking/mouth movement from @video1.
Use the audio/BGM and sound texture from @video3.
```

Video: [audio-precision-video-01.mp4](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/84936303-92ea-41f5-8447-20c05e11b2bf/audio-precision-video-01.mp4?table=block&id=30bd38a8-50fc-814a-bb5f-e19c3e7b9a8f&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=3WENqOqCYaOsUwqnMHayXxLbpwFMbmMQRFZUTYtTO2o)

Video: [audio-precision-video-03.mp4](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/0f0ec98f-fde2-4eed-a432-7153d34e1140/audio-precision-video-03.mp4?table=block&id=30bd38a8-50fc-8110-9d0e-f4feddee1b6c&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=EkQYBQ10NHRZDIItt92flMVvLt5nYzS4e66ywsq2b1A)

Video: [audio-precision-video-02.mp4](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/542fe2d6-00f2-4727-a07c-2f3fa4e5d667/audio-precision-video-02.mp4?table=block&id=30bd38a8-50fc-8151-b250-ed2100950b84&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=pZVlil8jHjFGynjU2DPRhd1CcSIwRvcnlXOXWXeqKN8)

Video: [audio-precision-video-04.mp4](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/02bcd71b-903c-460c-859d-ba0232e949f2/audio-precision-video-04.mp4?table=block&id=30bd38a8-50fc-81d7-9ed4-d96bfb1d2df4&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=yC-X03-8ROjBs6p8yKX-adIE6ULc5oVS7ieQofXniXU)

**Or just write dialogue:**

```Plain Text
In the center, a girl wearing a hat gently sings and says, “I’m so proud of my family!”
Then she turns and hugs the Black girl in the middle.
The Black girl responds emotionally, “My sweetie, you’re the heart of our family,” and hugs back.
On the left, the boy in a yellow shirt says happily, “Folks, let’s dance together to celebrate!”
On the far right, a girl replies, “I’ll bring the music!”
Latin music starts playing in the background.
On the left, a woman in an orange dress (Julieta) smiles and nods.
On the right, a braided-hair woman (Luisa) clenches her fist and pumps her arm.
People in the crowd start stepping to the beat. Kids clap along.
The whole family forms a circle and dances in a colorful street, spreading joy and warmth.
```

![image.png](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/a6fc3415-4174-45fe-8d9d-3d2797c14009/image.png?table=block&id=30bd38a8-50fc-8138-9895-e38ebe35e3f6&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=j7NgyY392sxGYn_jgP0aaDUkicAkQnTV6xHKfkZDtN8)

Video: [audio-precision-video-06.mp4](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/e3ff211e-70a3-433a-b671-54327c5b9a96/audio-precision-video-06.mp4?table=block&id=30bd38a8-50fc-818c-9a6e-eb1efabb308b&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=eCnZnX4Ra6lKld8tkiEDFg7BNnwFnPlsJrySHa_UwkQ)

---

**Supported audio types:**

- Narration

- Character dialogue (multi-language: Chinese, English, Korean, etc.)

- Background music

- Sound effects (footsteps, ambience, etc.)

- Even opera-style singing

### Use case 7: Beat sync to music

**The problem:** You want visuals to hit the beat.

**What to do:** Upload a music reference video and let the model sync the cuts and motion.

**Example prompt:**

```Plain Text
The girl in the poster keeps changing outfits.
Use the clothing styles from @image1 and @image2.
She carries the bag from @image3.
Match the rhythm and pacing to @video1.
```

---

![image.png](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/2a5c8158-90bd-4f06-8d43-61c0e576b487/image.png?table=block&id=30bd38a8-50fc-819e-b53a-d8a7c206dd23&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=Dmy6yHJ7GP5UyDyegTHStvRX2nwaFMBWBdSYCXJkBfQ)

![image.png](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/ebea03c9-216a-457d-89d2-9dba25db74bb/image.png?table=block&id=30bd38a8-50fc-8128-a0c0-e266df37eb5b&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=9De95gaWIj1l5_E6jpkALV9KtPSkioHssteiRYS6Vg4)

![image.png](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/4e2b0531-098d-4e91-ac45-2d7112021c47/image.png?table=block&id=30bd38a8-50fc-8140-bc95-fe1bc83a563c&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=hyic9ztz53-5RGAlZO3xe83OA40LE-aFFsoz-_p_Cmw)

![image.png](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/85244dad-516f-4361-992e-0084c8638005/image.png?table=block&id=30bd38a8-50fc-8150-9bf1-c39e40c170e7&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=TNzVLQkj8XXCQ3Rx5Kt1cnNP9v5ZgDVpbVPjVroHfCA)

Video: [beat-sync-video-01.mp4](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/7a12ae05-951d-49dd-b647-1354f573d4e1/beat-sync-video-01.mp4?table=block&id=30bd38a8-50fc-81f1-9a36-f6b47903fae8&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=DDO09BtNfZn04Ac-dhbuKV2K59u9BEA5UmUR3_8o6vs)

Video: [beat-sync-video-02.mp4](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/331ec3d8-668a-417f-b05e-3b95edd682cb/beat-sync-video-02.mp4?table=block&id=30bd38a8-50fc-8147-9993-eb057d65fa3e&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=UdbOeGx4EFkhCUJTxKnm_mOJrLpKAYQU8MVO54uTfug)

### Use case 8: One-take (no cuts)

**The problem:** You want a smooth long take, but it keeps cutting.

**What to do:** Explicitly say “one take, no cuts” and describe the camera path in detail.

**Example prompt:**

```Plain Text
Based on the exterior shot in @image1, do a fast push-in from a first-person POV into the cabin interior.
In the near/mid foreground, a young deer from @image2 and a sheep from @image3 sit by the fireplace, drinking tea and chatting.
Push in to a close-up of the teacup. Match the teacup style from @image4.
```

![image.png](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/abd23054-09e8-4ad1-a076-fd29338fc095/image.png?table=block&id=30bd38a8-50fc-8145-a817-e5d1a1b5193d&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=WiHOkL4VO9UEuvYTt7JcDX_TQpSZXOkuW18ojX5KQwI)

![image.png](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/44a75f81-51cc-49fd-bd6c-7eef39ffa2c3/image.png?table=block&id=30bd38a8-50fc-8149-89b8-c177f9173f86&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=K_j86HXNgnM713llgdKbhwa2dlF5FpwmY_YsNyah9ec)

![image.png](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/46ec6481-34fa-4fcc-8c41-a4617c6518f7/image.png?table=block&id=30bd38a8-50fc-81d9-84b8-c56cb69648b8&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=0vUCI_8tPlkwS6q1M-0H6gGJE34nerOjnf5Vb24B4Fo)

![image.png](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/8d41473f-6d34-4f20-97a7-97ea6b0fa9ce/image.png?table=block&id=30bd38a8-50fc-81cd-adb8-c1ae60cfc52e&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=2JMzrHhmRq90_cErkMBZY3RbVStdKbq3ZTvsDN1GbQU)

Video: [long-take-video-04.mp4](https://file.notion.so/f/f/f03d38a8-50fc-81bd-ba44-00039a771382/06df903e-f29b-46e4-9aec-ad41e88511f5/long-take-video-04.mp4?table=block&id=30bd38a8-50fc-8110-bbf0-c48d77b69d7c&spaceId=f03d38a8-50fc-81bd-ba44-00039a771382&expirationTimestamp=1779789600000&signature=QzFOnQn4dTLLAXwD6AeXPL-rroOxa1RL3EkePKTD8fM)

---

[Previous](./04-prompt-formula-and-core-syntax.md)  
[Index](./README.md)  
[Next](./06-camera-language-cheat-sheet.md)
