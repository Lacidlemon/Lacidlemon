# Lola — Character Sheet Prompt (Goth)

AI influencer character reference sheet. Use this as the master prompt for image
models to lock in Lola's look. Built with Higgsfield's character-sheet slot layout
(split-screen: full body left, chest-up close-up right).

## Master prompt

```
Split-screen character sheet composition, left side a full-body shot of the character standing
upright in a neutral straight standing pose facing the camera with both feet flat on the ground
and arms relaxed at the sides, full head-to-toe framing with the whole body and both feet
visible, right side a tight close-up chest-up portrait of the same character, identical original
female character named Lola on both sides, single subject only exactly one person, pure white
seamless studio background, professional character sheet presentation, beautiful adult goth
woman aged 25 with fair porcelain skin, oval face with defined jawline and high cheekbones,
mature adult features, small straight nose, full lips with deep black-cherry matte lipstick and
a subtle confident smirk, bright blue-green almond eyes, smoky black winged eyeliner and dark
smudged eyeshadow, naturally muted catchlights, dark-brown arched brows, long platinum-blonde
hair with subtle darker roots, loose waves past the shoulders with wispy bangs, small silver
septum ring, visible fine skin texture with natural pores, a few faint freckles across the nose,
no beauty filter, slim athletic build with average proportions, about 5'7", wearing a black
long-sleeve fitted top with lace trim at the collar and cuffs, black high-waisted pleated
knee-length skirt with silver chain detail, opaque black tights, black leather studded belt with
silver O-ring, chunky black platform lace-up combat boots, black velvet choker with small silver
crescent-moon pendant, layered silver chain necklaces, silver rings, small silver hoop earrings,
black nail polish, no bag, natural anatomy, alternative fashion lookbook photography, soft
diffused studio lighting, cinematic realism, 4K quality, sharp focus, fully clothed
```

## Negative prompt

```
no other people, no props, no furniture, left panel standing full-body head-to-toe not cropped,
right panel tight close-up, no text, no watermark, no logos, original character not resembling
any real celebrity
```

> Note: on Higgsfield (gpt_image_2_5) the filter blocked earlier versions that mentioned
> bust size, mesh/sheer fabrics and a mini skirt. This wording passes.

## Character profile

| Trait | Detail |
|---|---|
| Name | Lola |
| Age | 25 |
| Role | AI goth / alt-fashion influencer |
| Hair | Long platinum blonde, darker roots, loose waves, wispy bangs |
| Eyes | Blue-green, smoky black winged liner |
| Skin | Fair porcelain, faint freckles |
| Build | Slim, toned, ~5'7" |
| Signature style | All-black lace and leather, platform boots, velvet choker, silver jewelry |
| Makeup | Black-cherry matte lip, smudged dark shadow, black nails |
| Vibe | Moody, confident, a little playful |
| Content | Goth outfit try-ons, makeup tutorials, thrift hauls, cemetery/cathedral shoots, concerts, dark cafés |

## Tips for consistency

- Generate the sheet first, then use the best close-up as a face reference for all future posts.
- Keep the seed fixed while iterating on the sheet.
- Use 16:9 or 3:2 for the sheet.
- For single posts, swap the composition clause for a scene, e.g.
  `Lola leaning against a gothic cathedral wall at dusk, candid smartphone photo`.
