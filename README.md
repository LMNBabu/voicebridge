# VoiceBridge — Real-time Multilingual Voice Meeting Assistant

**Short:** VoiceBridge listens to short audio, converts speech→text (Whisper), translates it, and produces natural speech via Murf TTS.

## Features
- Speech-to-text (OpenAI Whisper)
- Translation (Googletrans)
- TTS with Murf API (mp3 output)
- Simple Flask endpoint: `/process` accepts `audio` file and returns transcript, translation and output filename

## Quick start (local)
1. Clone repo:
```bash
git clone https://github.com/<your-username>/voicebridge.git
cd voicebridge
