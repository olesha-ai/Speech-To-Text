# SpeechToText

Local speech-to-text for **Windows**, **CPU only** — no cloud, no GPU required.

**Binary demo only. Source code is not published.**

## Download

The full package is too large for normal repo uploads. Get **`SpeechToText.zip`** from **[Releases](https://github.com/olesha-ai/Speech-To-Text-speech-to-text-demo/releases)** (latest release).

## Quick start

1. Unzip `SpeechToText.zip` anywhere on disk.
2. Run `SpeechToText.exe`.
3. Keep this layout intact:
   - `libs\` — runtime DLLs
   - `model\speech\` — ASR model (Parakeet TDT 0.6B v3 int8)

## Use

| Mode | What to do |
|------|------------|
| **File** | Open audio (wav, mp3, m4a, flac, ogg, …) → **Transcribe** → **Save** if you want a `.txt` file |
| **Mic** | Choose microphone → level meter (VU) → **Record** → speak, **pause** → text appears |

Language: **auto-detect** (Parakeet multilingual). UI is in English.

## Licenses

Third-party notices are inside the zip in `licenses\`.

Before you redistribute or charge money for a bundle:

- Read `licenses\nemo-parakeet-NOTICE.txt` (model, CC-BY-4.0)
- Read `licenses\samples-NOTICE.txt` (demo audio)

This README is not legal advice.

## What this is not

Not live TV subtitles. Not multi-speaker meeting transcription. One person at a desk, pause-based chunks — dictation-style.

---

*olesha-ai*
