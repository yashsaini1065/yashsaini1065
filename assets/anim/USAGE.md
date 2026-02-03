# Animated Assets Documentation

## File Structure

```
assets/anim/
├── hero_banner_dark.svg      # Dark theme header with waves + particles
├── hero_banner_light.svg     # Light theme variant
├── divider_dark.svg          # Animated section separator (dark)
├── divider_light.svg         # Animated section separator (light)
├── spotlight_arrow.svg       # Bouncing arrow pointing down
├── cta_button.svg            # Glowing "Let's Connect" button
├── skills_marquee.svg        # Scrolling skills ticker
├── project_glow.svg          # Animated frame for project cards
├── footer_wave.svg           # Closing wave animation
├── underline_sweep.svg       # Animated text underline
├── learning_progress.svg     # Animated progress bar
├── spotlight_projects_bg.svg # Floating spotlight background
├── scanline_bg.svg           # Retro scanline effect
├── open_to_work_dot.svg      # Pulsing availability indicator
│
│   🆕 ADVANCED SKILLS ANIMATIONS
├── skill_cards.svg           # Animated skill cards with rotating icons
├── skill_bars.svg            # Animated progress bars with shine effect
├── expertise_hexgrid.svg     # Hexagonal expertise grid with glow
├── tech_orbit.svg            # Orbital tech stack visualization
├── code_typing.svg           # Terminal-style typing animation
├── skills_wave.svg           # Audio wave visualizer with skills
└── radar_skills.svg          # Radar chart skills visualization
```

---

## Embed Snippets for README.md

### 1. Hero Banner (Place at top)

**Dark Theme (GitHub default):**
```html
<div align="center">
  <img src="./assets/anim/hero_banner_dark.svg" alt="Header" width="100%" />
</div>
```

**Light Theme:**
```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/anim/hero_banner_dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/anim/hero_banner_light.svg">
  <img src="./assets/anim/hero_banner_dark.svg" alt="Header" width="100%" />
</picture>
```

---

### 2. Section Divider

**Dark Theme:**
```html
<img src="./assets/anim/divider_dark.svg" alt="divider" width="100%" />
```

**With theme switching:**
```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/anim/divider_dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/anim/divider_light.svg">
  <img src="./assets/anim/divider_dark.svg" alt="divider" width="100%" />
</picture>
```

---

### 3. Spotlight Arrow (Before Projects Section)

```html
<div align="center">
  <img src="./assets/anim/spotlight_arrow.svg" alt="See projects below" width="40" height="50" />
  <br/>
  <strong>Pinned Projects</strong>
</div>
```

---

### 4. CTA Button (Connect Section)

```html
<div align="center">
  <a href="mailto:yashsaini1065@gmail.com">
    <img src="./assets/anim/cta_button.svg" alt="Let's Connect" width="200" height="50" />
  </a>
</div>
```

---

### 5. Skills Marquee

```html
<div align="center">
  <img src="./assets/anim/skills_marquee.svg" alt="Skills" width="100%" />
</div>
```

---

### 6. Project Card Glow (Wrap around project screenshot)

```html
<div align="center" style="position: relative;">
  <img src="./assets/anim/project_glow.svg" alt="Project Frame" width="320" height="180" />
</div>
```

**Usage tip:** Place this around or overlay on your project screenshots for a premium glow effect.

---

### 7. Footer Wave

```html
<img src="./assets/anim/footer_wave.svg" alt="Footer" width="100%" />
```

---

## Bonus Assets

### 8. Underline Sweep (For headings)

```html
<div align="center">
  <h2>My Projects</h2>
  <img src="./assets/anim/underline_sweep.svg" alt="" width="200" height="8" />
</div>
```

---

### 9. Learning Progress Bar

```html
<div align="center">
  <strong>Currently Learning: AWS</strong>
  <br/>
  <img src="./assets/anim/learning_progress.svg" alt="Progress" width="300" height="30" />
</div>
```

---

### 10. Spotlight Projects Background

```html
<div align="center">
  <img src="./assets/anim/spotlight_projects_bg.svg" alt="Background" width="100%" />
</div>
```

---

### 11. Scanline Background

```html
<img src="./assets/anim/scanline_bg.svg" alt="Background" width="100%" />
```

---

### 12. Open to Work Indicator

```html
<img src="./assets/anim/open_to_work_dot.svg" alt="Available" width="24" height="24" /> Open to opportunities!
```

**Inline usage:**
```html
<p>
  <img src="./assets/anim/open_to_work_dot.svg" alt="" width="16" height="16" style="vertical-align: middle;" />
  <strong>Available for hire</strong>
</p>
```

---

## Complete README Example

