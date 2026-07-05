---
name: wanwu-jieke-haaland
description: >-
  Generate person-reference novelty ice-pop images in the fixed "万物皆可哈兰德" styles. Use when the user says 万物皆可哈兰德, 雪糕哈兰德Skill, 雪糕哈兰德, 哈兰德冰棍, 人物雪糕, Q版冰棍, or asks to turn a real person photo into HAALAND popsicle images. By default, one person photo generates four images: Style A blue jersey kissy-pout fists; Style B black jersey tongue-out side face; Style C blue seated meditation with OK mudra; Style D cream flying bare-bust with swept-back hair and sly grin. Preserve identity cues while replacing clothing, pose, expression, face angle, text, and background with the selected style.
---

# 万物皆可哈兰德

Create hand-held Q-version character popsicles from real person photos. Preserve the person's identity cues, then generate four fixed HAALAND ice-pop styles unless the user explicitly asks for only one style.

The word `HAALAND` is a required decorative text element. The number `9` appears only in the jersey styles. Do not copy a real club badge, official logo, trademark, or Erling Haaland's identity unless the user explicitly asks for that subject.

## Default Workflow

1. Use the image generation skill/tool for raster image generation.
2. Treat uploaded person photos as identity/style references only.
3. If the user provides one real person image, generate four separate images from that same person:
   - Style A: sky-blue jersey, puffy-cheek kissy pout, tiny fists.
   - Style B: black jersey, tongue-out side-facing expression, tiny fists.
   - Style C: sky-blue seated meditation body, closed eyes, compressed pout, OK mudra hands.
   - Style D: cream flying bare-bust body, swept-back hair, image-right sly grin.
4. If the user asks for only one style, generate only that style.
5. If multiple person photos are available and the user does not specify one, choose the clearest face with the most useful hairstyle/accessory details.
6. Ignore the source photo's original clothing, pose, hand gesture, expression, face angle, and background.
7. Use the same amusement-park hand-held popsicle scene and same identity cues in all images.
8. Validate each generated image against its style-specific checklist. Regenerate any style that misses clothing, expression, gesture, face direction, pose, or text.

Ask for a person reference image only when no usable person image is available. Do not ask the user for separate demo images; the four style templates below are the defaults.

## Shared Identity Rules

Preserve visible identity and styling cues from the uploaded person:

- Face shape and general likeness, simplified into a cute edible sculpture.
- Hairstyle and hair color.
- Glasses, sunglasses, earrings, hats, or other distinctive accessories.
- Overall vibe/personality only when it does not alter the fixed style lock.

Do not preserve the uploaded person's original clothing as the popsicle body. Convert hair and accessories into molded frozen-dessert details rather than realistic fabric or real hair.

## Shared Visual Style

Use a photorealistic 3D novelty ice cream/popsicle style:

- Cute Q-version character sculpture.
- Creamy matte frozen-dessert face.
- Smooth rounded features with toy-like softness.
- Sculpted hair grooves and molded accessory details.
- Glossy frozen football-jersey body or cream sculptural body with subtle frost, depending on the style.
- Tiny melt droplets along edges.
- Wooden stick with visible grain.
- Real hand holding the stick from the bottom.
- Bright natural sunlight.
- Outdoor amusement-park walkway, carousel, roller coaster, or ride structures softly blurred in the background.
- Vertical close-up product-photo composition with the popsicle centered and filling most of the frame.

Only include style-specified readable text: `9` and `HAALAND` for jersey styles, and stick-only `HAALAND` for the cream flying style. If a crest is needed in a jersey style, make it a small generic circular patch with no official logo or readable brand.

## Style A: Blue Kissy-Pout Jersey

Use this style for the first output image when generating the default set.

Always match these elements:

- Clothing/body: sky-blue molded frozen football jersey body with rounded short sleeves.
- Text: white `9` on the chest, white `HAALAND` across the lower jersey front, and vertical `HAALAND` on the wooden stick.
- Gesture: two tiny rounded frozen-dessert arms bent at both sides, with small clenched fists near the chest.
- Expression: very puffy chubby cheeks, lips pushed forward into an exaggerated kissy pout, slightly narrowed eyes, mildly furrowed brows, serious-cute expression.
- Face direction: mostly front-facing with a slight three-quarter turn toward the viewer's right side; nose, puckered lips, and gaze subtly point toward image-right.

