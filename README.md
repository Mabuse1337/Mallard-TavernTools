# 🦆 Mallard-TavernTools

A curated collection of storytelling resources for use with [SillyTavern](https://github.com/SillyTavern/SillyTavern), focused on immersive roleplay and AI-assisted narrative control.

This repo includes:

- 🎭 **Character Cards** — Flexible narrator and NPC templates with deeply customized system prompts.
- 🎨 **Themes** — Aesthetic configurations for SillyTavern UI with optional enhancements via the Moonlit Echoes extension.
- 🧠 **Text Generation Presets** — Model-aligned `system_prompt` and `post_history_instructions` configurations for best-in-class performance across supported LLMs.

---

## 📁 Contents

### `characters/`

Narrator and role-specific cards designed for tight narrative control. Cards include:
- Embedded JSON config
- Proper `first_mes`, `personality`, and `scenario` fields
- Full support for custom instructions (e.g., Past vs Present tense narrators)

---

### `themes/`

Monochrome noir, arcanist-inspired, and other atmospheric themes.  
Each theme includes:
- A `CurrentSettings.json` file for core UI styling
- A `[Moonlit]`-prefixed companion file for visual enhancements using the fantastic:

> 🌙 [Moonlit Echoes Theme Extension](https://github.com/RivelleDays/SillyTavern-MoonlitEchoesTheme)

Loading both files (main and Moonlit) provides rich visuals like custom blur, shadow styling, and refined accent colors. Strongly recommended.

---

### `presets/`

Custom configurations for use with a variety of language models in SillyTavern.

Presets include:

- Support for structured thought formatting using `<think>...</think>` tags (where appropriate)  
- Grounded system prompts designed to prevent padding, rambling, or overreach  
- Post-history instructions optimized for immersive and controlled roleplay behavior  

These presets are designed to adapt across multiple models and will be expanded over time.

---

## ⚖️ License

This repository is released under [The Unlicense](https://unlicense.org/), meaning:

> You can do whatever you want with this code and content—no conditions, no attribution required.

For details, see the [LICENSE](./LICENSE) file.

---

## 🤝 Contributions

Feel free to fork, modify, and send pull requests. More narrator archetypes, preset profiles, and theme variations welcome.
