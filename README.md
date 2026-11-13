# Terminal Burn website

Static website served by GitHub Pages at https://terminalburn.com.

## Wiki

The wiki starts at `/wiki/` (`wiki/index.html`). Each article is an `index.html` inside its own folder, so direct links work on GitHub Pages without client-side routing. Shared styling is in `wiki/style.css`. No build step or server is needed.

To add an article, copy an existing article folder, update its title, description, content, and GitHub edit link, then add it to the navigation on each wiki page and the wiki index. Articles are maintained through GitHub; the edit link requires repository write access or a pull request. This is a static wiki, with no public account or browser editing system.

Preview from the repository root with `python -m http.server 8000`, then visit `http://localhost:8000/wiki/`.

Keep `CNAME` set to `terminalburn.com`. Adding the wiki does not require DNS changes. Publishing follows the repository's configured GitHub Pages source.
