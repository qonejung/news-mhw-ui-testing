# CSS Media — three mobile web UIs in one

Open `css-media-three-ui-comparison.html` directly in a modern browser, or deploy it as a single static web page renamed `index.html` to any static host. **No mobile app or backend needed for the UI review.**

### Use
- Tap the Facebook / X / CSS Media brand at the top of the feed, or the unobtrusive `Switch UI` button, to open the three-option comparison popup.
- Choose Facebook-inspired, X-inspired, or CSS Media news website.
- Experimental condition (Neutral / POLAR_POS / POLAR_NEG) and reading requirement configurations are shared between modes.
- Every mode retains the original highlighting (2 sentences), article quiz, optional 10-second minimum visible time, scroll/visibility logs, simulated reactions, and downloadable JSON logs.
- Switching variant starts a **fresh in-memory reading progress state** in that view. Previously completed article visits remain in each variant's separate browser-local event log. The view selection is remembered on reload.
- The shared article stimulus comes from the uploaded original Immigration Step 2 dataset, three articles per experimental condition. Not yet the Step 3 selection task.
- No user activity data is sent to any server; everything is browser-local. For production research use, session/persistence, consent and server logging need to be designed separately.

### Editing
The combined HTML is self-contained and embeds all three original complete HTML prototypes. To edit news texts or React components, start from the original source projects included below or use the supplied project source. The pages are embedded as Base64 text so the final result can be distributed as **one file** without dependencies. The UI switching shell is plain JavaScript at the end of the combined HTML.

### Notes
The source previews are placeholders (first 35 words from the original article), not validated experimental preview manipulations. Social-media post captions are dummy placeholder text. All three styles are for research discussion and are not official Facebook, X or news publisher products.
