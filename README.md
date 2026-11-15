# the journal of Joanne Alice Thomas ✨

My personal portfolio, a journal-style story of everything I've built, said and manifested so far.

It's a plain static site (one `index.html` plus an `img/` folder), so there's no build step and nothing to install.

## Run it locally

Open `index.html` in your browser. That's it.

## Deploy on Vercel

1. Push this folder to a GitHub repo.
2. On [vercel.com](https://vercel.com), choose **Add New → Project** and import the repo.
3. Set **Framework Preset** to **Other**, and leave the build command and output directory empty.
4. Click **Deploy**.

Every time you push to `main`, Vercel redeploys automatically.

## Editing

- All text and styles live in `index.html`.
- To swap a photo, replace the file in `img/` and keep the same name (for example `img/joanne2.jpg` is the cover polaroid).
- To add a talk poster, put the image in `img/` and add a line to the `POSTERS` list near the bottom of `index.html`.
