# JARVIS Android Starter — Build 0.1

This is the first runnable prototype: a mobile-friendly web app with a chat window, text input, browser speech recognition, and spoken replies.

## Important current limitation
This is a **local demo**, not a connected AI assistant yet. It only has a few demonstration responses (greeting, date, time, help). The next development stage is to connect a real AI model through a secure backend. Never put a private API key in `index.html` or any JavaScript shipped to the phone.

## Run it on Android
1. Extract this ZIP on your phone.
2. Put the folder in a GitHub repository (you can use GitHub's website or an Android code editor).
3. Enable GitHub Pages for the repository, using the `main` branch and `/ (root)` folder.
4. Open the published HTTPS website in Chrome on Android.
5. Allow microphone access when prompted.
6. In Chrome, open the menu and choose **Add to Home screen** or **Install app** if offered.

Voice recognition depends on browser support, microphone permission, and sometimes an internet connection. Text mode remains available if speech recognition is unsupported.

## Files
- `index.html` — interface, voice input, speech output, and demo replies
- `manifest.json` — installable app metadata
- `sw.js` — basic offline caching

## Next build
Add a backend `/api/chat` endpoint, connect an AI model securely, then add conversation memory and Android integrations with explicit user permissions.
