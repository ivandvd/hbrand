# Hyperwood Brand Kit

Visual identity edition 1.0 · October 28, 2026

The selected identity is **15 / Morph**: the connected, fluid abstract symbol with Hyper Neon, Ink, and White.

## Start here

1. Read the brand guidelines PDF. The PowerPoint version provides editable page layouts and copy.
2. Install Manrope and IBM Plex Mono from `05-Fonts` before editing the presentation or SVG templates.
3. Use the SVG logo masters in `01-Logos/SVG`. Use PNG only where the application cannot accept SVG.
4. Replace bracketed template copy with approved content before publishing.

## Contents

- `01-Logos`: symbol, outlined wordmark, stacked lockup, and horizontal lockup in black, white, and neon. Transparent PNG exports are 2048 px wide.
- `02-App-and-Social`: app icon, circular avatar, banner, and favicon sizes. App tile sources are square with no platform-specific corner mask.
- `03-Graphics`: three graphic devices, 12 interface icons, liquid editorial artwork, physical application concept, and an animated SVG reveal.
- `04-Templates`: square, portrait, and story social formats; presentation cover; business-card front and back; A4 letterhead. SVG versions retain editable text. PNG versions are previews.
- `05-Fonts`: Manrope static weights and IBM Plex Mono Regular, with their license texts.
- `06-Tokens`: color, spacing, font, corner-radius, and timing values in JSON and CSS.

## Core specifications

| Role | Value |
|---|---|
| Hyper Neon | `#CCFF00` |
| Ink | `#0A0A0A` |
| White | `#FFFFFF` |
| Paper | `#F4F5F0` |
| Slate | `#62685D` |
| Line | `#D9DCD2` |
| Primary type | Manrope Regular / Bold |
| Technical type | IBM Plex Mono Regular |
| Logo clear space | At least one quarter of the symbol height |

Keep the logo proportions and orientation unchanged. Do not retype its wordmark. The outlined wordmark is distinct from the document typeface.

## Production notes

The SVG masters were reconstructed from the approved concept image for this edition. They preserve its recognizable contour and wordmark. Use these files consistently as the production master; generated mockups are visual examples rather than geometry references.

The artwork uses sRGB. Digital neon does not translate exactly to process ink. For fluorescent output, approve a spot-ink sample on the final substrate. For process printing, request the printer's ICC conversion and proof. No exact Pantone or universal CMYK equivalence is assigned.

Business-card artwork is designed at an 85.6 × 54 mm trim ratio. Add 3 mm bleed and maintain at least 4 mm internal safety during print preparation. Letterhead targets A4. The SVG dimensions describe the canvas; set the intended physical dimensions in the print application.

Social templates target 1080 × 1080, 1080 × 1350, and 1080 × 1920. The supplied banner is 1500 × 500. Verify the crop and overlay behavior in the destination platform before posting.

The animated SVG demonstrates a 600 ms reveal. It respects `prefers-reduced-motion`. The editable guide's motion page is a static storyboard.

## Product context

This identity is designed around an emerging blockchain ecosystem. Network architecture, Ethereum relationship, EVM compatibility, chain configuration, token details, product availability, official domains, and launch status were not confirmed in the brief. Website and transaction screens in the guide are visual studies, not a deployed product. Confirm these details before publishing factual product copy.

## Fonts and editing

The supplied Manrope files are static instances of the Google Fonts variable source. IBM Plex Mono is supplied unchanged. License texts accompany both families. Install the fonts before opening the editable PowerPoint to avoid substitution.

SVG templates can be edited in software that supports SVG text and paths. Keep logos as paths. Live template text depends on the supplied fonts; convert text to outlines only in a separate print export after copy approval.

## File conventions

Use names such as `hyperwood-symbol-neon.svg` and keep color and layout names intact. Make new versions for modified assets. Keep the approved master files alongside any working copies.