Avoid black jerseys, tongue-out expression, raised index fingers, peace signs, open-mouth smiles, normal portrait poses, extra text, watermarks, real club badges, brand marks, and official sports logos.

### Style A Prompt Template

```text
Use case: stylized-concept
Asset type: vertical social-media preview image
Primary request: Turn the uploaded person photo into a hand-held Q-version character popsicle in Style A: sky-blue HAALAND jersey with puffy-cheek kissy pout.
Input images: Use the uploaded person photo only for identity and styling cues. Do not use the source pose, clothing, expression, face angle, hand gesture, or background.
Subject identity: A cute custom character ice pop shaped like the person in the reference photo. Preserve [face likeness / hairstyle / hair color / glasses / sunglasses / earrings / distinctive accessories], simplified into a creamy molded ice-pop sculpture.
Face direction: Mostly front-facing with a slight three-quarter turn toward the viewer's right side; nose, puckered lips, and gaze subtly point toward image-right.
Expression: Inflated chubby cheeks, exaggerated kissy pout, slightly narrowed eyes, mildly furrowed brows, serious-cute expression. No tongue, no open mouth, no smile.
Gesture: Two tiny rounded ice-cream arms bent at both sides, with small clenched fists close to the chest. No raised fingers.
Clothing/body: Sky-blue molded frozen football jersey body with rounded short sleeves, white number "9" on the chest, white "HAALAND" across the lower front, and a small generic circular crest-like patch on one side. The body is glossy icy dessert, not fabric. Do not use the person's original clothing.
Text: Include exactly "9" and "HAALAND" on the jersey body, plus vertical "HAALAND" on the wooden stick. No other readable text.
Scene/backdrop: Sunny amusement-park walkway with softly blurred carousel, roller coaster, or ride structures in the background, bright outdoor daylight, shallow depth of field.
Composition/framing: Vertical close-up product photo. A real hand holds the wooden popsicle stick from the bottom. The popsicle is upright, centered, and fills most of the frame.
Style/medium: Photorealistic 3D molded ice cream / popsicle, cute Q-version edible sculpture, premium theme-park novelty dessert.
Lighting/mood: Bright natural sunlight, cheerful, clean, appetizing.
Color palette: Creamy vanilla face, preserved hair/accessory colors from the person photo, sky-blue jersey body, white lettering and number, warm tan wooden stick, blue-sky amusement park background.
Materials/textures: Smooth creamy frozen face, sculpted hair grooves, subtle frost crystals, tiny melt droplets along jersey edges, glossy blue icy shirt, realistic wooden stick grain.
Constraints: Most important: sky-blue jersey, kissy-pout expression, tiny fists, slight image-right face direction, and text must match Style A. Preserve only the person's identity/hair/accessory cues. Avoid black jersey, tongue-out expression, raised finger, open mouth, normal portrait pose, source clothing, extra text, watermark, real club badges, and official logos.
```

## Style B: Black Tongue-Out Jersey

Use this style for the second output image when generating the default set.

Always match these elements:

- Clothing/body: black molded frozen football jersey body with rounded short sleeves and pale/white cuff accents.
- Text: white `9` on the chest, white `HAALAND` across the lower jersey front, and vertical `HAALAND` on the wooden stick.
- Gesture: two tiny rounded frozen-dessert arms raised or bent at both sides, with small clenched fists near the chest or lower face.
- Expression: very inflated chubby cheeks, a pink tongue sticking out between small lips, eyes looking toward image-right, focused brows. This is tongue-out, not puckered kiss lips.
- Face direction: slight three-quarter side turn toward the viewer's right side; nose, protruding tongue, and gaze point toward image-right while the jersey body stays mostly front-facing.

Avoid blue jerseys, puckered lips, kissy pout, duck face, raised index fingers, peace signs, open-mouth smiles, normal portrait poses, extra text, watermarks, real club badges, brand marks, and official sports logos.

### Style B Prompt Template

