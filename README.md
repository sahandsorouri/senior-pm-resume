# Sahand Sorouri — Senior Product Manager Resume

My resume, written in LaTeX. Senior PM with 6+ years across crypto, fintech, and e-commerce, based in Dubai.

[**Download the PDF**](Sahand%20Sorouri%20-%20Senior%20Product%20Manager.pdf)

- Portfolio: [sahand.sorouri.com](https://sahand.sorouri.com)
- LinkedIn: [linkedin.com/in/sahand-sorouri](https://linkedin.com/in/sahand-sorouri)
- Email: sahand.sorouri@gmail.com

## What is in here

| File | Description |
|------|-------------|
| `Resume Template.tex` | The LaTeX source |
| `Sahand Sorouri - Senior Product Manager.pdf` | The compiled resume |

## Use it as a template

The source is a single, self-contained `.tex` file. You are welcome to use it as a starting point for your own resume.

It works with any of these fonts and falls back automatically if none are installed: Segoe UI, Bahnschrift, Inter, Carlito, Helvetica Neue, and finally Latin Modern. So it compiles cleanly on any machine.

### Build it

You need a LaTeX setup with **XeLaTeX** (the source uses `fontspec`, so pdfLaTeX will not work).

```bash
xelatex "Resume Template.tex"
```

Or with [Tectonic](https://tectonic-typesetting.github.io/), which downloads what it needs on its own:

```bash
tectonic "Resume Template.tex"
```

You can also drop the `.tex` into [Overleaf](https://www.overleaf.com) and set the compiler to XeLaTeX.

### Make it yours

Edit the text inside `\begin{document} ... \end{document}`. The styling commands are defined once at the top (`\sectiontitle`, `\majorposition`, `\position`, `\bulletitem`, `\kpi`, `\boxedtext`), so you change content without touching layout.
