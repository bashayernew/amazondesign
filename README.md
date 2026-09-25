# Amazon International — Website

Exhibition booth design & build and interior decor, Kuwait.
Arabic by default, with an **EN** button that switches the whole site to English.

## What's here

| File | What it is |
|---|---|
| `index.html` | The entire website — HTML, styles and script in one file. No build step. |
| `images/` | Your photos. Each image slot shows the file name it expects until the file exists. |

Open `index.html` in a browser to view the site locally.

## Adding images

Save photos into `images/` using the exact names listed in `images/README.txt`, e.g.
`images/logo.png`, `images/hero.jpg`, `images/booths/booth-01.jpg`.
They appear on the site automatically — no code change needed.

## Adding a project to the gallery

In `index.html`, find `var PROJECTS` and copy one line:

```js
{ src:"images/booths/booth-06.jpg", cat:"booths", en:"English caption", ar:"الوصف بالعربي" },
```

`cat` is one of `booths`, `3d`, `interior`. Add `wide:true` for a double-width tile.

## Where quote requests go

Near the top of the script in `index.html`:

```js
var WHATSAPP = "96555776301";
var EMAIL    = "amazoninternational527@gmail.com";
```

The quote form sends the visitor's filled-in details to one of these, whichever they pick.

## Deploying

Static site — no framework, no build command.
On Vercel: import this repo, set **Framework Preset: Other**, leave build and output settings empty, deploy.
Every push to `main` redeploys automatically.
