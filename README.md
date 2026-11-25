# Gorge TTS Arabic

Free Arabic narration with `edge-tts` neural voices. No API key. The script caches by
text/voice/rate/pitch, trims silence, and writes 48 kHz mono WAV durations.

Kokoro (used by Lemo) is high quality but has no reliable Arabic voice, so this skill
keeps Edge as the Arabic provider and documents Lemo's TTS source notes for reference.

Use: `python3 scripts/tts_edge.py --storyboard storyboard.json --outdir build/tts --rate -6% --pitch +2Hz`.
