# Aditya Singh - Portfolio

A single-file portfolio (index.html). No install or build step needed.

## Open in VS Code
1. Unzip this folder, then in VS Code choose File > Open Folder and select `aditya-portfolio`.
2. Install the "Live Server" extension, right-click `index.html` and choose "Open with Live Server".
   (You can also just double-click `index.html` to open it in a browser.)

## Edit your details
Open `index.html` and search for `CONFIG` near the top of the `<script>`:
- `profileImage`: already set to `images/profile.jpg` (your photo is included)
- `resume`: already set, the Download Resume button is active
- `linkedin`: add your LinkedIn URL
- `email`, `email2`, `phone`, `github`, `aiEndpoint`: already set or optional

Projects are in the `PROJECTS` list: add, remove or edit entries and links there.

## Deploy on Netlify
Go to app.netlify.com, choose Add new site > Deploy manually, and drag this whole folder in.

## Notes
- Ask Aditya AI runs in demo mode (answers from the facts in the page). Set `aiEndpoint` to a backend URL for a real AI.
- The contact form opens the visitor's email app; it does not send mail by itself.
