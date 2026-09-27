# Clippy 2.0 📎🧠

The classic **Microsoft Office Assistant**, reborn with a **real brain** — and a **General Assistant** mode. Same authentic Clippy sprite and animations as the original project, now able to actually answer you when you bring your own AI key. Still **free. Never for sale.**

> Want the pure, AI-free classic? See the separate **Clippy** project.

## What it does
- 🎭 **The real Clippy** — genuine Office Assistant sprite + **43 animations**, plus 9 other assistants (Merlin, Rover, Genius, Links, Bonzi, F1, Genie, Peedy, Rocky).
- 🧠 **Real AI, bring-your-own-key** — plug in your own **Anthropic (Claude)**, **OpenAI**, or **local Ollama** engine and chat for real.
- 🎚️ **Two personalities, one toggle:**
  - **Clippy** — in character, playful, the classic charm (with the "It looks like you're…" winks).
  - **General Assistant** — a straight, helpful, general-purpose assistant that just answers clearly.
- 💬 **Works with no key, too** — Clippy mode falls back to his classic scripted lines out of the box; add a key to unlock the brain.
- 🪟 **Windows-9x styling** — beveled windows, gradient title bars, draggable panels, and the "Show Everything" animation gallery.

## Run it
Open **`Clippy-2.0.html`** in any modern browser (Chrome, Edge, Firefox). No install, no build step.

To enable AI: click the gear ⚙ (**Setup**) → pick an **Engine** → paste your **API key** (or point at a local Ollama) → choose a **Personality** → **Save**.

## Privacy
Your API key is **bring-your-own**, stored **only in your browser's local storage**, and sent **directly** to the engine you choose (Anthropic / OpenAI / your local Ollama) — never to the author or any third party. There is no backend and no analytics.

> Note: the Anthropic option uses the `anthropic-dangerous-direct-browser-access` header to call the API straight from the browser. Any script running in your browser could read a key used that way, so use a key you're comfortable using client-side (or use local Ollama, which needs no key).

## Credits
- [clippy.js](https://github.com/smore-inc/clippy.js) by smore-inc (MIT) — serves the authentic Office Assistant sprites & animations.
- Clippy / the Office Assistant characters © **Microsoft Corporation**; Clippy designed by Kevan Atteberry.

## License & non-commercial use
- The **original code** in this repo is licensed under the **PolyForm Noncommercial License 1.0.0** — free for any non-commercial purpose, **no selling**. See [`LICENSE`](LICENSE).
- The Clippy characters/assets are **Microsoft's**, are **not** included in this repo, and are **not** covered by that license. See [`NOTICE.md`](NOTICE.md).

**This is a free, non-commercial fan project, not affiliated with Microsoft.**
