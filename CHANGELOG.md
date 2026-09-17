# Changelog

Versions with a letter (like 0.7.3a) are small fixes on top of the version before them.

## 0.8.1

- **Minimal portfolio** template: a light, quiet one-page portfolio with a large introduction, your selected work in big cards, an About section with your experience, and an email link. Pick it when you create a new project.

## 0.8.0

- **Website Builder is now called Moritsuke** (盛り付け, the Japanese art of plating food).
- Because the extension has a new name, it installs as a new extension: uninstall *Website Builder*, set your Moritsuke settings again, and bring back your projects with **Add Existing Project**. Your project files don't change.
- New projects are saved in `Documents/Moritsuke`.

## 0.7.5

- While dragging, rest the pointer on the **Add**, **Layers** or **Pages** tab to open it, so you can drag something from Add straight into Layers.
- A step-by-step tutorial with pictures, from getting started to putting your website online.

## 0.7.4a

- Fixed: in Preview, clicking About, Projects or Contact in the menu turned the page white. Section links now scroll to the section, and links to a section on another page open that page first.
- Links to other websites clicked in Preview now open in your browser.

## 0.7.4

- **Export On Save** setting: exports the website every time you save the project, `custom.css` or `custom.js`.

## 0.7.3b

- The extension is now MIT licensed.

## 0.7.3a

- The **⋯** menu on project cards no longer covers the folder name.
- Clearer message after exporting.

## 0.7.3

- **HTML code** element for embeds and your own markup.
- **Advanced** section on every element: CSS classes and ID.

## 0.7.2

For people who write code:

- `custom.css` and `custom.js` for each project, in the new **Code** section of the Site tab. CSS changes show on the page as you type.
- Open the project file (JSON) beside the editor.

## 0.7.1

- **Get started** walkthrough.
- Extension icon, and an installable `.vsix` package.

## 0.7.0a

- Projects that were moved or deleted show as *can't be found* in the list, instead of failing to open.

## 0.7.0

- **Website Builder in the activity bar**, next to Explorer and Search, with the list of your projects.
- **Create New Project** and **Add Existing Project**, in the side bar and in the new **Website Builder** tab.
- New projects are saved in `Documents/Website Builder` unless you pick another folder.

## 0.6.1a

- In a narrow editor, the Add, Layers and Pages tabs show icons only, so their names don't get cut off.

## 0.6.1

- Images and videos update on the page when their files change. The old picture stays until the new one is ready.

## 0.6.0d

- Text pasted while typing on the page arrives without formatting.

## 0.6.0c

- Fixed: text shown in small capital letters (like labels) was saved in capitals after typing on the page.

## 0.6.0b

- Double-clicking text works more reliably.

## 0.6.0a

- The bar with move, duplicate and delete no longer covers the text of elements near the top of the page.

## 0.6.0

- **Type directly on the page**: double-click a heading, paragraph, button or section title.

## 0.5.5

- **Drag and drop in Layers** to reorder elements or move them into another section.

## 0.5.4

- Projects made with earlier versions open as a one-page site.

## 0.5.3

- The navigation links to your pages, and highlights the page you're on.

## 0.5.2

- **Navigation and footer on every page**: change them once and every page updates.

## 0.5.1

- Export creates one HTML file per page, with unique file names.

## 0.5.0b

- Switching pages scrolls the page back to the top.

## 0.5.0a

- The Delete key never deletes a page, so a page can't be removed by accident.

## 0.5.0

- **Multiple pages**: add, rename, reorder and delete pages in the new Pages tab, with a name, file name, tab title and description for each.

## 0.4.4b

- Export finishes right away, instead of waiting for you to close its message.

## 0.4.4a

- The close button of the project detail panel no longer pushes the picture down.

## 0.4.4

- **Preview**: use the page like a visitor, with the menu, filters and detail panel working.

## 0.4.3

- **Desktop, Tablet and Phone** views, to see how the page looks on each screen size.
- Columns stack on phones, and the navigation gets a collapsible menu.

## 0.4.2

- Site title, description and language.

## 0.4.1

- **Dark**, **Light** and **Paper** theme presets.

## 0.4.0

- **Site settings**: colours, fonts, corner roundness and content width.

## 0.3.3b

- Large headings are a little smaller, so they fit better next to pictures.

## 0.3.3a

- The example project uses placeholder images.

## 0.3.3

- **Hero** and **About** sections, ready to fill in.
- **New Site** command, starting from a portfolio template or a blank page.

## 0.3.2

- **Contact** section, with an optional contact form that opens the visitor's email app or sends to your own server.

## 0.3.1b

- On tablets, the project grid shows two cards per row.

## 0.3.1a

- Project cards work better with a keyboard and screen readers.

## 0.3.1

- **Project grid** section: a card for each project, tag filters, a detail panel and black-and-white covers until hover.

## 0.3.0

- **Navigation** and **Footer** sections. The navigation links to sections that have a menu label.

## 0.2.5

- **Layers** list showing everything on the page. Click a row to select that element.

## 0.2.4

- **Video** element, for a YouTube link or a video file. YouTube videos show their preview picture in the editor.

## 0.2.3

- A bar on the selected element to select its parent, move it up or down, duplicate it or delete it.

## 0.2.2

- The page scrolls by itself when you drag near its top or bottom edge.
- Press Esc to cancel a drag.

## 0.2.1b

- Fixed: an interrupted drag could still drop the element.

## 0.2.1a

- Fixed: while dragging from Add, the selected element looked as if it was being moved.

## 0.2.1

- Move elements by dragging them on the page. A blue line shows exactly where they'll land.

## 0.2.0

- **Columns**, **Spacer** and **Divider**.

## 0.1.3

- Click an element in the Add panel to add it next to the selected one.

## 0.1.2

- Keyboard shortcuts: Delete, duplicate (Cmd/Ctrl+D), move up and down (Alt+↑/↓).

## 0.1.1b

- Fixed: quick edits could briefly jump back to an older version.

## 0.1.1a

- Fixed: Redo sometimes did nothing after Undo.

## 0.1.1

- Undo, redo and save work like any other file in VS Code.

## 0.1.0c

- A clear message when a project file can't be read, with a button to open it as text.

## 0.1.0b

- Fixed: your own images didn't show on the page in the editor.

## 0.1.0a

- Fixed: the editor could stay stuck on "Loading…" when opening a project.

## 0.1.0

First version.

- Open a `.site.json` file to edit a one-page website visually.
- Drag a **Section** onto the page, then **Heading**, **Text**, **Image** and **Button** into it.
- Click an element to change its settings in the panel on the right, or delete it.
- **Export** the page as plain HTML and CSS.
