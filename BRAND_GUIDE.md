# Chasing Sun Brand Guide

This is the working source of truth for website, presentation, document and
social-media design. Keep executions warm, precise and recognisably rooted in
real agricultural work.

## Brand idea

**From the Ground Up** connects cultivation, commercial discipline and the
daily movement of the sun. Sun and orbit references should support the story;
they should never make the brand feel like a space or software company.

## Colour

| Role | Name | Hex | Use |
| --- | --- | --- | --- |
| Primary | Sunflower | `#FFD34E` | Prominent surfaces, section accents and brand moments |
| Deep | Sunflower Earth | `#6A4B00` | Headlines, footer and high-contrast yellow-led surfaces |
| Deep | Night Forest | `#082C25` | Hero overlays, footer and high-contrast surfaces |
| Agricultural | Crop Green | `#6A961F` | Small crop-specific accents only |
| Accent | Sunset Gold | `#F2B51D` | Calls to action, sun discs and key details |
| Surface | Sun Wash | `#FFF9E8` | Main page and soft section backgrounds |
| Surface | Warm Cream | `#FFF8E6` | Panels and soft page backgrounds |
| Text | Soft Charcoal | `#626963` | Body copy and secondary information |

Yellow is the dominant brand colour, expressed through sunflower accents,
warm cream surfaces and golden light. Forest green remains a supporting colour
for agricultural context. Use Sunflower Earth or Night Forest behind white text
to maintain accessible contrast.

## Typography

- **Display and editorial headings:** Playfair Display, semibold or bold.
- **Body, labels and interface:** DM Sans, regular through semibold.
- Use no more than these two families in one execution.
- Use sentence case for titles. Reserve uppercase with wide tracking for short
  section labels.
- Prefer short, balanced headlines and comfortable body-copy line lengths.

Both families are Google Fonts and should be used consistently in digital
templates where available. Use Georgia and Arial as fallbacks respectively.

## Sun and orbit motif

- Use a thin circular orbit with one small gold sun disc.
- Use it for section labels, numbered steps, connectors or a single hero
  composition—not all of them at once.
- Keep line weight light and geometry simple.
- Do not use planetary illustrations, star fields or literal space imagery.

## Icons

- Use rounded outline icons with consistent stroke width.
- Default to forest green; use one small gold detail where emphasis helps.
- Avoid mixing filled, illustrated and outline icon families.
- Core subjects are growing, sourcing, traceability, quality, logistics,
  markets and farm visits.

## Photography

- Lead with professional AI-generated agricultural imagery and crop-only farm
  photography. Do not use photographs of real people on the website.
- Prefer early-morning, late-afternoon or naturally warm directional light.
- Use wide environmental frames alongside close crop and process details.
- Keep greens natural and saturation restrained.
- Avoid generic handshake, boardroom, stock-market and anonymous warehouse
  photography.
- Keep generated scenes operationally credible and disclose materially
  generated imagery in alt text or accompanying metadata where appropriate.

## Writing voice

Chasing Sun sounds confident, precise, commercial and human.

- Lead with what we grow, source or deliver.
- Prefer specific claims over superlatives.
- Use short sentences and concrete agricultural language.
- Explain technology through the operational value it creates.
- Avoid vague phrases such as “revolutionising agriculture” unless supported by
  evidence.

Example: “Grown under cover and harvested to specification” is preferred to
“Delivering world-class agricultural excellence.”

## Asset implementation

The website colour and type tokens live in the Tailwind configuration inside
`index.html`. The current hero uses `images/greenhouse/hero-golden-hour-v2.webp`.
AI-generated project assets use the `ai-` filename prefix. Update this guide and
the implementation together when the system changes.
