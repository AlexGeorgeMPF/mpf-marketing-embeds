# MPF Marketing Embeds

Self-contained HTML animation files for the MyPathfinder marketing site.
Served via GitHub Pages and embedded in Webflow using iframes.

## Files

| File | Description | Dimensions |
|------|-------------|------------|
| `high-vibe-card.html` | Animated job card with vibe score | 420×auto |
| `vibe-setup.html` | Vibe score setup wizard animation | 440×580 |
| `cv-builder-mobile.html` | CV builder mobile animation | 480×560 |
| `cv-desktop-improve.html` | CV builder desktop "Improve" animation | 900×560 |

## Usage in Webflow

Add an **Embed** element and paste:

```html
<iframe src="https://AlexGeorgeMPF.github.io/mpf-marketing-embeds/vibe-setup.html"
  width="440" height="580" style="border:none;overflow:hidden"
  scrolling="no" loading="lazy"></iframe>
```

Adjust the filename and dimensions for each animation.