```text
Use case: stylized-concept
Asset type: vertical social-media preview image
Primary request: Turn the uploaded person photo into a hand-held Q-version character popsicle in Style B: black HAALAND jersey with tongue-out side-facing expression.
Input images: Use the uploaded person photo only for identity and styling cues. Do not use the source pose, clothing, expression, face angle, hand gesture, or background.
Subject identity: A cute custom character ice pop shaped like the person in the reference photo. Preserve [face likeness / hairstyle / hair color / glasses / sunglasses / earrings / distinctive accessories], simplified into a creamy molded ice-pop sculpture.
Face direction: Match the black demo style. The oversized head is a slight three-quarter side turn toward the viewer's right side; nose, protruding tongue, and gaze point toward image-right while the jersey body remains mostly front-facing.
Expression: Very inflated chubby cheeks, eyes open and looking toward image-right, focused brows, and a rounded pink tongue sticking out between small lips. This is a tongue-out expression, not kissy lips, not puckered lips, not duck face. No smile and no open laugh.
Gesture: Two tiny rounded frozen-dessert arms raised/bent at both sides, with small clenched fists near the sides of the chest or lower face. No raised fingers.
Clothing/body: Black molded frozen football jersey body, glossy icy black dessert shirt, short sleeves with pale/white cuff accents, white number "9" on the chest, white "HAALAND" across the lower front, and a small generic circular crest-like patch on one side. The body is frozen dessert, not fabric. Do not use the person's original clothing.
Text: Include exactly "9" and "HAALAND" on the jersey body, plus vertical "HAALAND" on the wooden stick. No other readable text.
Scene/backdrop: Sunny amusement-park walkway with softly blurred carousel, roller coaster, or ride structures in the background, bright outdoor daylight, shallow depth of field.
Composition/framing: Vertical close-up product photo. A real hand holds the wooden popsicle stick from the bottom. The popsicle is upright, centered, and fills most of the frame.
Style/medium: Photorealistic 3D molded ice cream / popsicle, cute Q-version edible sculpture, premium theme-park novelty dessert.
Lighting/mood: Bright natural sunlight, cheerful, clean, appetizing, glossy highlights on the black jersey.
Color palette: Creamy vanilla face, preserved hair/accessory colors from the person photo, black jersey body, white lettering and number, pink tongue, warm tan wooden stick, blue-sky amusement park background.
Materials/textures: Smooth creamy frozen face, sculpted hair grooves, smooth pink frozen tongue, subtle frost crystals, tiny melt droplets along jersey edges, glossy black icy shirt, realistic wooden stick grain.
Constraints: Most important: black jersey, tongue-out expression, tiny fists, image-right face direction, and text must match Style B. Preserve only the person's identity/hair/accessory cues. Avoid blue jersey, puckered lips, kissy lips, duck face, raised finger, open-mouth smile, normal portrait pose, source clothing, extra text, watermark, real club badges, and official logos.
```

## Style C: Blue Seated Meditation Jersey

Use this style for the third output image when generating the default set.

Always match these elements:

- Clothing/body: sky-blue molded frozen football jersey and pants integrated into a seated cross-legged body.
- Text: white `9` on the front, white `HAALAND` across the lower jersey front, and vertical `HAALAND` on the wooden stick.
- Pose: seated cross-legged lotus/meditation pose as part of the popsicle body.
- Gesture: both small rounded arms extend outward to the sides; hands form an OK/meditation mudra with thumb and index finger touching.
- Expression: eyes closed as thin horizontal slits, full cheeks, tightly compressed wrinkled pout, slight chin dimple/pressed fold, serious meditative expression.
- Face direction: mostly forward-facing, slightly downward or centered, not side-facing.

Avoid black jerseys, tongue-out expression, kissy lips, open eyes, small fists, raised index fingers, peace signs, open-mouth smiles, side-facing heads, normal portrait poses, extra text, watermarks, real club badges, brand marks, and official sports logos.

### Style C Prompt Template

