# Sahand Sorouri — Senior Product Manager Resume

My resume, written in LaTeX. Senior Product Manager and AI builder with 7 years across marketplaces, fintech and real estate, based in Dubai.

[**Download the PDF**](Sahand%20Sorouri%20-%20Senior%20Product%20Manager.pdf)

- Portfolio: [sahand.sorouri.com](https://sahand.sorouri.com)
- LinkedIn: [linkedin.com/in/sahand-sorouri](https://linkedin.com/in/sahand-sorouri)
- Email: hi@sorouri.com

## What is in here

| File | Description |
|------|-------------|
| `Sahand Sorouri - Senior Product Manager.tex` | The LaTeX source of my resume |
| `Sahand Sorouri - Senior Product Manager.pdf` | My compiled resume |
| `resume-template.tex` | A blank version of the same design, with inline instructions, for you to fill in |

## Use it as a template

Start from `resume-template.tex`. It is a single, self-contained file with the same design as my resume, but every spot you need to fill is marked `<<< ... >>>` and each section has a short comment explaining what goes there.

It works with any of these fonts and falls back automatically if none are installed: Segoe UI, Bahnschrift, Inter, Carlito, Helvetica Neue, and finally Latin Modern. So it compiles cleanly on any machine.

### Build it

You need a LaTeX setup with **XeLaTeX** (the source uses `fontspec`, so pdfLaTeX will not work).

```bash
xelatex resume-template.tex
```

Or with [Tectonic](https://tectonic-typesetting.github.io/), which downloads what it needs on its own:

```bash
tectonic resume-template.tex
```

You can also drop the `.tex` into [Overleaf](https://www.overleaf.com) and set the compiler to XeLaTeX.

### Make it yours

1. Replace every `<<< ... >>>` placeholder with your own content.
2. Copy the marked employer block for each company, and add or remove `\bulletitem{...}` lines as needed.
3. Wrap any metric you want to emphasize in `\kpi{...}` (for example `\kpi{+30\%}`).

The styling commands are defined once at the top (`\sectiontitle`, `\majorposition`, `\position`, `\bulletitem`, `\kpi`, `\boxedtext`), so you change content without touching layout.
