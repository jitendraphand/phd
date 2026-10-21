# PhD Thesis Narration Player

Self-contained HTML page that narrates the PhD thesis summary on Scientometrics and Information Literacy using the browser's Web Speech API.

## Features
- Play / Pause / Stop buttons
- Forward / Reverse (~10s approximate jumps)
- Real-time word highlighting synchronized to speech
- Voice selection (prefers soft female English voices when available)
- Fully client-side, no external dependencies or audio files needed

## GitHub Pages Deployment

1. Go to the repository **Settings** → **Pages**
2. Under **Build and deployment** → **Source**, select **Deploy from a branch**
3. Choose **main** branch and **/ (root)** folder
4. Click **Save**
5. After a minute or two, the site will be live at:

   **https://jitendraphand.github.io/phd/**

Open the URL, select a soft female voice from the dropdown (if available), and press Play. The text will highlight the exact word being pronounced.

## Notes
- Requires a modern browser with Web Speech API support (Chrome, Edge, Safari, Firefox with limitations).
- Voice quality and availability depend on the user's operating system and browser.
- The original document text is embedded directly in the HTML.
