# LaTeX CV

The one-page CV I use for internship applications, written in LaTeX. The repository holds two templates: the original one and an updated one. Fork it, pick a template and replace the content with your own.

[Version française plus bas](#cv-latex-en-français)

## Templates

| Folder | What it is |
| --- | --- |
| `template-1/` | Original template (current CV) |
| `template-2/` | Updated template, built from a new resume (in progress) |
| `temp/` | Local scratch folder, git-ignored (source resumes, drafts) |

### `template-1/`

| Path | What it is |
| --- | --- |
| `template/main.tex` | Blank template with placeholders, start here |
| `my-cv/Marsel_Bakashov_CV_EN/main.tex` | My English CV |
| `my-cv/Marsel_Bakashov_CV_FR/main.tex` | My French CV |
| `my-cv/Marsel_Bakashov_CV_*.pdf` | Compiled PDFs of my two CVs |

## Layout

- Single page, A4, Roboto font, FontAwesome icons.
- Two-column summary and skills block, then education, experience, projects and activities in a `tabularx` grid.
- Section headings use one `\sechead{...}` macro, so the rules always end at the right margin.
- Plain text is extractable from the PDF, which helps applicant tracking systems.

## Build

You need a LaTeX distribution with the `roboto` and `fontawesome5` packages (MiKTeX and TeX Live both have them).

```bash
cd template-1/template
pdflatex main.tex
```

You can also upload the folder to [Overleaf](https://www.overleaf.com) and compile `main.tex` there.

## Reuse

1. Fork or clone the repository.
2. Copy `template-1/template/` (or another template folder), then in its `main.tex`, replace the name, contact details, and the About, Skills, Education, Experience, Projects and Activities content.
3. Remove any section you do not need.
4. Recompile and check that the result still fits on one page.

## License

MIT License.

---

# CV LaTeX en français

Le CV d'une page que j'utilise pour mes candidatures de stage, écrit en LaTeX. Le dépôt contient deux templates : l'original et une version mise à jour. Faites-en une copie, choisissez un template et remplacez le contenu par le vôtre.

## Templates

| Dossier | Description |
| --- | --- |
| `template-1/` | Template original (CV actuel) |
| `template-2/` | Template mis à jour, construit à partir d'un nouveau CV (en cours) |
| `temp/` | Dossier de travail local, ignoré par git (CV sources, brouillons) |

### `template-1/`

| Chemin | Description |
| --- | --- |
| `template/main.tex` | Template vide avec des placeholders, point de départ |
| `my-cv/Marsel_Bakashov_CV_EN/main.tex` | Mon CV en anglais |
| `my-cv/Marsel_Bakashov_CV_FR/main.tex` | Mon CV en français |
| `my-cv/Marsel_Bakashov_CV_*.pdf` | PDF compilés de mes deux CV |

## Compilation

Il faut une distribution LaTeX avec les paquets `roboto` et `fontawesome5` (MiKTeX et TeX Live les incluent).

```bash
cd template-1/template
pdflatex main.tex
```

Le dossier peut aussi être importé dans [Overleaf](https://www.overleaf.com).

## Réutilisation

1. Copiez ou clonez le dépôt.
2. Copiez `template-1/template/` (ou un autre dossier de template), puis dans son `main.tex`, remplacez le nom, les coordonnées et le contenu de chaque section.
3. Supprimez les sections inutiles.
4. Recompilez et vérifiez que le CV tient toujours sur une page.

## Licence

Licence MIT.
