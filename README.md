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

Model-specific configurations for:
- 🧠 Qwen 3 (3B to 235B)
- 🧠 DeepSeek-MoE
- 🧠 Mistral, Mixtral, and others

Presets include:
- Thought tag formatting (`<think>...</think>`)![Ports_00061_](https://github.com/user-attachments/assets/4e15ae43-e39c-4c5c-a7c9-0f06199233b6)

- Grounded system prompts with no padding or AI overreach
- Roleplay-safe post-history instructions

---

## ⚖️ License

This repository is released under [The Unlicense](https://unlicense.org/), meaning:

> You can do whatever you want with this code and content—no conditions, no attribution required.

For details, see the [LICENSE](./LICENSE) file.

---

## 🤝 Contributions

Feel free to fork, modify, and send pull requests. More narrator archetypes, preset profiles, and theme variations welcome.
