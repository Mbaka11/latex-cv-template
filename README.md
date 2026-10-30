# LaTeX CV

The one-page CV I use for internship applications, written in LaTeX. Fork it and replace the content with your own to reuse the layout.

[Version française plus bas](#cv-latex-en-français)

## Contents

| Path | What it is |
| --- | --- |
| `Marsel_Bakashov_CV_EN/main.tex` | English CV |
| `Marsel_Bakashov_CV_FR/main.tex` | French CV |
| `Marsel_Bakashov_CV_FR_La_Caisse_Quant/main.tex` | French variant tailored to quantitative finance |
| `Marsel_Bakashov_CV_*.pdf` | Compiled PDFs of the three versions |
| `CV_REVISION_NOTES.md` | Working notes on wording choices and open items |

## Layout

- Single page, A4, Roboto font, FontAwesome icons.
- Two-column summary and skills block, then education, experience, projects and activities in a `tabularx` grid.
- Section headings use one `\sechead{...}` macro, so the rules always end at the right margin.
- Plain text is extractable from the PDF, which helps applicant tracking systems.

## Build

You need a LaTeX distribution with the `roboto` and `fontawesome5` packages (MiKTeX and TeX Live both have them).

```bash
cd Marsel_Bakashov_CV_EN
pdflatex main.tex
```

You can also upload the folder to [Overleaf](https://www.overleaf.com) and compile `main.tex` there.

## Reuse

1. Fork or clone the repository.
2. In `main.tex`, replace the name, contact details, and the About, Skills, Education, Experience, Projects and Activities content.
3. Remove any section you do not need.
4. Recompile and check that the result still fits on one page.

## License

MIT License.

---

# CV LaTeX en français

Le CV d'une page que j'utilise pour mes candidatures de stage, écrit en LaTeX. Faites-en une copie et remplacez le contenu par le vôtre pour réutiliser la mise en page.

## Contenu

| Chemin | Description |
| --- | --- |
| `Marsel_Bakashov_CV_EN/main.tex` | CV en anglais |
| `Marsel_Bakashov_CV_FR/main.tex` | CV en français |
| `Marsel_Bakashov_CV_FR_La_Caisse_Quant/main.tex` | Variante française orientée finance quantitative |
| `Marsel_Bakashov_CV_*.pdf` | PDF compilés des trois versions |
| `CV_REVISION_NOTES.md` | Notes de travail sur la rédaction et les points à confirmer |

## Compilation

Il faut une distribution LaTeX avec les paquets `roboto` et `fontawesome5` (MiKTeX et TeX Live les incluent).

```bash
cd Marsel_Bakashov_CV_FR
pdflatex main.tex
```

Le dossier peut aussi être importé dans [Overleaf](https://www.overleaf.com).

## Réutilisation

1. Copiez ou clonez le dépôt.
2. Dans `main.tex`, remplacez le nom, les coordonnées et le contenu de chaque section.
3. Supprimez les sections inutiles.
4. Recompilez et vérifiez que le CV tient toujours sur une page.

## Licence

Licence MIT.
