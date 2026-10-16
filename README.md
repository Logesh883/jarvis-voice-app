# Jarvis Voice: website and downloads

The Jarvis Voice website (`index.html`) and the app's releases. Talk to Claude Code on your Mac; hear when it's done.

**Download:** [Apple silicon](https://github.com/Logesh883/jarvis-voice-app/releases/latest/download/Jarvis-arm64.dmg) · [Intel](https://github.com/Logesh883/jarvis-voice-app/releases/latest/download/Jarvis-x86_64.dmg) · [all versions](https://github.com/Logesh883/jarvis-voice-app/releases)

No source code lives here. Releases are built and published by the app's own (private) repository: pushing a version tag there builds both disk images and creates the release here. The Download buttons on the site point at `releases/latest/download/…`, so they always serve the newest version.

`.github/workflows/pages.yml` publishes the site with GitHub Pages on every push to `main`.
