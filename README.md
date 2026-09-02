# Markdown Previewer

Write Markdown and see it rendered live. Runs entirely in your browser, no external libraries.

**Live:** <https://markdown-preview.slippylabs.com/>

## What it does

- Write Markdown on the left, watch the rendered HTML update on the right.
- Headings, lists, tables, code fences, links, images, blockquotes and inline formatting.

## How it works

The Markdown parser is written from scratch in the page — there is no marked, no showdown, no CDN. That keeps the whole tool one file with nothing to audit but its own source.

## Run it locally

A static site. No build step, no package manager, no dependencies:

```
git clone git@github.com:slippylabs/markdown-preview.slippylabs.com.git
cd markdown-preview.slippylabs.com
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

---

Part of [Slippy Labs](https://slippylabs.com). Every tool is indexed at
[projects.slippylabs.com](https://projects.slippylabs.com).
