# 🌍 OmniVoice — Google Colab + Gradio UI

Run [OmniVoice](https://github.com/k2-fsa/OmniVoice) in your browser — voice cloning, voice design, and 600+ languages. Free, no setup required.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/elkdev72/OmniVoice_Colab/blob/main/OmniVoice_Colab.ipynb)

---

## 🎬 Demo

> Watch the full tutorial on YouTube: **[link to your video]**

---

## ✨ What makes OmniVoice unique

Most TTS models give you a fixed list of voices. OmniVoice gives you three powerful modes:

- **Voice Cloning** — upload any audio clip and clone that exact voice
- **Voice Design** — describe the voice in plain text: `"female, high pitch, british accent"`
- **Auto Voice** — let the model pick a voice automatically

All of this across **646 languages** with inference 40x faster than real-time.

---

## 🚀 Quick Start

1. Click **Open in Colab** above
2. Set runtime to **GPU** (Runtime → Change runtime type → T4 GPU)
3. Run **Cell 1** — installs dependencies
4. Run **Cell 2** — downloads model (~3-5 GB, takes a few minutes first time)
5. Run **Cell 3** — launches the Gradio UI
6. Click the public URL and start generating!

---

## 🎛️ Modes

### Voice Cloning
Upload any clear speech recording — the model clones the voice. Reference transcript is optional; leave it blank and Whisper auto-transcribes it for you.

### Voice Design
Describe the voice with comma-separated attributes:

| Category | Options |
|---|---|
| Gender | `male`, `female` |
| Age | `child`, `young adult`, `middle-aged`, `elderly` |
| Pitch | `very low`, `low`, `moderate`, `high`, `very high` |
| Style | `whisper` |
| English accent | `british`, `american`, `australian`, `indian`, `canadian`, ... |
| Chinese dialect | `四川话`, `陕西话`, ... |

Example: `"female, high pitch, young adult, british accent"`

### Non-verbal tags
Insert anywhere in your text:
`[laughter]` `[sigh]` `[sniff]` `[question-en]` `[surprise-ah]` `[dissatisfaction-hnn]`

---

## ⚙️ Generation controls

| Parameter | What it does |
|---|---|
| Diffusion steps | More steps = better quality but slower. Use 16 for drafts, 32 for final output |
| Speed | `< 1.0` slower, `> 1.0` faster |

---

## 🙏 Credits

- [OmniVoice](https://github.com/k2-fsa/OmniVoice) by k2-fsa
- [Gradio](https://gradio.app) for the UI
- Notebook by **[elkdev72](https://github.com/elkdev72)**

---

## 📄 License

This notebook is MIT licensed. OmniVoice is Apache-2.0 — see the [original repo](https://github.com/k2-fsa/OmniVoice) for details.
