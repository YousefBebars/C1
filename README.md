# Masar C1 Studio — Personal B1–B2 → C1 English Mastery PWA (عربي / EN)

A complete, installable Progressive Web App (PWA) for intermediate-to-advanced English learners (native Arabic support), featuring:
- **☀️ Daily 30-Min Plan & Streak Tracker**
- **🗂️ 5-Box Leitner Spaced Repetition Flashcards** (100 B2–C1 words & phrasal verbs + custom cards + touch swipe gestures)
- **📖 Interactive Graded Reading** (10 B2–C1 articles, tap **any word** for instant Arabic translation & English definition, full paragraph Arabic translation toggle, and 5 comprehension questions per article)
- **🎬 Video & Audio Studio + 🎧 Focus Music Synthesizer** (4 animated C1 video lessons, custom `.mp4`/`.mp3` player, Web Audio Lo-Fi / Rain / Focus sounds, and Web Speech API Shadowing with word-by-word accuracy diff)
- **⚡ Grammar Drills** (30 questions across 5 weak spots with Arabic contrast notes)
- **✍️ C1 Writing Studio** (10 prompts, live word & C1 connector counter, self-review checklist, and AI feedback)
- **✨ 3-Tier Hybrid AI Mode (Works Out of the Box!)**:
  1. **Free Keyless Cloud AI** (`Pollinations AI` over HTTPS) — works automatically when hosted on GitHub Pages and installed on your phone or tablet without needing any API key!
  2. **Optional Custom API Key** (Google Gemini `gemini-2.5-flash` or OpenAI `gpt-4o-mini` in Settings).
  3. **Built-in Offline Smart AI Engine** — works 100% offline when your phone or tablet has no internet connection.

---

## 🚀 How to Deploy on GitHub Pages & Install as a Phone/Tablet App (60 Seconds)

1. Create a new public repository on [GitHub](https://github.com/new) (for example, `masar-c1-english`).
2. Upload the 4 files from this package to the root of your repository:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon.svg`
3. In your GitHub repository, go to **Settings → Pages** (on the left sidebar).
4. Under **Build and deployment → Branch**, select **`main`** (and `/ (root)`), then click **Save**.
5. Wait ~30 seconds, then open your live app URL on your phone or tablet:
   `https://<your-github-username>.github.io/<repo-name>/`
6. **Install on Your Device**:
   - **Android (Chrome)**: Tap the **Install Masar C1** banner or tap **📲 Phone & Tablet App → Install App Now** (or Chrome menu `⋮` → **Install app**).
   - **iPhone / iPad (Safari)**: Tap the **Share** icon (`⬆️`) at the bottom → **Add to Home Screen**.
