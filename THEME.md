# Succulents Box Marketing Workspace Theme

Version 1.0
Purpose: Internal marketing tools and lightweight operational dashboards

## 1. Theme direction

The theme should feel:

- Young, friendly, and optimistic
- Clearly connected to the Succulents Box brand
- Playful without looking childish
- Easy to scan during everyday work
- More like a creative team workspace than corporate software

The visual balance is approximately:

- 65% warm neutrals and white
- 25% green brand colors
- 10% soft supporting accents

Green is the anchor, not the entire canvas.

## 2. Design principles

### Brand first

Use Succulents Box mint green for primary actions, active states, highlights, and plant illustrations. Use deep green for text, outlines, and structure.

### Playful structure

Use chunky outlines, asymmetric corner radii, small rotations, and solid offset shadows. Keep the underlying grid orderly.

### Calm surfaces

Large surfaces should use cream, white, or very pale mint. Avoid filling the entire page or every component with saturated green.

### Useful personality

Decorative elements should relate to plants, gardening, or the team's work. Avoid unrelated floating blobs or generic abstract artwork.

## 3. Color system

### Core brand colors

| Token | Hex | Use |
|---|---:|---|
| Brand green | `#4BC0A8` | Primary actions, active accents, illustrations |
| Dark green | `#08705D` | Secondary brand accents and links |
| Deep green | `#073F35` | Headlines, borders, active navigation |
| Light mint | `#9DE3D4` | Soft highlights and decorative fills |
| Pale mint | `#E4F6F2` | Quiet backgrounds and focus details |

### Neutral colors

| Token | Hex | Use |
|---|---:|---|
| Page background | `#FAF8F2` | Main canvas |
| Cream | `#FFFDF7` | Warm neutral surface |
| White | `#FFFFFF` | Cards, search, filters |
| Ink | `#17382D` | Standard body text |
| Muted text | `#63746D` | Descriptions and secondary labels |
| Border | `rgba(18, 60, 44, 0.13)` | Quiet dividers |

### Supporting accents

| Accent | Hex | Suggested use |
|---|---:|---|
| Soft yellow | `#F7E7A1` | Content and writing |
| Soft coral | `#FFD2C8` | Product listings |
| Soft lavender | `#CFC6EF` | Communications |
| Soft mint | `#C8E9DF` | Inventory and data |
| Soft blue | `#C9DFF0` | Analytics |
| Soft mauve | `#EAD7E7` | Team operations |

## 4. Typography

```css
font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
```

| Role | Size | Weight | Line height |
|---|---:|---:|---:|
| Hero headline | `clamp(34px, 6vw, 62px)` | 850 | 0.95 |
| Section title | 16px | 740 | 1.3 |
| Card title | 17px | 800 | 1.3 |
| Hero body | 16px | 520 | 1.5 |
| Body description | 12.5px | 400 | 1.55 |
| Small label | 10–12px | 650–850 | 1.3 |

## 5. Tokens (CSS starter)

```css
:root {
  --brand: #4bc0a8;
  --brand-dark: #08705d;
  --brand-deep: #073f35;
  --brand-light: #9de3d4;
  --brand-pale: #e4f6f2;

  --surface-page: #faf8f2;
  --surface-cream: #fffdf7;
  --surface-card: #ffffff;
  --surface-hero: #eef5e9;

  --text-strong: #073f35;
  --text-body: #17382d;
  --text-muted: #63746d;

  --accent-yellow: #f7e7a1;
  --accent-coral: #ffd2c8;
  --accent-lavender: #cfc6ef;
  --accent-mint: #c8e9df;
  --accent-blue: #c9dff0;
  --accent-mauve: #ead7e7;

  --border-strong: 1.5px solid #073f35;
  --radius-card: 22px;
  --radius-control: 18px;
  --shadow-small: 0 3px 0 rgba(18, 60, 44, 0.08);
  --shadow-large: 0 12px 0 rgba(18, 60, 44, 0.12);
}
```

> Full spec (background, hero, cards, motion, accessibility, responsive rules) lives in this file. Update here when the theme evolves.
