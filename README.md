# ALTERIMAGE V8.1 — Your Identity Studio

A creative, mobile-friendly, step-by-step cyber avatar studio with optional extras that stay tucked away until visitors want them.

## New in V8

- **Vibe Kits:** on the character-selection step, expand *Try a Vibe* to apply one of three cohesive looks: Ghost Mode, Voltage, or Sol Shift. Your chosen character stays the same and all details remain editable.
- **My Looks:** on the Finish step, expand a personal collection of up to six saved characters. SAVE MY LOOK adds the current design; each entry can be loaded or deleted. Looks stay in the browser's local storage on the current device, not in an online account. Clearing browser storage removes them.
- **My ID Card:** on the Finish step, expand and download a 1200 × 1500 PNG that combines the current avatar with its character type, signal, custom name and a local identity code. It is an artwork, **not an NFT or an on-chain asset**.

## New in V8.1

- **FOMO Banner:** a one-tap profile-banner size in Banner Forge. Export as a 1500 × 600 PNG with your existing avatar, name, tagline, colors and layout. This is a suggested wide profile preset, **not a verified official FOMO dimension**; upload and check how FOMO crops it.

## Existing features

- Eight-step wizard: Character → Eyes → Expression → Outfit → Accessories → Colors → Background → Finish.
- Four character archetypes with independently customizable Face DNA; Basic Glow eyes, None/no-mouth expression, eye colors, facial markings, crests and finishes.
- Twelve color palettes, eight outfits, head accessories, ten emblems, and twelve backgrounds (including six Solana-inspired themes with editable gradients, glow and patterns).
- Minimal Mode shortcut; downloads, client-side saved looks, and portable URL links; custom X, FOMO, Discord and community banner generator.
- Removed Halo accessory and Halo Rings eye style; unsupported legacy settings fall back to valid options.

## Deploy for free

The HTML site does not need a backend or build framework. To use **Netlify Drop**, unzip and upload the folder containing `index.html` (or use the connected GitHub repository in the Netlify dashboard). A free `*.netlify.app` address will be assigned when the site is published. Free-tier limits apply.

For **Render** Static Sites, use the included `render.yaml`, or manually create a static site with:
- Build command: `mkdir -p public && cp index.html public/index.html`
- Publish directory: `public`

## Privacy & limitations

Your customizations and favorites are kept locally in your browser. The site does not include real AI image generation, user accounts, real-time cross-device sync, wallet integrations, token launches, or on-chain verification. Solana-inspired visuals are original artwork; ALTERIMAGE is not affiliated with Solana or the Solana Foundation.