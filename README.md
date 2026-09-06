# kellynwu.github.io

Personal site: https://kellynwu.github.io

Static HTML, no build step. Edit the files and push; GitHub Pages serves `main` directly.

```
index.html                          the whole site: welcome, about, projects,
                                    the real numbers, work in progress, contact
style.css                           stylesheet for the landing page (light + dark)
```

Each project is told in the same four beats, my motivation, what it solves, what I
learnt and the takeaway, in my own words. Section 03 is the measured evidence, including the
thing the drone cannot do.

**Adding photos or video.** Every project has a `<figure class="media">` slot with a
dashed placeholder. Drop the file in `assets/` and replace the `<div class="ph">…</div>`
with the `<img>` or `<video>` line already written in the comment directly above it, then
rewrite the `<figcaption>`. Portrait media uses `--ratio: 9 / 16`, landscape `16 / 9`.

To preview locally:

```bash
python3 -m http.server 8000
# open http://localhost:8000
```
