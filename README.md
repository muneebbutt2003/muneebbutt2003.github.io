# Muneeb Ahmad Butt — Portfolio

Personal portfolio site. Plain HTML, CSS and JavaScript — no build step, no dependencies.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole site (HTML + CSS + JS in one file) |
| `profile.jpg` | Profile photo — replace this with a higher-resolution one |
| `Muneeb-Ahmad-Butt-CV.pdf` | The CV the "Download CV" button links to |

## Put it online with GitHub Pages

1. On GitHub, create a **new public repository** named exactly:

   ```
   muneebbutt2003.github.io
   ```

   The name matters — a repo named `username.github.io` gets published at the root URL,
   so your link is short and clean.

2. Upload all four files (`index.html`, `profile.jpg`, `Muneeb-Ahmad-Butt-CV.pdf`, `README.md`)
   into the **root** of that repo — not inside a folder. Use **Add file → Upload files**,
   then commit.

3. Go to **Settings → Pages**. Under *Build and deployment*, set:
   - Source: **Deploy from a branch**
   - Branch: **main** and folder **/ (root)**, then **Save**.

4. Wait one to two minutes, then open:

   ```
   https://muneebbutt2003.github.io
   ```

   If you get a 404 at first, give it another minute and hard-refresh (Ctrl+Shift+R).

### Using your existing `Portfolio` repo instead

If you'd rather keep it in your current repo, upload the files there and turn on Pages the same
way. Your URL becomes `https://muneebbutt2003.github.io/Portfolio/` — it works fine, it's just
longer.

## Add the link to LinkedIn

1. Open your LinkedIn profile → **Edit intro** (the pencil icon under your name).
2. Scroll to **Website**, click **Add website**.
3. Paste the URL, set the label to **Personal** or **Portfolio**, and save.

Two more places worth putting it:
- **Featured section** on your profile — add it as a link so it shows as a large card with a preview.
- **Contact info → Website**, plus the first line of your About section.

## Before you share it

- [ ] Replace `profile.jpg` with a sharper photo (square, at least 600×600).
- [ ] In `index.html`, find `YOUR-LINKEDIN-USERNAME` and put your real LinkedIn URL there.
- [ ] Make the MedZone repo public and point the "Code on GitHub" link straight at it.
- [ ] Open the site on your phone and check it reads well.

## Editing

Everything lives in `index.html`. Text is in the `<body>`, styling is in the `<style>` block at
the top. The colours are set once as variables at the very top of the CSS:

```css
--ink:#0A1733;   /* dark navy background */
--sky:#38BDF8;   /* cyan accent          */
```

Change those two and the whole site re-themes.