```text
Use case: stylized-concept
Asset type: vertical social-media preview image
Primary request: Turn the uploaded person photo into a hand-held Q-version character popsicle in Style C: sky-blue seated meditation HAALAND jersey with closed eyes, compressed pout, and OK mudra hands.
Input images: Use the uploaded person photo only for identity and styling cues. Do not use the source pose, clothing, expression, face angle, hand gesture, or background.
Subject identity: A cute custom character ice pop shaped like the person in the reference photo. Preserve [face likeness / hairstyle / hair color / glasses / sunglasses / earrings / distinctive accessories], simplified into a creamy molded ice-pop sculpture.
Face direction: Head faces mostly forward, slightly downward or centered. Do not make the head side-facing.
Expression: Closed-eye meditation expression. Eyes are closed into thin horizontal slits, cheeks are full and slightly puffy, mouth is tightly compressed into a small wrinkled pout, and the chin has a slight pressed dimple/fold. Serious meditative expression. No tongue, no kissy lips, no smile, no open mouth, no teeth.
Gesture and pose: Seated cross-legged lotus/meditation pose as part of the popsicle body. Both tiny rounded arms extend outward to the sides, elbows slightly bent, hands forming an OK/meditation mudra gesture with thumb and index finger touching and the other fingers rounded. No fists, raised fingers, or peace signs.
Clothing/body: Sky-blue molded frozen football jersey and pants integrated into the seated cross-legged body, glossy icy blue dessert material, white number "9" and white "HAALAND" across the front, subtle pale/white collar/cuff accents. The body is frozen dessert, not fabric. Do not use the person's original clothing.
Text: Include exactly "9" and "HAALAND" on the blue jersey body, plus vertical "HAALAND" on the wooden stick. No other readable text.
Scene/backdrop: Sunny amusement-park walkway with softly blurred carousel, roller coaster, or ride structures in the background, bright outdoor daylight, shallow depth of field.
Composition/framing: Vertical close-up product photo. A real hand holds the wooden popsicle stick from the bottom. The seated popsicle is upright, centered, and fills most of the frame.
Style/medium: Photorealistic 3D molded ice cream / popsicle, cute Q-version edible sculpture, premium theme-park novelty dessert.
Lighting/mood: Bright natural sunlight, cheerful, clean, appetizing, glossy highlights on the blue jersey and pants.
Color palette: Creamy vanilla face, preserved hair/accessory colors from the person photo, sky-blue jersey/pants body, white lettering and number, warm tan wooden stick, blue-sky amusement park background.
Materials/textures: Smooth creamy frozen face, sculpted hair grooves, subtle frost crystals, tiny melt droplets along blue body edges and bottom, glossy icy blue clothing, realistic wooden stick grain.
Constraints: Most important: sky-blue seated cross-legged body, closed-eye compressed-pout expression, OK mudra hands, forward face direction, and text must match Style C. Preserve only the person's identity/hair/accessory cues. Avoid black jersey, tongue-out expression, kissy lips, open eyes, fists, raised finger, open-mouth smile, side-facing head, normal portrait pose, source clothing, extra text, watermark, real club badges, and official logos.
```

## Style D: Cream Flying Sly-Grin Bust

Use this style for the fourth output image when generating the default set.

Always match these elements:

- Body/clothing: no jersey and no normal clothing; use a monochrome creamy vanilla bare-bust/upper-body sculpture with simplified shoulders and torso.
- Text: vertical `HAALAND` printed on the wooden stick only. Do not put `9` or `HAALAND` on the body.
- Pose: forward-lunging or flying bust, as if moving horizontally while still mounted on the wooden stick.
- Hair: sculpted hair swept backward toward image-left to suggest motion.
- Gesture: arms are minimal, tucked back, or not visible. Do not use fists or OK mudra.
- Expression: mischievous sly grin with closed or slightly visible teeth, narrowed intense eyes looking toward image-right, raised/angled brows, cheek dimples, confident prankster expression.
- Face direction: strong three-quarter angle turned toward the viewer's right side; nose, eyes, and grin point toward image-right.

Avoid football jerseys, shirts, pants, blue or black clothing, `9` on the body, `HAALAND` on the body, pouts, tongue-out expressions, closed eyes, fists, OK gestures, normal portrait poses, extra text, watermarks, real club badges, brand marks, and official sports logos.

### Style D Prompt Template

