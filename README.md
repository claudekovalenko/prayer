# Prayer Topics

A small, private prayer list you can open on your phone or laptop. No accounts, no server: everything is saved in your browser.

## What it does

- Keeps a list of your big prayer topics, seeded with the ones you shared.
- Each topic has a short description and a log of **updates and answers** you can add over time, so you can see how God has been leading.
- **Pray through all** walks you one topic at a time, shows recent updates, lets you jot a note, and marks each one prayed.
- **The Lord's Prayer** is a second guided walk: the six movements of Matthew 6:9-13, each with prompts for what that line opens up, and room to write as you go.
- **History** shows a month calendar shaded by how many topics you prayed each day, with a dot on the days you prayed the Lord's Prayer. Tap any day to see what you prayed for, when, and anything you wrote.
- Add, edit, reorder, and delete topics.
- **Export / Import** a JSON backup so you can move your list between devices.
- Works offline and can be added to your phone's home screen like an app.

## Install it on your phone

The app is deployed to GitHub Pages on every push (see `.github/workflows/pages.yml`):

**https://claudekovalenko.github.io/prayer/**

- **iPhone (Safari):** open the link, tap the Share button, then **Add to Home Screen**.
- **Android (Chrome):** open the link, tap the ⋮ menu, then **Install app** or **Add to Home screen**.

Once installed it opens full-screen like a native app and works offline. Your data stays in that app's storage on your phone.

## Running it locally

Open `index.html` in a browser, or serve the folder to get the offline service worker too:

```
python3 -m http.server 8080
```
