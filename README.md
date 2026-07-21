# BSOD's Character Codex v3.5
## The Ultimate Browser-Based Prompt Builder for Stable Diffusion

**No installation. No dependencies. Just open the HTML file and start building.**

---

### What is it?

BSOD's Character Codex is a single-file HTML application designed specifically for Stable Diffusion prompt engineering. It combines a massive character database with intelligent scene building tools, model-specific presets, and a distraction-free interface that stays out of your way while you work.

Think of it as your personal prompt assistant—searchable, customizable, and completely offline.

---

### What's New in v3.5

**18 Color Themes** — From Midnight Cyan to Toxic Green to Royal Gold. Each theme features animated lava backgrounds with glowing blobs.

**NSFW Scene Builder** — Toggleable mature content section with 180+ tags for 18+ artwork generation. Off by default, one-click enable.

**Enhanced Visual Effects** — Animated glows, floating tags, shimmer backgrounds, and smooth transitions throughout.

**5 Audio Tracks** — Ambient, Piano, Lofi, Guitar, and Synth background music with volume control.

**Improved Tag Search** — Search across all categories or filter by specific sections. Auto-expands matching categories.

**Character Import** — Import custom characters via TXT or CSV files. Supports Danbooru-style tag formats.

---

### Core Features

**📚 244,932+ Character Database**
Instantly search anime, game, and manga characters. Each entry includes properly formatted Danbooru-style tags (1girl, hair color, outfit details, etc.) that you can add to your prompt with a single click. Sorted by popularity so the most relevant results surface first.

**🎨 Scene Builder (700+ Tags)**
Eight categorized tag pools with one-click randomization:
- **Expressions** (60+) — smiles, embarrassed, angry, etc.
- **Clothing** (100+) — dresses, uniforms, armor, casual
- **Actions** (80+) — poses, activities, gestures
- **Locations** (100+) — indoors, outdoors, fantasy settings
- **Lighting** (75+) — golden hour, dramatic, soft, etc.
- **Composition** (65+) — camera angles, framing
- **Objects** (100+) — weapons, props, accessories
- **NSFW/Mature** (180+) — 18+ content (toggleable)

Hit the 🎲 button to randomize any category—or all at once for instant inspiration.

**⚙️ Model Presets**
One-click quality tag sets for specific models:
- **Pony** — Optimized for Pony Diffusion
- **Illustrious** — For Illustrious checkpoints
- **Anima** — Animagine XL specialized
- **SDXL** & **SD1.5** — Standard quality tags

**🖼️ 30 Art Style Presets**
From Realistic to Vaporwave, Cyberpunk to Ukiyo-e, Art Nouveau to Film Noir. Each applies appropriate positive tags and contradictory negatives so your style stays consistent.

**📝 Multi-Syntax Support**
Switch between A1111, NovelAI, Compel/ComfyUI, Plain text, or Krea 2 natural language. Your prompts format automatically.

**🎨 18 Color Themes**
- Midnight (default cyan/dark)
- Synthwave (purple/pink)
- Terminal (green/black)
- Ember (orange/dark)
- Paper (light mode)
- Forest (green)
- Ocean (blue)
- Rose (pink)
- Solar (sepia light)
- Mono (grayscale)
- Crimson (red/dark)
- Frost (light blue)
- Nord (arctic blue)
- Sakura (pink light)
- Toxic (neon green)
- Royal (gold/purple)
- Abyss (teal/black)
- Candy (pastel blue)

---

### Why Use This?

**Zero Setup** — It's one HTML file. Double-click it. Done.

**Works Offline** — No internet connection required after the first download. Your prompts never leave your machine.

**CLIP Token Counter** — Built-in estimation so you know when you're approaching the 77 token limit.

**Drag & Drop Reordering** — Prioritize tags by dragging them in the prompt boxes.

**Import Your Own Characters** — Drop a TXT or CSV file with your custom tags. They'll appear at the top of search results.

**Preset System** — Save your favorite prompt combinations. Export them as JSON to share or backup.

**History** — Last 20 copied prompts saved automatically. Click to restore.

**Notepad** — Jot down ideas while you build. Auto-saves to browser storage.

**Background Music** — Optional ambient, piano, lofi, guitar, or synth tracks while you work.

---

### Quick Start

1. **Download** the HTML file
2. **Open** in any modern browser (Chrome, Firefox, Edge, Safari)
3. **Search** a character (e.g., "miku", "touhou")
4. **Click** a result to add tags to Positive prompt
5. **Add** model preset (Pony/SDXL/etc) and art style
6. **Build** your scene with the tag categories or hit 🎲 to randomize
7. **Copy** and paste into your SD frontend

---

### Pro Tips

- **Quick Add**: If your search doesn't match a character, hit Enter to add it as a custom tag instantly
- **Series Browsing**: Click any purple series badge to filter all characters from that franchise
- **Weight Adjustment**: Click the weight indicator on any tag to adjust emphasis
- **Token Management**: Watch the counter—CLIP has a 77 token limit per prompt
- **Syntax Switching**: Change formats mid-workflow without rewriting anything
- **Collapse Sections**: Use the ▾ toggle to hide categories you don't need
- **NSFW Toggle**: Click the NSFW button in Scene Builder to reveal mature tags

---

### Importing Custom Characters

**TXT Format:**

Name: tag1, tag2, tag3
Name (Series): tag1, tag2

**CSV Format:**
Header: `character,copyright,core_tags`

Click "Import Characters" → Choose file(s). Imported characters appear at top of search results with an amber indicator.

---

### Technical Details

- **Pure HTML/CSS/JS** — No external dependencies except Google Fonts
- **LocalStorage** — Presets, history, and notepad save to your browser
- **Web Audio API** — For optional background music
- **CSS Grid/Flexbox** — Responsive layout system
- **CSS Variables** — Dynamic theming with animated backgrounds
- **File Size** — ~260KB including the entire character database

---

### Browser Compatibility

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Opera 76+

Requires ES6+ support and CSS Grid.

---

### Screenshots

*[Interface showing the three-column layout: Character search on left, prompt panels in center, scene builder on right. Dark theme with cyan accents and animated lava background.]*

*[Scene builder showing the tag categories with the randomize button and NSFW toggle.]*

*[The prompt output showing formatted tags ready to copy with token count.]*

---

### Download

**Version:** 3.5  
**File:** `BSOD_sCharacterCodexV3_5.html`  
**Size:** ~260KB

---

### Changelog

**v3.5**
- Added 8 new themes (Crimson, Frost, Nord, Sakura, Toxic, Royal, Abyss, Candy) — 18 total
- Added NSFW/Mature scene builder section with 180+ tags (toggleable)
- Enhanced glow effects and animations throughout UI
- Added Guitar and Synth background music tracks (5 total)
- Improved tag search with category filtering
- Added 100+ new object/prop tags
- Performance optimizations for large databases

**v3.4**
- Added 10 themes with animated lava backgrounds
- Added Piano and Lofi music tracks
- Enhanced visual effects and transitions

**v3.0-3.3**
- Initial release with character database
- Scene builder with 6 categories
- Model and style presets
- Import/export functionality

---

### Credits

Made with help from Claude and v0 by Vercel.
https://huggingface.co/datasets/Laxhar/noob-wiki
