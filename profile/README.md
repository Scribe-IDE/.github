<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Scribe-IDE/Scribe/main/docs/logo-dark.svg">
    <img src="https://raw.githubusercontent.com/Scribe-IDE/Scribe/main/docs/logo-light.svg" alt="Scribe, the LaTeX editor for working scientists" width="420">
  </picture>
</p>

<p align="center">
  <a href="https://scribe.georgekiritsis.com"><b>Website</b></a>
  &nbsp;&middot;&nbsp;
  <a href="https://github.com/Scribe-IDE/Scribe/releases/latest"><b>Download</b></a>
  &nbsp;&middot;&nbsp;
  <a href="https://scribe.georgekiritsis.com/manual.html"><b>Manual</b></a>
  &nbsp;&middot;&nbsp;
  <a href="https://github.com/Scribe-IDE/Scribe#readme"><b>Source</b></a>
  &nbsp;&middot;&nbsp;
  <a href="https://scribe.georgekiritsis.com/#contribute"><b>Contributing</b></a>
</p>

Scribe is a free desktop editor for LaTeX papers, theses and notes, with the Python behind them in
the same project. Figures and numbers in the PDF come straight from the notebooks, everything
compiles on your own computer, and there is no account to make.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Scribe-IDE/Scribe/main/docs/screenshot-dark.png">
  <img src="https://raw.githubusercontent.com/Scribe-IDE/Scribe/main/docs/screenshot-light.png" alt="Scribe with a paper open: the source on the left, the compiled PDF with a figure from the notebook on the right">
</picture>

### What it does

- **Notebooks in the paper.** `\nbfig` and `\nbval` bring a notebook's figures and measured values
  into the LaTeX, rerun when the code changes.
- **A LaTeX editor that knows the paper.** Completion, hover previews, writing checks with fixes,
  snippets, an equation editor, tables as a grid, SyncTeX both ways.
- **TikZ drawn and written.** The picture beside its source, with nodes dragged and shapes drawn
  on a grid; every change is an edit to the TikZ.
- **An assistant with your own model.** Claude, GPT, Gemini or a local model through Ollama, with
  your key kept in the system keychain.
- **Track changes and comments** in the source with the `changes` package, latexdiff revisions,
  and a letter to the reviewers.
- **Notes, reading and revision cards.** Markdown notes with maths, highlights from the papers you
  cite, spaced repetition.

For macOS, Windows and Linux, under the MIT licence.

### Repositories

- [**Scribe**](https://github.com/Scribe-IDE/Scribe): the app, a Tauri 2 desktop editor with a
  TypeScript front end and a Rust back end. Releases and issues live here.

### Getting involved

Bug reports and ideas go in the [issues](https://github.com/Scribe-IDE/Scribe/issues). To change
something yourself, fork [Scribe](https://github.com/Scribe-IDE/Scribe), run it with
`npm install && npm run tauri dev`, and send a pull request; a template, a theme or a writing check
makes a good first one. A star on the repository helps other people find it.
