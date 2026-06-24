# 🎨 Random Artist Discovery

**Stumble onto art you've never seen.** Spin up a random artist from **45,000+** names across the world's great modern collections, instantly see their work, read a one-line bio, and dive deeper — then take that spark wherever your imagination goes.

### ▶︎ [**Try it live →**](https://ericdataplus.github.io/random-artist-exploration/)

*No sign-up. No install. Press **Space** and start exploring.*

---

## 💡 Why I built it — a muse for AI art

I made this for myself, as a **creative engine for AI art.**

Text-to-image models (Midjourney, DALL·E, Stable Diffusion, Gemini…) are *incredible* at channeling a specific artist's style — but you can only prompt the names you already know, and everyone reaches for the same ten: Van Gogh, Picasso, Monet, repeat. The result is a million identical-looking AI images.

So I built a machine for **discovering artists you've never heard of** — 45,000 of them — and the moment one of their galleries grabs me, I drop their name straight into a prompt. Suddenly you're making art in the voice of a forgotten Czech Art Nouveau illustrator or a Meiji-era woodblock master instead of the same recycled five. **New names → genuinely new-looking art.**

> ### 🖌️ The workflow
> 1. **Discover** a random artist (or filter by era / nationality).
> 2. **Look** — the gallery loads their actual work; the bio tells you who they were.
> 3. **Steal the vibe** — drop their name into your favourite image model:
>    > *"a quiet harbor at dawn, in the style of **Kuwagata Keisai**, ukiyo-e woodblock, soft dawn palette"*
> 4. **"More like this"** to stay in that lane, or spin again for a totally fresh direction.

It turns "I don't know what to make today" into an endless well of starting points.

---

## ✨ What's inside

- 🎲 **45,000+ artists** — merged from the **MoMA** and **The Met** open collections, deduped and cleaned.
- 🖼️ **Instant artwork gallery** — see each artist's real work the moment you land on them.
- 📖 **One-tap context** — a Wikipedia mini-bio + a "Nationality · years" line, so every name means something.
- 🎚️ **Smart filters** — narrow by **nationality**, **era**, or **gender**, with a live count of the pool.
- ✨ **"More like this"** — reroll within the current artist's nationality or era to chase a style you're feeling.
- 🔗 **Shareable links** — every artist gets its own URL (`?artist=…`) + a Share button. Send a friend a painter.
- 🎨 **Artist of the Day** — one featured pick that's the same for everyone, every day.
- 🕑 **History that sticks** — your recent discoveries persist between visits.
- 🌙 **Dark mode** — auto-matches your system, with a manual toggle.
- ⌨️ **Keyboard-fast** — `Space` for the next artist, `Backspace` to go back.
- 📱 **Built for mobile** — collapsible filters, a thumb-friendly bottom bar, zoom-proof controls.

---

## 🛠️ How it works

Pure front-end, zero dependencies, zero backend — it just runs.

- **Vanilla HTML / CSS / JS** in a single `index.html` (no framework, no build step).
- **`artists.json`** — a lean, pre-processed dataset (~45k artists with nationality, gender, and birth/death years) merged from the [MoMA](https://github.com/MuseumofModernArt/collection) and [Met Open Access](https://github.com/metmuseum/openaccess) collections.
- **Wikipedia REST API** for live bios (no key, CORS-friendly).
- Hosted free on **GitHub Pages**.

```
random-artist-exploration/
├── index.html     # the whole app — HTML + CSS + JS
├── artists.json   # 45k artists (name, nationality, gender, born, died)
└── README.md
```

## 🚀 Run it locally

```bash
git clone https://github.com/Ericdataplus/random-artist-exploration.git
cd random-artist-exploration

# serve it (any static server works — needs fetch() of artists.json)
python -m http.server 8000
# then open http://localhost:8000
```

---

## 🙏 Credits

Artist data from the open collections of **The Museum of Modern Art (MoMA)** and **The Metropolitan Museum of Art**. Bios from **Wikipedia**. Built with curiosity — go find an artist nobody's prompting yet. 🎨
