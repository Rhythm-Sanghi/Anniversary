# Anniversary Retro Hindi Radio

A single-page skeuomorphic retro Hindi radio web app built for Sumit & Neeta's 21st wedding anniversary. It simulates a June 28, 2005 FM radio station hosted by an AI RJ named DJ Vikram.

## Features
- **Skeuomorphic Retro Indian Radio UI**: Complete with wood cabinet cabinet casing, glowing amber dial scale, a moving tuning needle, pulsing speaker drivers, and an LED marquee.
- **Procedural Web Audio Sound Effects**: Generates realistic radio static hiss, oscillator tuning sweeps, and chord stabs entirely in-browser.
- **Embedded YouTube Player**: Stream 2005 Bollywood hits with automatic volume ducking when the RJ speaks, and automatic skip handling for geo-blocked songs.
- **AI RJ Vikram Dialogue**: Uses Google Gemini 2.5 Flash API with personalized context (Indore references, family jokes).
- **Voice Synthesis & Fallback**: Integrates ElevenLabs TTS for realistic speech, with a built-in browser SpeechSynthesis voice fallback.
- **Call-In Feature**: Supports Hindi Web Speech API recognition for voice dedications and interactive mood changes.

## Running Locally
Since YouTube embedding requires a valid web origin, the app **cannot be run directly via `file://`** (by double-clicking the HTML file). You must run it through a local HTTP server:

```bash
# Python
python -m http.server 8000

# Node.js
npx serve
```
Then open `http://localhost:8000` or the node port in your browser.
