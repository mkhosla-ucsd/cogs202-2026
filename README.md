# COGS 202 — Spring 2026 Course Website

This is a simple static website for **COGS 202: Computational Modeling of Cognition**.

## Files

- `index.html` — main course website
- `styles.css` — styling
- `script.js` — small footer script
- `.nojekyll` — prevents GitHub Pages from trying to process the site with Jekyll

## Edit locally

You can open `index.html` directly in your browser, or run a simple local server:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Deploy on GitHub Pages

### Option 1: easiest route

1. Create a GitHub repository.
2. Upload these files to the repository root.
3. On GitHub, go to **Settings → Pages**.
4. Under **Build and deployment**, set:
   - **Source** = `Deploy from a branch`
   - **Branch** = `main`
   - **Folder** = `/ (root)`
5. Save.

Your site will appear at:

```text
https://YOUR-USERNAME.github.io/REPOSITORY-NAME/
```

If the repository is named `YOUR-USERNAME.github.io`, then it will appear at:

```text
https://YOUR-USERNAME.github.io/
```

## Suggested customizations

- Add lecture slides week by week in the schedule table.
- Replace the presentation sign-up placeholder with your new sheet link.
- Update guest lecture links if they change.
- Add Canvas / syllabus / office-hours links if you want a quick-links section.