```text
Use case: stylized-concept
Asset type: vertical social-media preview image
Primary request: Turn the uploaded person photo into a hand-held Q-version character popsicle in Style D: cream flying bare-bust sculpture with swept-back hair and mischievous sly grin.
Input images: Use the uploaded person photo only for identity and styling cues. Do not use the source pose, clothing, expression, face angle, hand gesture, or background.
Subject identity: A cute custom ice pop shaped like the person in the reference photo. Preserve [face likeness / hairstyle / hair color / glasses / sunglasses / earrings / distinctive accessories], adapted into a creamy molded frozen-dessert sculpture.
Face direction: Strong three-quarter angle turned toward the viewer's right side, leaning forward as if flying. Nose, eyes, and grin point toward image-right. The head dominates the frame, with side contour visible and hair swept backward toward image-left.
Expression: Mischievous sly grin with closed or slightly visible teeth, narrowed intense eyes looking toward image-right, raised/angled brows, cheek dimples, confident prankster expression. No pout, no tongue, no closed eyes, no open laugh.
Pose/body/gesture: Monochrome creamy vanilla bust/upper-body sculpture with bare shoulders and simplified torso, flying or lunging forward horizontally. Arms are minimal, tucked back, or not visible. Do not use fists, OK gestures, raised fingers, or normal clothing.
Clothing/body: Uniform vanilla/cream ice-pop material for face, hair, shoulders, and torso. No football jersey, no shirt, no pants, no body lettering. Keep it toy-like, non-realistic, edible, and sculptural.
Text: Include vertical "HAALAND" printed on the wooden popsicle stick only. No jersey text, no number "9" on the body, no "HAALAND" on the body, no other readable text.
Scene/backdrop: Sunny amusement-park walkway with softly blurred ferris wheel, carousel, roller coaster, or ride structures in the background, bright outdoor daylight, shallow depth of field.
Composition/framing: Vertical close-up product photo. A real hand holds the wooden popsicle stick from the bottom. The flying cream popsicle is upright enough to be held but sculpted as a forward-lunging flying bust, centered and filling most of the frame.
Style/medium: Photorealistic 3D molded ice cream / popsicle, cute Q-version edible sculpture, premium theme-park novelty dessert.
Lighting/mood: Bright natural sunlight, playful, funny, clean, appetizing, glossy highlights and frost on the cream dessert surface.
Color palette: Monochrome creamy vanilla ice-cream body and hair, preserved accessory colors only if they are distinctive, warm tan wooden stick, brown "HAALAND" lettering on the stick, bright blue-sky amusement park background.
Materials/textures: Smooth creamy frozen face, sculpted windswept hair grooves, subtle frost crystals, tiny melt droplets on shoulders and edges, realistic wooden stick grain.
Constraints: Most important: cream bare-bust body, flying/lunging pose, swept-back hair, image-right three-quarter face direction, sly grin expression, and stick-only HAALAND text must match Style D. Preserve only the person's identity/hair/accessory cues. Avoid football jersey, blue or black clothing, number 9 on the body, HAALAND on the body, pout, tongue, closed eyes, fists, OK gesture, normal portrait pose, source clothing, extra text, watermark, real club badges, and official logos.
```

## Validation Checklist

When generating the default set, validate all outputs:

- All images are clearly hand-held popsicles, not normal portraits.
- All preserve the same person's key face, hair, and accessory cues.
- All use an amusement-park product-photo scene with a real hand holding the stick.
- Styles A-C include `9` and `HAALAND` on the jersey/body and `HAALAND` on the stick when visible.
- Style D includes `HAALAND` on the stick only, with no `9` or body text.
- No image contains readable text other than style-specified `9` and `HAALAND`.
- No image uses a real club badge, brand mark, watermark, or official sports logo.

Style A specific checks:

- Sky-blue frozen jersey body.
- Kissy-pout expression, no visible tongue.
- Small clenched fists near the chest.
- Slight image-right face direction.

Style B specific checks:

- Black frozen jersey body.
- Tongue-out expression, not puckered lips.
- Small clenched fists raised or near the chest/lower face.
- Three-quarter side-facing head toward image-right.

Style C specific checks:

- Sky-blue seated cross-legged jersey/pants body.
- Closed eyes, compressed wrinkled pout, and slight chin press.
- OK/meditation mudra hands, not fists.
- Mostly forward-facing head, not side-facing.

Style D specific checks:

- Monochrome cream bare-bust/upper-body sculpture, not a jersey.
- Sly grin, narrowed eyes, and image-right three-quarter face direction.
- Swept-back hair and flying/lunging pose.
- Stick-only `HAALAND`, with no body text or number `9`.

If a check fails, regenerate only the failed style with stronger wording for the missed constraint.
