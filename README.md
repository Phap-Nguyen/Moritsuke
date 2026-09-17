# Moritsuke

*Moritsuke* (盛り付け) is the Japanese art of plating: arranging food so the whole dish looks good. This extension does the same for websites.

Build a website by dragging and dropping, right inside VS Code. No code needed: pick a template, drag sections onto the page, type your text, choose your colours, and export a finished website you can put online.

![The Moritsuke editor in VS Code: elements to add on the left, the page in the middle, settings on the right](https://raw.githubusercontent.com/Phap-Nguyen/Moritsuke/main/tutorial/images/getting-started-06-editor.png)

If you do write code, you can add your own CSS and JavaScript, paste HTML, and edit the project file directly. Your changes show up in the editor as you type.

**New here? Read the [tutorial](tutorial/README.md)**: a step-by-step guide with pictures, from [getting started](tutorial/01-getting-started.md) to putting your website online.

## Install

**From a .vsix file** (for example, downloaded from a website):

1. In VS Code, open the **Extensions** view (the four-squares icon on the left, or Cmd+Shift+X on Mac, Ctrl+Shift+X on Windows).
2. Click the **⋯** menu at the top of that view and choose **Install from VSIX…**
3. Pick the `moritsuke-….vsix` file.

You can also drag the `.vsix` file onto the Extensions view, or run `code --install-extension moritsuke-0.8.0.vsix` in a terminal.

## Get started

1. Click the **Moritsuke** icon (a small browser window) in the bar on the far left of VS Code.
2. Choose **Create New Project**: give it a name, pick the *Portfolio* template or a *Blank page*, and choose where to save it.
3. The editor opens. Start building.

Already made a website with Moritsuke? Choose **Add Existing Project** and pick its folder. Your websites stay listed in the side bar and in the **Moritsuke** tab, so you can come back to them any time.

VS Code also shows a short **Get started with Moritsuke** guide after installing (Help → Welcome to open it again). For the full walkthrough with pictures, see [Getting started](tutorial/01-getting-started.md) in the tutorial.

## Building your website

| Where | What it's for |
| --- | --- |
| **Add** (left) | Everything you can put on a page. Drag it onto the page, or click it to add it next to what's selected. |
| **Layers** (left) | What's on the page, as a list. Drag to reorder. |
| **Pages** (left) | Your pages: add, rename, reorder, delete. The first page is the home page. |
| **Page** (middle) | Click to select, drag to move. **Double-click text** to type directly on the page. |
| **Element** (right) | Settings of what you selected: text, image, layout and on/off features. |
| **Site** (right) | Site title, colours, fonts, corner roundness, export folder. |

- **Desktop / Tablet / Phone** (top) show how the page looks on each screen size.
- **Preview** lets you use the page like a visitor: open the menu, filter projects, follow links between pages.
- **Undo** with Cmd+Z (Mac) or Ctrl+Z (Windows), save with Cmd+S or Ctrl+S.
- The navigation bar and footer can be **shown on every page**: change them once and every page updates.

### What you can add

| Group | Elements |
| --- | --- |
| Sections | Hero, About, Navigation, Project grid, Contact, Footer |
| Layout | Section, Columns, Spacer, Divider |
| Basic | Heading, Text, Image, Button, Video (YouTube link or a video file) |
| Code | HTML code (for embeds and your own markup) |

Features you can switch on or off include: sticky navigation, a collapsible menu on phones, project filters, a project detail panel, black-and-white images until hover, a contact form (opens the visitor's email app, or sends to your own server), and a back-to-top link.

## Export (putting it online)

Click **Export**. Your website is saved in a folder called `site` next to your project: one HTML file per page, the styles, a small script and your images. Open `index.html` to see it in your browser, or upload the folder to any web host (GitHub Pages, Netlify, your own server…).

## For people who write code

- **Site tab → Code**: `custom.css` loads after the builder's styles, so it can override anything; `custom.js` runs in Preview and on the exported site. Both open beside the editor, and CSS changes show on the page **as you type**.
- **Advanced** section on every element: give it CSS classes and an ID to target it from your code.
- **HTML code** element for embeds and hand-written markup.
- **Site file (JSON)** opens the project file beside the editor. Edits in either one show up in the other right away.
- **Settings → Moritsuke → Export On Save** keeps the `site` folder up to date whenever you save, so a live-reload server (like the Live Server extension) refreshes your browser automatically.
- The export is plain HTML, CSS and JavaScript with no framework and no build step.

A project is a folder with a `.site.json` file, an `assets` folder for images, and optionally `custom.css` / `custom.js`.

## Settings

| Setting | What it does |
| --- | --- |
| Open Projects Tab | Open the Moritsuke tab when you click the side bar icon (on by default). |
| Projects Folder | Where new projects are saved. Empty means `Documents/Moritsuke`. |
| Export On Save | Export the website every time you save. |

## Support

Moritsuke is free. If it helps you, you can buy me a bowl of pho:

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/A3G227661M)

---

Planned features are listed in `ROADMAP.md`, and notes for working on the extension itself in `DEVELOPMENT.md` (both in the extension's source folder).