```markdown
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/anim/hero_banner_dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="./assets/anim/hero_banner_light.svg">
    <img src="./assets/anim/hero_banner_dark.svg" alt="Header" width="100%" />
  </picture>

  # 👋 Hi, I'm Yash Saini

  **Full-Stack Developer | Enterprise Systems | Mobile Apps**

  <img src="./assets/anim/open_to_work_dot.svg" width="16" height="16" /> Open to remote opportunities

</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/anim/divider_dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/anim/divider_light.svg">
  <img src="./assets/anim/divider_dark.svg" alt="" width="100%" />
</picture>

## 🛠️ Tech Stack

<div align="center">
  <img src="./assets/anim/skills_marquee.svg" alt="Skills" width="100%" />
</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/anim/divider_dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/anim/divider_light.svg">
  <img src="./assets/anim/divider_dark.svg" alt="" width="100%" />
</picture>

<div align="center">
  <img src="./assets/anim/spotlight_arrow.svg" alt="" width="40" height="50" />
  <h2>📌 Pinned Projects</h2>
  <img src="./assets/anim/underline_sweep.svg" alt="" width="200" height="8" />
</div>

<!-- Your projects here -->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/anim/divider_dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/anim/divider_light.svg">
  <img src="./assets/anim/divider_dark.svg" alt="" width="100%" />
</picture>

## 📊 Currently Learning

<div align="center">
  <strong>AWS Cloud Services</strong>
  <br/><br/>
  <img src="./assets/anim/learning_progress.svg" alt="Progress" width="300" height="30" />
</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/anim/divider_dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/anim/divider_light.svg">
  <img src="./assets/anim/divider_dark.svg" alt="" width="100%" />
</picture>

## 🤝 Let's Connect

<div align="center">
  <a href="mailto:yashsaini1065@gmail.com">
    <img src="./assets/anim/cta_button.svg" alt="Let's Connect" width="200" height="50" />
  </a>
</div>

<img src="./assets/anim/footer_wave.svg" alt="" width="100%" />
```

---

## SVG Optimization Tips

### 1. Remove Metadata
Remove unnecessary XML metadata, comments, and editor-specific data:
```bash
# Using svgo (Node.js)
npm install -g svgo
svgo input.svg -o output.svg --multipass
```

### 2. Simplify Paths
- Round decimal places to 2 digits
- Remove unnecessary whitespace
- Combine identical gradients

### 3. Minimize Filter Complexity
Reduce `feGaussianBlur` stdDeviation values if animations feel slow.

### 4. SVGO Configuration (optional)
Create `svgo.config.js`:
```javascript
module.exports = {
  plugins: [
    'preset-default',
    'removeDimensions',
    {
      name: 'removeAttrs',
      params: { attrs: '(data-.*)' }
    }
  ]
}
```

---

## GIF Optimization (if needed)

If you convert to GIF for broader compatibility:

### Using ImageMagick
```bash
convert -delay 4 -loop 0 frames/*.png output.gif
```

### Using Gifsicle (compression)
```bash
gifsicle -O3 --colors 64 --lossy=80 input.gif -o optimized.gif
```

### Using FFmpeg
```bash
ffmpeg -i input.mp4 -vf "fps=15,scale=800:-1:flags=lanczos,split[s0][s1];[s0]palettegen[p];[s1][p]paletteuse" -loop 0 output.gif
```

---

## Animation Timing Reference

| Asset | Duration | Loop |
|-------|----------|------|
| hero_banner | 3-4s waves | ∞ |
| divider | 3s pulse | ∞ |
| spotlight_arrow | 1.5s bounce | ∞ |
| cta_button | 2.5s glow sweep | ∞ |
| skills_marquee | 25s scroll | ∞ |
| project_glow | 3-3.5s | ∞ |
| footer_wave | 3-5s | ∞ |
| underline_sweep | 2.5s | ∞ |
| learning_progress | 2s fill (once) | 1 |
| open_to_work_dot | 2s pulse | ∞ |

---

## Browser/Platform Compatibility

| Platform | SMIL Animation | Notes |
|----------|----------------|-------|
| GitHub README | ✅ | Full support |
| Chrome | ✅ | Full support |
| Firefox | ✅ | Full support |
| Safari | ✅ | Full support |
| Edge | ✅ | Full support |

**Note:** GitHub sanitizes JavaScript and CSS animations, but SMIL animations (used in these SVGs) work perfectly.

---

## Color Reference

| Color | Hex | Usage |
|-------|-----|-------|
| Neon Cyan | `#00d4ff` | Primary accent |
| Bright Cyan | `#00ffff` | Highlights |
| Deep Cyan | `#0099cc` | Shadows/depth |
| Dark BG | `#0a0a0f` | Dark theme |
| Card BG | `#1a1a2e` | Card backgrounds |
| Light Cyan | `#0891b2` | Light theme accent |
| Light BG | `#f8fafc` | Light theme |

---

## Customization

To change colors, search and replace in SVG files:
- `#00d4ff` → Your primary color
- `#00ffff` → Your highlight color
- `#0a0a0f` → Your dark background
- `#f8fafc` → Your light background

