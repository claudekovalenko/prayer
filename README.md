# Prayer Topics

A small, private prayer list you can open on your phone or laptop. No accounts, no server: everything is saved in your browser.

## What it does

- Keeps a list of your big prayer topics, seeded with the ones you shared.
- Each topic has a short description and a log of **updates and answers** you can add over time, so you can see how God has been leading.
- **Pray through all** walks you one topic at a time, shows recent updates, lets you jot a note, and marks each one prayed.
- Add, edit, reorder, and delete topics.
- **Export / Import** a JSON backup so you can move your list between devices.
- Works offline and can be added to your phone's home screen like an app.

## Running it

Open `index.html` in a browser. That's it.

To use it as a home-screen app (with offline support), serve the folder over HTTP, for example:

```
python3 -m http.server 8080
```

then open http://localhost:8080 and choose "Add to Home Screen" in your phone's browser. GitHub Pages works too: enable Pages for this repository on the branch that has these files.
