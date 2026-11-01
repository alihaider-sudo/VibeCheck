# VibeCheck

Build with AI. Think like a developer.

A five-page educational website about responsible AI-assisted web development, built with plain HTML, CSS, and a little JavaScript. No frameworks, no build step, no backend.

## Run it on your computer

1. Unzip the folder.
2. Double-click `index.html` to open it in your browser.
   (Or in VS Code: right-click `index.html` and choose "Open with Live Server".)
3. Stay online the first time so the Google Fonts can load.

## Folder structure

```
vibecheck/
├── index.html        Home
├── explore.html      Explore (category filter uses js/main.js)
├── lab.html          VibeCheck Lab (Spot the Mistake quiz uses js/main.js)
├── guides.html       Guides
├── about.html        About (demonstration contact form)
├── articles/         8 article pages
├── css/style.css     The one shared stylesheet
├── js/main.js        Filter, quiz, and demo form
└── images/           12 SVG illustrations + favicon.svg
```

## Publish it for free

Keep `index.html` at the top level of the folder you upload. All links are relative, so the site works on any host without changes.

### Option A: Netlify Drop (fastest, no account setup needed to try)
1. Go to https://app.netlify.com/drop
2. Drag the whole `vibecheck` folder onto the page.
3. Netlify gives you a public link. Create a free account to keep it permanently.

### Option B: GitHub Pages
1. Create a free GitHub account and a new public repository named `vibecheck`.
2. Upload all files and folders, keeping the structure above.
3. Go to Settings, then Pages. Under "Build and deployment", choose "Deploy from a branch", branch `main`, folder `/ (root)`, and save.
4. After a minute, your site is live at `https://YOUR-USERNAME.github.io/vibecheck/`.

## Notes

- The contact form is a demonstration. It does not send messages, and says so on screen.
- The Explore filter and the Lab quiz need JavaScript. Without it, all articles still show and the pages still read correctly.
