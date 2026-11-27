# voice-labs-prompt

# Voice Labs Prompt

Build your own **100% client-side, serverless ElevenLabs TTS & Speech-to-Text Studio** in seconds using **Gemini Canvas** (or any AI coding assistant) — with zero hardcoded keys (BYOK).

### ✨ What It Builds
- **ElevenLabs v4 Turbo / v4 / v3 TTS** — live credit/quota tracking, account voice loader, custom tone presets, Web Audio waveform visualizer.
- **Auto-Emotion Tagging (Enhance)** — injects ElevenLabs `[excited]`, `[whispering]`, `[sighing]`, `[pause]` audio tags without altering your words (free local NLP engine + optional Gemini/OpenAI LLM).
- **Persistent Segment Cache (`IndexedDB`) + Seamless MP3 Stitcher** — caches recurring video intros, outros, and CTAs locally for **0 credits** and stitches them frame-accurately with newly voiced sections into one clean `.mp3`.
- **ElevenLabs Scribe v3 / v2 Speech-to-Text** — drag-and-drop audio/video upload, live browser mic recording, speaker diarization, clickable timeline, `.SRT` / `.VTT` / `.TXT` / `.JSON` export, and one-click send to TTS editor.

### 🚀 Quick Start (Gemini Canvas)
1. Open [Gemini](https://gemini.google.com) and turn on the **Canvas** toggle below the input box.
2. Open one of the prompt files below and copy everything under the start line:
   - 🇬🇧 English: [`voice-labs-prompt-en.txt`](./voice-labs-prompt-en.txt)
   - 🇹🇷 Türkçe: [`voice-labs-prompt-tr.txt`](./voice-labs-prompt-tr.txt)
3. Paste into Gemini and send, then switch to the **Preview** tab in Canvas.
4. Click **Export .HTML** inside the app if you want to save and run it locally anytime.

---

### 🇹🇷 Hızlı Kullanım (Türkçe)
1. [Gemini](https://gemini.google.com) ekranında yazma kutusunun altındaki **Canvas** seçeneğini aç.
2. [`voice-labs-prompt-tr.txt`](./voice-labs-prompt-tr.txt) içindeki promptu kopyalayıp gönder.
3. Sağdaki panelden **Önizleme (Preview)** sekmesine geç — stüdyo doğrudan tarayıcı içinde çalışır. Kendi ElevenLabs API anahtarını girip kullanmaya başlayabilirsin (anahtar yalnızca kendi tarayıcında saklanır).

## License
MIT
