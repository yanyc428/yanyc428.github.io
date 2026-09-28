# Publication figures

Put a paper's representative figure(s) here, then reference it in that paper's
markdown file under `_publications/`.

## How to add a figure

1. Save the image here, e.g. `images/publications/inftythink.png`
   (square-ish or landscape PNG/JPG works best; Figure 1 / the framework figure
   is usually the most representative).

2. In the matching file under `_publications/` (e.g.
   `_publications/2026-04-24-inftythink.md`), add to the front matter:

   ```yaml
   image: "/images/publications/inftythink.png"
   image_caption: "Overview of the InftyThink iterative reasoning framework."
   ```

   A second figure is optional:

   ```yaml
   image2: "/images/publications/inftythink-results.png"
   image2_caption: "Main results on long-context reasoning benchmarks."
   ```

3. The figure(s) render on that paper's detail page, between the abstract button
   and the abstract text.

Filenames are up to you; only the path in the `image:` field has to match.

## Link buttons

Besides `paperurl`, a paper can link its code, project page, data, and model.
Each one that is set shows up as a button on the detail page and as a link on
the publications list:

```yaml
codeurl: 'https://github.com/ZJU-REAL/InftyThink'
projecturl: 'https://zju-real.github.io/InftyThink'
dataurl: 'https://huggingface.co/datasets/...'
modelurl: 'https://huggingface.co/...'
```
