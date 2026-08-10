### Hi 👋

I build **[PersoDub](https://github.com/stronghamjji/PersoDub)** — a desktop app that dubs a video
into another language in the original speaker's own voice, entirely on your Mac.

Most dubbing tools speed the audio up when a translation runs longer than its line, which is the
main reason dubs sound rushed. PersoDub doesn't. It constrains the translation to land inside the
original time slot instead, and a watchdog verifies line by line that no resampling took place.

- 🎙️ &nbsp;Voice cloning, not narration — each speaker's timbre is cloned from the source audio
- 🔒 &nbsp;Runs locally by default — no account, no API key, nothing uploaded
- 🍎 &nbsp;macOS on Apple Silicon today — Windows and Linux planned
- 📄 &nbsp;Apache-2.0

---

**The only official repository is [github.com/stronghamjji/PersoDub](https://github.com/stronghamjji/PersoDub).**

PersoDub ships **no downloadable binary**. It is installed from the command line and built from
source. If you find a copy of this project offering a download link, it is not this project.
