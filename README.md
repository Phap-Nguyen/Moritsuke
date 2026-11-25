# Moritsuke

*Moritsuke* (盛り付け) is the Japanese art of plating: arranging food so the whole dish looks good. This extension does the same for websites.

Build a website by dragging and dropping, right inside VS Code. No code needed: pick a template, drag sections onto the page, type your text, choose your colours, and export a finished website you can put online.

**Building a website:** drag sections onto the page, type straight on it, and set up buttons that switch between panels.

<video src="https://raw.githubusercontent.com/Phap-Nguyen/Moritsuke/main/tutorial/images/demo-website.mp4" controls muted loop playsinline width="720"></video>

**Building a small web app, coming in 0.9.0:** a screen of a fixed size where you place things freely, line them up with guides, resize them, and switch between screen sizes. It's already in the editor and is being finished off, one release at a time.

<video src="https://raw.githubusercontent.com/Phap-Nguyen/Moritsuke/main/tutorial/images/demo-webapp.mp4" controls muted loop playsinline width="720"></video>

[**Install from the Marketplace**](https://marketplace.visualstudio.com/items?itemName=phap-nguyen.moritsuke) · [**Project page on GitHub**](https://github.com/Phap-Nguyen/Moritsuke) · [**Tutorial**](https://github.com/Phap-Nguyen/Moritsuke/blob/main/tutorial/README.md) · [**Releases**](https://github.com/Phap-Nguyen/Moritsuke/releases)

If you do write code, you can add your own CSS and JavaScript, paste HTML, and edit the project file directly. Your changes show up in the editor as you type.

**New here?** The [tutorial](https://github.com/Phap-Nguyen/Moritsuke/blob/main/tutorial/README.md) is a step-by-step guide with pictures, from [getting started](https://github.com/Phap-Nguyen/Moritsuke/blob/main/tutorial/01-getting-started.md) to putting your website online.

## Install

**From the Marketplace** (easiest, and VS Code keeps it up to date):

1. In VS Code, open the **Extensions** view (the four-squares icon on the left, or Cmd+Shift+X on Mac, Ctrl+Shift+X on Windows).
2. Search for **Moritsuke** and click **Install**.

Or open the [extension page](https://marketplace.visualstudio.com/items?itemName=phap-nguyen.moritsuke) and click **Install**.

**From a .vsix file** (for example, downloaded from the [releases page](https://github.com/Phap-Nguyen/Moritsuke/releases)):

1. Open the **Extensions** view.
2. Click the **⋯** menu at the top of that view and choose **Install from VSIX…**
3. Pick the `moritsuke-….vsix` file.

You can also drag the `.vsix` file onto the Extensions view, or run `code --install-extension moritsuke-0.8.2.vsix` in a terminal.

## Get started

1. Click the **Moritsuke** icon (a small browser window) in the bar on the far left of VS Code.
2. Choose **Create New Project**: give it a name, pick a template (*Portfolio*, *Minimal portfolio*) or a *Blank page*, and choose where to save it.
3. The editor opens. Start building.

Already made a website with Moritsuke? Choose **Add Existing Project** and pick its folder. Your websites stay listed in the side bar and in the **Moritsuke** tab, so you can come back to them any time.

VS Code also shows a short **Get started with Moritsuke** guide after installing (Help → Welcome to open it again). For the full walkthrough with pictures, see [Getting started](tutorial/01-getting-started.md) in the tutorial.

## Building your website

| Where | What it's for |
| --- | --- |
| **Add** (left) | Everything you can put on a page. Drag it onto the page, or click it to add it next to what's selected. |
| **Layers** (left) | What's on the page, as a list. Drag to reorder. |
| **Pages** (left) | Your pages: add, rename, reorder, delete. The first page is the home page. Drag a page onto another to put it in a dropdown under it in the menu. |
| **Page** (middle) | Click to select, drag to move. **Double-click text** to type directly on the page. |
| **Element** (right) | Settings of what you selected: text, image, layout and on/off features. |
| **Site** (right) | Site title, sharing (address, tab icon, link preview), colours, fonts, corner roundness, export folder, code. |

- **Desktop / Tablet / Phone** (top) show how the page looks on each screen size.
- **Preview** lets you use the page like a visitor: open the menu, filter projects, click tabs, follow links between pages.
- **Undo** with Cmd+Z (Mac) or Ctrl+Z (Windows), save with Cmd+S or Ctrl+S.
- The navigation bar and footer can be **shown on every page**: change them once and every page updates.

### What you can add

| Group | Elements |
| --- | --- |
| Sections | Hero, About, Cards, Info cards, Tabs, Navigation, Project grid, Contact, Footer |
| Layout | Section, Columns, Grid, Card, Spacer, Divider |
| Basic | Heading, Text, Image, Button, Video (YouTube link or a video file) |
| Code | HTML code (for embeds and your own markup) |

### Backgrounds

Every section has a **Background** setting: the page colour, the surface colour, the accent, or one of your own:

- **A colour of your own** - any colour, with the text automatically switched to light or dark so it stays readable.
- **A gradient** - up to nine colours. Drag the handles on the bar to move a colour along it, click the bar to add one, and **Flip** to turn it around. On the page itself, a line is drawn across the section: drag either end to aim the gradient and set where the colours start and finish, drag a marker to move a colour in between, or drag the line to slide the whole thing. Hold Shift while dragging to snap the direction.
- **A picture** - fill, fit or tile it, choose where it sits, darken it so text on top stays readable, and blur it.

For all three you can also:

- Set the **text colour**: default (light or dark, whichever reads better on it), light, dark, or a colour of your own.
- **Fade the edges**, so the background melts into the page instead of stopping at a hard line.
- Add **grain**, a fine film grain over the background.
- Choose whether the background covers **the whole width** or only **the content column** (which gives it the theme's rounded corners, like a big card).

### The Look box

Every element has a **Style** section with the same handful of settings, whatever it is - a heading, a picture, a card, a whole section:

| Setting | What it does |
| --- | --- |
| **Text colour** | The colour of the words in it |
| **Background** | A colour behind it |
| **Border** | Width, colour and solid, dashed or dotted |
| **Corner radius** | Rounded corners, which reach the picture or video inside. Drag the round handle in the element's corner on the page, or type a number |
| **Shadow** | Soft, medium, strong, or one cast inwards |
| **Inner space** | Padding inside it |
| **Nudge across / down** | Moves it without moving anything else, so elements can overlap on an ordinary page |
| **Fade** | How solid it is |

Anything left empty stays exactly as it was, so this changes nothing until you use it.

### Effects on text

Headings and text have a **Style** section with five effects. Switch on as many as you like at once - an outlined heading can glow and cast a shadow at the same time. Each one keeps its own settings, so turning it off and on again picks up where it was.

| Effect | Settings |
| --- | --- |
| **Outline** | Thickness, colour, and **hollow** for nothing but the outline |
| **Glow** | Size, strength, colour |
| **Shadow** | Distance, direction, blur (0 keeps a hard edge), colour |
| **Gradient fill** | The same gradient bar as backgrounds, and a direction |
| **Blur** | Type (soft or motion), direction, amount, and any number of blurred patches |

**Blur** covers all of an element, or only the patches you put on it. Add a patch and work on it straight on the page: click it to pick it up, drag it to move it, pull its handles to resize it, and drag the orange grip to say how far it **eases out** at its edges. Only the patch you are working on shows its handles, so several patches stay out of each other's way; the panel lists them all, and each can be **duplicated** or removed there. Each patch is a **box or an oval**, is named (Blur 1, Blur 2…), and can also be removed with the cross that appears when you point at it. Up to eight per element.

Each patch either **follows the element's blur** or carries **its own amount**, so one part of a line can be barely soft and another lost completely. Patches that overlap merge into one blurred area.

**Patches blur** either **this element only** (the default: the words go soft and everything around them stays exactly as it is) or **everything behind them**, which works like a lens over the page and blurs the background as well.

On the page, a patch is drawn with a **solid line where the blur is at full strength and a dashed line out to where it has faded away**. With no patches at all, the whole element is blurred, and a handle on the page sets how far the blur reaches.

Effects are plain CSS, except a motion blur, which needs a small definition the page carries only when one is used.

### Handles on the page

Some settings are changed on the page itself, by dragging the thing they belong to. The panel still has the numbers.

- **A section's spacing:** select a section and drag the dashed line at the top or bottom of it. The striped band is the space you're changing (above and below stay equal). It moves in steps of 8; hold Alt for any value.
- **A section's width:** drag the bar on its left or right side. It catches on the theme's width, the narrow width and the full window; anywhere else becomes the section's own width.
- **A cropped picture:** an image with a shape other than Original, or a section's background picture, gets a round grip. Drag it and the picture moves inside its frame until its edge meets the frame's.
- **A colour from the page:** every colour setting has a dropper. Press it, then click anything on the page to take its colour: a pixel of a picture, a letter, a background or a point of a gradient. Escape calls it off.

### Motion

Every element has a **Motion** group in the Element panel. Each choice is a small tile that acts out what it does, and picking one plays it on the page straight away. The play button in the element's toolbar on the page (or **Play again** in the panel) shows it once more.

- **When it scrolls into view:** fade, rise, slide in from either side, or zoom, once, as it first comes into view. Set how long it takes and how long it waits. On a section, card, grid or columns, **In turn** brings what's inside in one after another instead, so a row of cards arrives card by card.
- **When the pointer is over it:** lift, grow a little, or glow.
- **Stays on screen while scrolling:** it stays in view until the end of what it's in. In Columns, a picture next to a long text stays beside the text as it scrolls.
- **Its effects, while scrolling** (on text with effects): a blur that clears, or a glow that builds, as the element comes up the screen.

**Smooth scrolling** for menu links and Back to top is a switch in the Site tab. While you edit, elements stay put under your pointer and nothing hides itself: the motion only plays when you pick it or press play. Preview and the website do it for real. Visitors who have asked their device for less motion see everything in place, without movement.

### Free pages, for small web apps

A page is either **Flow** (sections under each other, like a normal website) or **Free** (one screen where you place things anywhere). The switch is in the toolbar, next to the page name.

On a Free page you also choose:

- **Screen size.** Pick one of the sizes in the list (monitor, Full HD, laptop, a tall screen, tablet, phone) or type your own width and height next to it.
- **Scale or Adapt**, which is what happens on a screen that isn't your size:
  - **Scale** shrinks the whole screen to fit the window, so your design stays exactly as you made it.
  - **Adapt** fills the window instead, and every element keeps the edges it's **anchored** to. The same app then suits a wide monitor, a Full HD laptop and a tall screen turned on its side.
- **Anchors** (Element panel, under Place, on Adapt screens): across the screen an element can keep the **Left** edge, the **Right** edge, stay in the **Center**, or **Stretch** to keep both. Down the screen: **Top**, **Bottom**, **Middle** or **Stretch**. A top bar usually stretches across, a sidebar stretches down, a button in a corner keeps that corner.

Switching to Adapt gives everything a sensible anchor to start with, and changing the screen size moves things the way the window will, so you can try a size and see the real result. Use **Preview** with the Desktop / Tablet / Phone buttons to watch it adapt.

### Free sections: place things anywhere on a normal page

Any section can be **Free** too, while the rest of the page keeps flowing: select the section and set *Section layout* to "Free: place anywhere". Its elements stay where they were, and from then on you drag them wherever you like inside the section, overlapping if you want (a heading over a picture in a hero, with a normal About section below it). Snapping, resize handles, the arrow keys and lining up work as on a Free page.

- **Area height:** drag the handle under the section, or type it in. It snaps to the bottom of the lowest element.
- **Narrow windows:** **Scale** (the default) shrinks the whole section with the window, so the design stays exactly as you made it, on a phone too. **Adapt** keeps sizes as they are and lets each element follow its anchors.

Switching a section back to Flow puts its elements under each other again, and they remember their places for the next time it's Free.

A button can also **switch an element's effects on or off**: set *When clicked* to "Turn an element's effects on or off", pick the element, and choose whether the click turns them on, off, or switches them each time. The change eases in rather than snapping, and is left alone for anyone who has asked for less motion.

Features you can switch on or off include: sticky navigation, a collapsible menu on phones, project filters, a project detail panel, black-and-white images until hover, a contact form (opens the visitor's email app, or sends to your own server), and a back-to-top link. Buttons can also **show, hide or switch between elements** (tabs, a Show more button, a panel that opens and closes) without any code.

### Menus, footers and sharing

- **Dropdown menus:** in the **Pages** list, drag a page onto another page. It moves under it, indented, and on the website it drops down from that page's link in the menu (on phones it's listed under it). Drag it back between two pages to bring it to the top again. The same choice is in the page's settings: *In the menu, under*.
- **Footer columns:** select the footer and give its links a **Column** name. Links with the same name are listed together under it, above the footer's bottom row.
- **Site tab → Sharing:** the **website address** (where the site will live), the **icon** in the browser tab and in bookmarks, and the **link preview picture** shown when someone posts a link to your site in a chat or on social media. A page can have its own preview picture in its settings. A picture from your project needs the website address to show in link previews.
- **A page for broken links:** visitors who follow a link to a page that doesn't exist see a 404 page with your menu and a way back home. To design your own, switch on *Page for broken links* in a page's settings.

## Export (putting it online)

Click **Export**. Your website is saved in a folder called `site` next to your project: one HTML file per page, a `404.html` page, the styles, a small script and your images. With the website address set (Site tab, Sharing), it also has `sitemap.xml` and `robots.txt` for search engines. Open `index.html` to see it in your browser, or upload the folder to any web host (GitHub Pages, Netlify, your own server…).

## For people who write code

- **Site tab → Code**: `custom.css` loads after the builder's styles, so it can override anything; `custom.js` runs in Preview and on the exported site. Both open beside the editor, and CSS changes show on the page **as you type**.
- **Site tab → Code → In the head / At the end of every page:** meta tags, an analytics snippet, a library from a CDN or a widget's script, copied into every exported page as typed (a page adds its own in its **Advanced** settings). They're left out of Preview, so analytics never counts your own editing.
- **Advanced** section on every element: give it CSS classes and an ID to target it from your code.
- **HTML code** element for embeds and hand-written markup.
- **Site file (JSON)** opens the project file beside the editor. Edits in either one show up in the other right away.
- **Settings → Moritsuke → Export On Save** keeps the `site` folder up to date whenever you save, so a live-reload server (like the Live Server extension) refreshes your browser automatically.
- The export is plain HTML, CSS and JavaScript with no framework and no build step.

**Driving effects from your own code.** Every effect and every Look box setting is written through a CSS variable, so a script can change it on a live page without touching the element's other styles:

```js
const hero = document.querySelector("#hero");        // an ID from the Advanced section
hero.style.setProperty("--wb-blur-amount", "20px");  // blur harder
hero.style.setProperty("--wb-fade", "0.4");          // fade it back
hero.setAttribute("data-wb-fx", "off");              // all effects off
hero.removeAttribute("data-wb-fx");                  // and back on
```

The variables are `--wb-blur-amount`, `--wb-glow-size`, `--wb-glow-color`, `--wb-outline-width`, `--wb-outline-color`, `--wb-shadow-x`, `--wb-shadow-y`, `--wb-shadow-blur`, `--wb-shadow-color`, and from the Look box `--wb-own-radius`, `--wb-nudge-x`, `--wb-nudge-y`, `--wb-fade`. A button can do the same thing without any code: set **When clicked** to *Turn an element's effects on or off*.

A project is a folder with a `.site.json` file, an `assets` folder for images, and optionally `custom.css` / `custom.js`.

## Updates

Moritsuke looks for a new version once a day and tells you when one is out. Choose **Update now** and it downloads the new version, checks it and installs it; VS Code then asks you to reload. **What's new** opens the release notes instead.

The version you have is at the bottom of the **Moritsuke** tab, with a **Check for updates** link. You can also open the Command Palette (Cmd+Shift+P on Mac, Ctrl+Shift+P on Windows) and run **Moritsuke: Check for Updates**. To stop the daily check, turn off the *Check For Updates* setting.

Your projects work across versions. A project made in a newer version still opens in an older one: parts the older version doesn't know are switched off, but they stay in the file and work again once you update. Moritsuke tells you when you open such a project.

## Settings

| Setting | What it does |
| --- | --- |
| Open Projects Tab | Open the Moritsuke tab when you click the side bar icon (on by default). |
| Projects Folder | Where new projects are saved. Empty means `Documents/Moritsuke`. |
| Export On Save | Export the website every time you save. |
| Check For Updates | Look for a new version once a day and offer to install it (on by default). |

## Support

Moritsuke is free. If it helps you, you can buy me a bowl of pho:

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/A3G227661M)

---

Found a problem or have an idea? Open an [issue on GitHub](https://github.com/Phap-Nguyen/Moritsuke/issues).
