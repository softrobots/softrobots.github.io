# Evolving Modular Soft Robots without Explicit Inter-Module Communication using Local Self-Attention

This repo contains the videos for the anonymous submission for GECCO 2022.

### If all you want to do is view the page locally (i.e. you are a reviewer)

Run `python -m http.server` to serve on the base directory to view `index.html` in a local browser.

### Article

`draft.md` - main text of the article, in markdown.

`draft_appendix.md` - appendix, in markdown.

`draft_bib.html` - the citations.

`draft_header.html` - start of the document

`index.html` - generated, don't edit this file.

### Instructions to Build and Test
```bash
git clone https://github.com/softrobots/softrobots.github.io.git
cd softrobots.github.io
npm install
```

Modify text by editing `draft.md` -- this is where all of the content exists.

Appendix content goes in `draft_appendix.md`. Add bib entries to `draft_bib.html`.

Run `./bin/make` to build document into `index.html` (which are identical).
Run `python -m http.server` to serve on the base directory to view `index.html` in a local browser for debugging.

To watch all markdown files for changes and then compile them, you can run the following
```
brew install fswatch
./bin/watch
```
