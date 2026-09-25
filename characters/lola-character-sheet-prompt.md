# Lola — Character Sheet Prompt

AI influencer character reference sheet. Use this as the master prompt for image
models (Midjourney, Flux, SDXL, Nano Banana, etc.) to lock in Lola's look.

## Master prompt

```
Professional character reference sheet of "Lola", a 25-year-old adult woman, very attractive
AI lifestyle influencer. Long, voluminous honey-blonde hair with soft golden highlights and
subtle darker roots, styled in loose glossy waves past the shoulders. Bright blue-green eyes
with long lashes, softly arched brows, high cheekbones, small straight nose, full natural
lips with a warm confident smile. Light sun-kissed skin with a natural glow and faint
freckles across the nose. Slim, toned, feminine hourglass figure, medium-size bust, defined
waist, long legs, height around 5'7". Polished "clean girl" makeup: dewy skin, bronzed
cheeks, soft brown eyeliner, nude-pink gloss.

Outfit: fitted white cropped ribbed top, high-waisted light-wash straight-leg jeans, thin
gold layered necklaces, small gold hoop earrings, white minimalist sneakers.

Layout: clean character turnaround sheet on a plain light-grey studio background.
Top row: full-body front view, 3/4 view, side profile, back view — neutral standing pose,
same outfit, consistent proportions.
Bottom row: close-up headshots with expressions — neutral, big smile, playful wink,
flirty over-the-shoulder glance, surprised, confident smirk.
Small side panel: hair detail, eye close-up, color swatches for hair, eyes, skin, lips.

Consistent face and identity across every view, photorealistic, soft even studio
lighting, 85mm lens look, high detail skin texture, sharp focus, 8k, editorial
fashion photography quality, labeled panels, orthographic turnaround.
```

## Negative prompt

```
different faces, inconsistent features, extra fingers, deformed hands, distorted anatomy,
cross-eyed, blurry, low resolution, watermark, text artifacts, heavy makeup, plastic skin,
cartoon, anime, 3d render, childlike features, nudity
```

## Character profile

| Trait | Detail |
|---|---|
| Name | Lola |
| Age | 25 |
| Role | AI lifestyle / fashion / travel influencer |
| Hair | Long honey-blonde, loose glossy waves |
| Eyes | Blue-green |
| Skin | Light, sun-kissed, faint freckles |
| Build | Slim, toned hourglass, medium bust, ~5'7" |
| Signature style | Clean-girl makeup, neutrals, gold jewelry |
| Vibe | Warm, confident, playful, approachable |
| Content | Outfit try-ons, morning routines, beach/travel, gym, coffee dates |

## Tips for consistency

- Generate the sheet first, then use the best front headshot as a face reference
  (IP-Adapter / character reference / `--cref`) for all future posts.
- Keep the seed fixed while iterating on the sheet.
- Aspect ratio 16:9 or 3:2 works best for turnaround layouts.
- For single posts, drop the "Layout" block and replace it with a scene, e.g.
  `Lola sitting at a sunny Paris café, candid smartphone photo, golden hour`.