To change animation speed, modify `dur` attributes in SVG files.

---

## 🆕 Advanced Skills & Expertise Animations

### Skill Cards (Animated icons with glow)

Premium animated cards with rotating React atom, pulsing icons, and gradient effects.

```html
<div align="center">
  <img src="./assets/anim/skill_cards.svg" alt="Skills" width="100%" />
</div>
```

---

### Skill Bars (Animated progress with percentages)

Smooth fill animations with shine sweep effect and staggered loading.

```html
<div align="center">
  <img src="./assets/anim/skill_bars.svg" alt="Skill Levels" width="400" height="300" />
</div>
```

---

### Expertise Hexagon Grid

Honeycomb-style grid showing all expertise areas with color-coded categories.

```html
<div align="center">
  <img src="./assets/anim/expertise_hexgrid.svg" alt="Expertise" width="600" height="300" />
</div>
```

---

### Tech Stack Orbit

Solar system visualization with your initials at center and technologies orbiting.

```html
<div align="center">
  <img src="./assets/anim/tech_orbit.svg" alt="Tech Stack" width="400" height="400" />
</div>
```

---

### Code Typing Animation

Terminal/IDE-style code block with typing cursor and syntax highlighting.

```html
<div align="center">
  <img src="./assets/anim/code_typing.svg" alt="Developer Profile" width="500" height="280" />
</div>
```

---

### Skills Wave Visualizer

Audio-wave style animation with skill names flowing through.

```html
<div align="center">
  <img src="./assets/anim/skills_wave.svg" alt="Skills" width="100%" />
</div>
```

---

### Radar Skills Chart

Interactive-looking radar chart with animated data points and scanning effect.

```html
<div align="center">
  <img src="./assets/anim/radar_skills.svg" alt="Skill Radar" width="400" height="400" />
</div>
```

---

## Premium Skills Section Layout Example

Combine multiple animations for maximum impact:

```markdown
## 💻 Technical Expertise

<div align="center">
  <img src="./assets/anim/underline_sweep.svg" alt="" width="250" height="8" />
</div>

<!-- Option 1: Skill Cards -->
<div align="center">
  <img src="./assets/anim/skill_cards.svg" alt="Core Technologies" width="100%" />
</div>

<br/>

<!-- Option 2: Side-by-side layout -->
<table align="center">
  <tr>
    <td align="center">
      <img src="./assets/anim/skill_bars.svg" alt="Skill Levels" width="400" />
    </td>
    <td align="center">
      <img src="./assets/anim/radar_skills.svg" alt="Skill Radar" width="350" />
    </td>
  </tr>
</table>

<br/>

<!-- Code profile visualization -->
<div align="center">
  <img src="./assets/anim/code_typing.svg" alt="Developer Profile" width="500" />
</div>

<br/>

<!-- Tech orbit for visual flair -->
<div align="center">
  <img src="./assets/anim/tech_orbit.svg" alt="Tech Stack" width="350" />
</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/anim/divider_dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/anim/divider_light.svg">
  <img src="./assets/anim/divider_dark.svg" alt="" width="100%" />
</picture>

## 🎯 Domain Expertise

<div align="center">
  <img src="./assets/anim/expertise_hexgrid.svg" alt="Expertise Areas" width="100%" />
</div>

<!-- Skills wave for dynamic feel -->
<div align="center">
  <img src="./assets/anim/skills_wave.svg" alt="Skills" width="100%" />
</div>
```

---

## Advanced Animation Timing Reference

| Asset | Duration | Animation Type | Loop |
|-------|----------|----------------|------|
| skill_cards | 2-8s | Icon rotation, glow pulse | ∞ |
| skill_bars | 1.5-2.5s | Fill + shine sweep | Fill once, shine ∞ |
| expertise_hexgrid | 3s | Stroke opacity pulse | ∞ |
| tech_orbit | 8-50s | Orbital rotation | ∞ |
| code_typing | 1s | Cursor blink, scanline | ∞ |
| skills_wave | 1.3-1.9s | Wave amplitude | ∞ |
| radar_skills | 2-4s | Data point expansion, scan | Expand once, scan ∞ |

---

## Animation Techniques Used

| Technique | SVGs Using It |
|-----------|---------------|
| SMIL `<animate>` | All |
| `<animateTransform>` rotation | tech_orbit, skill_cards (React icon) |
| Gradient animation | dividers, cta_button, skill_bars |
| Path morphing | hero_banner, footer_wave |
| Staggered timing (`begin`) | skill_bars, radar_skills |
| Filter glow (`feGaussianBlur`) | All skill animations |
| Clip paths | skill_bars shine effect |
| Easing (`calcMode="spline"`) | radar_skills, skill_bars |

---

Created for **Yash Saini** (@yashsaini1065)
