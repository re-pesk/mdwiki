# Download

## Precompiled releases

MDwiki ships with two different files:

- `mdwiki.html`, 320kB minified (100kB gz compressed). Contains all required scripts and styles inlined, works offline
- `mdwiki-slim.html`, 80kB minified (32kB gz compressed). Contains only minimal set off styles and scripts, other resources are loaded from a CDN during runtime (jQuery, Bootstrap, Themes, etc.). Does **not** work offline.

### Get the latest release &raquo;[here][release_dl]&laquo;

[release_dl]: https://github.com/Dynalon/mdwiki/releases

---

## Source code

To download and build from source, `node.js` >= 0.10 is required with installed npm.

```bash
git clone https://github.com/Dynalon/mdwiki.git
cd mdwiki
npm install
npm run build

```
