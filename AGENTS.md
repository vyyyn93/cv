# Repository guidance

- This repository contains one CV project: `cv_data_engineer/`. Its LaTeX source is `cv_data_engineer/main.tex`; image paths such as `assets/photo.JPG` are relative to that directory.
- Build from `cv_data_engineer/` with `latexmk -pdf -outdir=build main.tex`. The generated build files belong in `build/` (ignored by the project's `.gitignore`). The deliverable PDF at `cv_data_engineer/main.pdf` is tracked; copy the rebuilt `build/main.pdf` there when a CV change should update the deliverable.
- The project uses pdfLaTeX/Helvetica and has no repository-defined test, lint, or CI workflow. Check the compiled PDF visually and extract its text (for example, with `pdftotext`) after edits; a successful LaTeX compile alone will not catch layout or reading-order problems.
- Keep resume facts in `main.tex` accurate and consistent with the PDF. Research/session Markdown files are working notes, not CV content; don't copy unverified plans, estimates, or future milestones into the CV as completed results.
