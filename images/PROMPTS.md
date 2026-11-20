# Image prompts for ChatGPT

How to use:

1. Paste a prompt below into ChatGPT (image generation) and pick the size shown.
2. Download the image, save it with the **file name** shown, and put it in this `images/` folder.
3. Tell Claude Code "I've added the images" and it will switch them on in `index.html` (the `IMG` list near the top of the script), preview, push and confirm.
   Any image you don't add keeps the current SVG artwork, so you can add them one at a time.

Tips: export as **.jpg** at about 1500 px on the long side and keep each file under ~400 KB (squoosh.app is free and works well).
Add this line to the end of every prompt for a consistent look:

> Brand palette: midnight navy #0B1020, warm paper #F5F3EE, sand #EBE7DD, gold accent #F2B33D. Clean, modern, premium, Sri Lankan context. No logos of real companies, no watermarks, no gibberish text.

**Important for client work (Genova, Avishka, AWAKAASHA):** an AI image is a mock-up, not work you delivered. Use the
client's real designs and photos where you have them. If you use an AI version, keep it to concept visuals, and don't
let it pass as a real photo of the client, their staff or their patients. AI images also often garble text: add
headlines and Sinhala text yourself in Canva/Figma rather than asking ChatGPT to write them.

---

## Service pages (done: generated 20 Nov 2026 and live)

| File name | Size | Prompt |
|---|---|---|
| `images/svc-branding-marketing.jpg` | Landscape 1536×1024 | Editorial flat-lay on a sand-coloured desk: brand guideline book open to a colour palette page, logo sketches, business cards, colour swatches in navy and gold, a pencil and a coffee cup. Soft daylight from the left, shallow depth of field. |
| `images/svc-content-development.jpg` | Landscape 1536×1024 | A young Sri Lankan content creator at a bright studio desk editing a social media carousel on a large monitor, a phone on a small tripod and a ring light behind, Sinhala and English sticky notes on the wall. Warm, natural, candid. |
| `images/svc-digital-marketing.jpg` | Landscape 1536×1024 | Close-up of a laptop and a phone showing abstract social media analytics charts and ad performance graphs with gold and teal lines, on a dark navy desk, soft screen glow, nighttime office in Colombo through the window, blurred. |
| `images/svc-corporate-communication.jpg` | Landscape 1536×1024 | A polished company annual report and press kit on a boardroom table, a fountain pen and a signed letter, a blurred meeting in the background, calm and credible, navy and paper tones with a small gold accent. |
| `images/svc-tech-solutions.jpg` | Landscape 1536×1024 | A modern website shown on a laptop and phone side by side on a clean paper-coloured desk, abstract dashboard widgets on a second screen, minimal and bright, subtle gold highlights. |

## Nova Sapiens studio pieces (done: generated 20 Nov 2026 and live)

| File name | Replaces | Size | Prompt |
|---|---|---|---|
| `images/nsite.jpg` | `nsite` | Landscape 1536×1024 | A laptop on a sand-coloured desk showing a dark navy agency website with a large gold four-point star and a bold headline area left blank, minimal props, soft daylight. |
| `images/nbrand.jpg` | `nbrand` | Portrait 1024×1536 | Brand identity mock-up for a creative studio: a navy business card with a gold four-point star, a paper letterhead and a navy tote bag arranged on a sand background, top-down, soft shadows. |

## Genova Ferticare (fertility clinic, healthcare: use real designs if you have them)

| File name | Replaces | Size | Prompt |
|---|---|---|---|
| `images/genova/carousel-cover.jpg` | `gcar` | Portrait 1024×1536 | Calm social media carousel cover design for a fertility clinic, deep teal (#0F5E63) background, soft abstract circle illustration of a cell, generous empty space for a headline at the centre, gentle and reassuring. |
| `images/genova/tip.jpg` | `gtip` | Portrait 1024×1536 | Friendly flat illustration for a health tip post: a simple calendar with a check mark and a stethoscope, warm paper background, teal and gold accents, lots of empty space for text. |
| `images/genova/myth.jpg` | `gmyth` | Portrait 1024×1536 | "Myth vs reality" post background for a healthcare brand: split layout, left half soft red, right half teal, simple icons of a question mark and a check mark, empty space for text. |
| `images/genova/reel.jpg` | `greel` | Portrait 1024×1536 | Vertical video thumbnail: a friendly Sri Lankan female doctor in a white coat in a bright modern clinic, smiling at the camera, space at the top for a title. Clearly a stock-style image, not a real staff member. |
| `images/genova/grid.jpg` | `ggrid` | Portrait 1024×1536 | Phone screen showing an Instagram-style profile grid of nine calm teal, paper and gold healthcare posts, illustrated icons, no real logos. |
| `images/genova/ads.jpg` | `gads` | Landscape 1536×1024 | Abstract ads-manager style dashboard on a laptop with bar and line charts in teal and gold, no real numbers or brand names, dark navy UI. |
| `images/genova/cover.jpg` | `gcover` | Landscape 1536×1024 | Three social media posts for a fertility clinic floating at slight angles over a deep teal background, soft shadows, calm and premium. |

## Avishka Premadasa (motorsport personal brand: real race photos are much better)

| File name | Replaces | Size | Prompt |
|---|---|---|---|
| `images/avishka/hero.jpg` | `ahero` | Landscape 1536×1024 | Dramatic motorsport key visual: a red and black single-seater race car at speed on a track at dusk, motion blur, bold diagonal red stripes graphic overlay, number 27, no sponsor logos, no visible driver face. |
| `images/avishka/logo.jpg` | `alogo` | Portrait 1024×1536 | Personal brand mark presentation: a bold "AP" monogram in red and off-white on a black background, racing stripe motif, clean and sharp. |
| `images/avishka/social.jpg` | `asoc` | Portrait 1024×1536 | Race weekend social post design: a racing helmet in red, black and white on a dark background with diagonal stripes, space for text at the bottom. |
| `images/avishka/reel.jpg` | `areel` | Portrait 1024×1536 | Vertical video thumbnail of a driving coach in a racing suit talking beside a car in the pit lane, helmet in hand, face not identifiable, golden-hour light. |

## AWAKAASHA අවකාශ (music / live event venture)

| File name | Replaces | Size | Prompt |
|---|---|---|---|
| `images/awakaasha/poster.jpg` | `wposter` | Portrait 1024×1536 | Concert poster background: deep indigo night sky with soft lavender stage light beams and stars, a silhouetted crowd at the bottom, lots of empty space at the top for a title. |
| `images/awakaasha/docs.jpg` | `wdoc` | Landscape 1536×1024 | Two neatly bound joint venture agreement documents on a dark wooden table with a fountain pen, warm lamp light, the text on the pages blurred and unreadable. |
| `images/awakaasha/stage.jpg` | `wstage` | Landscape 1536×1024 | Live music stage concept at night: indigo and lavender beams, one gold spotlight centre stage, silhouetted crowd in the foreground, atmospheric haze. |

The case study cover slots (`gcover`, `ahero`, `wstage`) also appear on the "Next case study" banners and on the
service pages' "Related work" cards.
