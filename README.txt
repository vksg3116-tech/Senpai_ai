VIVEK AI — ANDROID PWA STARTER

WHAT THIS VERSION DOES
- App-like dark/gold interface
- Study, SAT, IELTS, editing, coding and career quick modes
- Voice input using browser speech recognition where supported
- Spoken replies using browser text-to-speech
- Saves chat history locally in the browser
- Exports chat backup as JSON
- Basic offline app shell after first visit

IMPORTANT LIMITATION
This is a working starter prototype, not yet a connected generative AI assistant. Its replies are built-in demo responses. It does not send your messages to an AI service. A real AI model requires a secure backend and may have usage costs or provider limits. Do not paste private API keys into front-end JavaScript.

INSTALL ON ANDROID
Recommended free route: publish these files to a private GitHub repository and enable GitHub Pages (Pages usually requires a public repository on free personal accounts; check current GitHub plan/settings). Open the HTTPS Pages URL in Chrome on Android, open the three-dot menu, then choose Install app or Add to Home screen. Microphone access requires HTTPS and browser permission.

FILES
- index.html: app interface and demo logic
- manifest.webmanifest: install metadata
- sw.js: offline cache
- icon.svg: app icon

NEXT DEVELOPMENT STEPS
1. Confirm the interface and voice controls work on your Android browser.
2. Add a secure backend (never expose provider API keys in the app).
3. Connect the backend to an AI model, then add real chat, memory controls and study progress.
4. Package as a native Android app only if needed; a PWA is the lowest-cost first step.
