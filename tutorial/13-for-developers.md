# 13. For people who write code

Everything in the earlier chapters works without code. This chapter is for web developers who want more control. Nothing here gets in the way of beginners: it's all in collapsed sections or at the bottom of panels.

## The Code section

At the bottom of the **Site** tab, open **Code (optional)**:

![The Code section of the Site tab](images/code-01-code-section.png)

- **custom.css**: your own stylesheet for this website.
- **custom.js**: your own script.
- **Site file (JSON)**: the project file itself.
- **In the head of every page** and **At the end of every page**: code boxes for snippets that belong in every page, such as meta tags, an analytics snippet, a library from a CDN or a chat widget's script.

Each file opens in a normal VS Code editor beside the visual editor, with all of VS Code's code editing features. `custom.css` and `custom.js` are created with a short explanation the first time you open them. The label next to each says **create** or **in use**.

## custom.css: live styling

`custom.css` is loaded **after** Moritsuke's own styles, so it can override anything. Changes show on the page **as you type**, before you even save.

![custom.css beside the editor; the highlight class turns the heading orange](images/code-03-custom-css.png)

Useful selectors:

- Your own classes and IDs, from the **Advanced** section (below).
- The builder's classes, which all start with `wb-`: `.wb-section`, `.wb-heading`, `.wb-text`, `.wb-button`, `.wb-card`, `.wb-navbar`, `.wb-footer` and so on.
- Theme variables: `var(--wb-accent)`, `var(--wb-bg)`, `var(--wb-surface)`, `var(--wb-text)`, `var(--wb-muted)`, `var(--wb-radius)`, `var(--wb-font-heading)`, `var(--wb-font-body)`.

## custom.js

`custom.js` runs in **Preview** and on the **exported website**, after the page and Moritsuke's own script have loaded. It doesn't run while you edit on the canvas, so it can't interfere with editing.

### Driving effects from your script

Every text effect and every Look box setting is written through a CSS variable, so a script can change it on a live page without touching the element's other styles:

```js
const hero = document.querySelector("#hero");        // an ID from the Advanced section
hero.style.setProperty("--wb-blur-amount", "20px");  // blur harder
hero.style.setProperty("--wb-fade", "0.4");          // fade it back
hero.setAttribute("data-wb-fx", "off");              // all effects off
hero.removeAttribute("data-wb-fx");                  // and back on
```

The variables are `--wb-blur-amount`, `--wb-glow-size`, `--wb-glow-color`, `--wb-outline-width`, `--wb-outline-color`, `--wb-shadow-x`, `--wb-shadow-y`, `--wb-shadow-blur`, `--wb-shadow-color`, and from the Look box `--wb-own-radius`, `--wb-nudge-x`, `--wb-nudge-y` and `--wb-fade`. A button can do the same without code: set **When clicked** to *Turn an element's effects on or off*.

## Code in the head and at the end of every page

The two code boxes in the Code section are copied into every exported page **exactly as typed**: the head code last in `<head>`, the end code after Moritsuke's own scripts, just before `</body>`. A page can add its own in its settings, under **Advanced (for code)**; it comes after the site's.

They're left out of **Preview** and of the project pictures in the Moritsuke tab, so an analytics script never counts your own editing. Try them with the browser button next to **Export** (see [Try it in your browser](10-preview-and-screen-sizes.md#try-it-in-your-browser)) or on the exported site.

## Classes and IDs: the Advanced section

Every element has an **Advanced (for code)** section at the bottom of its settings, closed by default.

![The Advanced section with a CSS class](images/code-02-advanced.png)

- **CSS classes**: one or more class names separated by spaces. They're added to the element's outer HTML tag.
- **ID**: a unique name for the element, for `#links` and `document.getElementById`. On a section with a menu label, the ID is also used for the navigation link.

Names that aren't valid in HTML are left out.

## The HTML code element

**Add → Code → HTML code** inserts your own HTML: an embed code (map, music player, form service, social post) or hand-written markup.

![An HTML code element styled by custom.css](images/code-04-html-element.png)

- It's shown on the canvas as you type. **Tab** indents in the code box.
- For safety, scripts inside it don't run in the editor or Preview, only on the exported website.
- Style it from `custom.css`.

## The project file (JSON)

**Site file (JSON)** opens the `.site.json` project beside the visual editor. Both show the same file: edit the JSON and the page updates, change the page and the JSON updates. Undo works across both.

![The project file beside the visual editor](images/code-05-json-beside.png)

The format, briefly:

- `meta`, `theme` and `settings`: the Site tab.
- `shared`: the elements shown on every page.
- `pages`: each page, with its sections in `children`.
- Every element has an `id`, a `type`, its settings in `props`, and `children` if it holds other elements.

If the JSON can't be read (for example a missing comma), the visual editor shows the error and waits until it's fixed.

## Live reload in a browser

The browser button in the toolbar (next to **Export**) exports the website, serves it on `http://localhost:5500` and opens it. Saving the project, `custom.css` or `custom.js` re-exports and reloads the page in the browser. The address is in the status bar; click it to stop the server.

If you'd rather use your own server (a framework's dev server, *Live Server*, or anything else), turn on **Settings → Moritsuke → Export On Save** and point it at the `site` folder.

## What the export looks like

The export is plain, readable HTML, CSS and JavaScript, with no framework and no build step:

- One `.html` file per page, with semantic tags (`header`, `section`, `nav`, `footer`, `dialog`).
- `styles.css`: theme variables at the top, then the styles of all elements.
- `site.js`: only the behaviour the page uses (menu, filters, detail panel, form).
- `custom.css` and `custom.js` when they exist, linked after the builder's own files.

---

Next: [Settings, shortcuts and help](14-settings-shortcuts-and-help.md)
