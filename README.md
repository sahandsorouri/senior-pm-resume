<img src="https://raw.githubusercontent.com/sahandsorouri/sahandsorouri/main/assets/banner.svg" alt="Sahand Sorouri" width="100%">

# Senior Product Manager Resume

My resume in LaTeX, plus a blank template of the same design for you to fill in.

[**Download the PDF**](Sahand%20Sorouri%20-%20Senior%20Product%20Manager.pdf)

- Portfolio: [sahand.sorouri.com](https://sahand.sorouri.com)
- LinkedIn: [linkedin.com/in/sahand-sorouri](https://linkedin.com/in/sahand-sorouri)

## What is in here

| File | What it is |
|------|-------------|
| `Sahand Sorouri - Senior Product Manager.tex` | The LaTeX source of my resume |
| `Sahand Sorouri - Senior Product Manager.pdf` | The compiled resume |
| `resume-template.tex` | A blank version of the same design, with notes, for you to fill in |

## Use it as a template

Start from `resume-template.tex`. It is one self-contained file. Every spot to fill is marked `<<< ... >>>`, and each section has a short comment on what goes there.

It works with any of these fonts and falls back on its own if none are installed: Segoe UI, Bahnschrift, Inter, Carlito, Helvetica Neue, then Latin Modern. So it compiles on any machine.

### Build

You need **XeLaTeX** (the source uses `fontspec`, so pdfLaTeX will not work):

```bash
xelatex resume-template.tex
```

Or [Tectonic](https://tectonic-typesetting.github.io/), which downloads what it needs:

```bash
tectonic resume-template.tex
```

You can also open the `.tex` in [Overleaf](https://www.overleaf.com) and set the compiler to XeLaTeX.

### Make it yours

1. Replace every `<<< ... >>>` placeholder with your own content.
2. Copy the marked employer block for each company, and add or remove `\bulletitem{...}` lines.
3. Wrap any number you want to stand out in `\kpi{...}` (for example `\kpi{+30\%}`).

The styling commands are defined once at the top (`\sectiontitle`, `\majorposition`, `\position`, `\bulletitem`, `\kpi`, `\boxedtext`), so you change content without touching layout.

## Tech

LaTeX with XeLaTeX and `fontspec`.

---

Built by [Sahand Sorouri](https://sahand.sorouri.com) · platforms, bots and AI tools for businesses in Dubai.
