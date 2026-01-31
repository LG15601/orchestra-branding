# 🎨 Orchestra Intelligence — Visual Moodboard

## Aesthetic Direction: "Premium Tech Minimalism"

**Inspirations**: Stripe, Linear, Vercel, Loom, Notion

---

## 🖼️ Visual References

### Website Inspiration

| Brand | What to Take |
|-------|--------------|
| **Stripe** | Gradient backgrounds, premium feel, whitespace |
| **Linear** | Dark mode elegance, purple accents, smooth animations |
| **Vercel** | Bold typography, minimal UI, confidence |
| **Loom** | Friendly but professional, video-first |
| **Notion** | Clean simplicity, smart use of illustrations |

### Color Mood

```
Primary Palette:
┌─────────────────────────────────────────────────┐
│  Deep Navy     Orchestra Purple   Electric Violet│
│  #0F172A       #6B21A8            #8B5CF6        │
│  ████████      ████████           ████████       │
└─────────────────────────────────────────────────┘

Accent:
┌─────────────────────────────────────────────────┐
│  Gold Accent   Soft Purple        Pure White    │
│  #F59E0B       #C4B5FD           #FFFFFF        │
│  ████████      ████████           ████████       │
└─────────────────────────────────────────────────┘
```

### Gradient Directions

1. **Hero Gradient**: Navy → Purple (diagonal, subtle)
2. **Card Gradient**: Transparent → Soft Purple (hover state)
3. **CTA Gradient**: Purple → Electric Violet (horizontal)
4. **Background Mesh**: Abstract purple/navy mesh (very subtle)

---

## 🔤 Typography Samples

### Display Headlines (Space Grotesk Bold)

```
Orchestrez
l'intelligence
de votre business.
```

### Body Copy (Inter Regular)

```
Nous créons des SaaS sur-mesure enrichis par l'IA.
De la vision au produit en 90 jours.
Stack moderne, architecture scalable, agents intégrés.
```

### UI Elements (Inter Medium)

```
[Découvrir nos services]  [Discutons de votre projet]
```

---

## 🎬 Motion Design

### Principles

1. **Subtle, Not Flashy** — Animations servent l'UX, pas l'ego
2. **Ease-Out Curves** — Tout se termine en douceur
3. **Purposeful Delays** — Stagger effects pour guider l'œil
4. **60fps Minimum** — Smooth AF

### Specific Animations

| Element | Animation | Duration |
|---------|-----------|----------|
| Page Load | Fade up + blur | 600ms |
| Hero Text | Stagger reveal | 800ms |
| Cards | Scale + fade on scroll | 400ms |
| Buttons | Scale 1.02 + glow on hover | 200ms |
| Logo | Subtle pulse on load | 1000ms |
| Background | Slow gradient shift | 10000ms |

### Micro-interactions

- **Buttons**: Slight scale up + purple glow
- **Links**: Underline slides in from left
- **Cards**: Lift + shadow on hover
- **Form inputs**: Purple border on focus
- **Toggles**: Smooth slide + color change

---

## 📐 Layout Grid

### Desktop (1440px)

```
┌────────────────────────────────────────────────────────────┐
│    80px    │         1280px content          │    80px    │
│   margin   │     12-column grid (32px gap)   │   margin   │
└────────────────────────────────────────────────────────────┘
```

### Mobile (375px)

```
┌──────────────────────────────┐
│  20px │  335px content │ 20px│
│ margin│   4-column grid │margin│
└──────────────────────────────┘
```

### Section Spacing

- Between sections: 120px (desktop) / 80px (mobile)
- Between elements: 32px / 24px
- Paragraph spacing: 24px / 16px

---

## 🖼️ Imagery Style

### Photography

- **Style**: Minimal, abstract, tech-forward
- **Colors**: Desaturated with purple/blue tints
- **Subjects**: Abstract patterns, light trails, geometric shapes
- **Avoid**: Stock photos of people shaking hands, generic office

### Illustrations

- **Style**: Geometric, line-based, minimal
- **Colors**: Monochrome with purple accents
- **Use for**: Process diagrams, feature explanations
- **Avoid**: Cartoonish, too playful

### Icons

- **Style**: Stroke-based, 1.5px weight
- **Size**: 24px base
- **Library**: Lucide or Phosphor icons
- **Color**: Slate 600 default, Purple on hover

---

## 🎭 UI Components

### Buttons

```css
/* Primary */
background: linear-gradient(135deg, #6B21A8, #8B5CF6);
color: white;
border-radius: 8px;
padding: 12px 24px;
font-weight: 500;

/* Secondary */
background: transparent;
border: 1px solid #475569;
color: white;

/* Ghost */
background: transparent;
color: #8B5CF6;
```

### Cards

```css
background: rgba(15, 23, 42, 0.5);
border: 1px solid rgba(139, 92, 246, 0.2);
border-radius: 16px;
backdrop-filter: blur(10px);
```

### Inputs

```css
background: #0F172A;
border: 1px solid #334155;
border-radius: 8px;
color: white;

/* Focus */
border-color: #8B5CF6;
box-shadow: 0 0 0 3px rgba(139, 92, 246, 0.2);
```

---

## 📱 Responsive Breakpoints

| Name | Width | Notes |
|------|-------|-------|
| Mobile | 0-639px | Stack everything, full-width CTAs |
| Tablet | 640-1023px | 2-column layouts |
| Desktop | 1024-1439px | Full layouts |
| Wide | 1440px+ | Max-width containers |

---

## 🎼 Brand Personality in Design

| Trait | Visual Expression |
|-------|-------------------|
| **Visionary** | Gradients pointing forward, upward motion |
| **Expert** | Clean typography, precise spacing |
| **Premium** | Generous whitespace, subtle details |
| **Innovative** | Unique interactions, unexpected delights |
| **Confident** | Bold headlines, strong contrast |

---

## ✅ Design Checklist

### Every Page Must Have:
- [ ] Consistent header/nav
- [ ] Clear visual hierarchy
- [ ] One primary CTA above fold
- [ ] Proper contrast (WCAG AA)
- [ ] Mobile-responsive layout
- [ ] Loading states for interactions
- [ ] Footer with key links

### Every Component Must:
- [ ] Have hover/focus states
- [ ] Use brand colors only
- [ ] Follow spacing system
- [ ] Be accessible (keyboard nav, ARIA)
- [ ] Animate smoothly

---

*Ce moodboard guide toutes les décisions design. Référez-y avant chaque création.*
