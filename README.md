# LaTeX Resume Template (ATS-friendly)

A clean, one-page(ish) LaTeX resume template designed for readability and ATS compatibility.
Built for students who want a structured resume with consistent formatting.

## Preview
You can compile the `.tex` file to generate a PDF.
(Optional) Add `examples/example-filled.pdf` as a preview for students.

## Files
- `resume.tex` — main template (edit this)
- `examples/example-filled.tex` — filled example (anonymized)
- `examples/example-filled.pdf` — compiled example output (optional)

## How to Use (Fast)
1. Download or clone this repository
2. Open `resume.tex`
3. Replace placeholders with your information
4. Export to PDF

## Compile Options

### Option A — Overleaf (Recommended for beginners)
1. Go to Overleaf and create a new project
2. Upload `resume.tex`
3. Click **Recompile**
4. Download the PDF

### Option B — Local Compile (Mac/Windows/Linux)
Install a LaTeX distribution:
- **TeX Live** (Linux / advanced users)
- **MacTeX** (Mac)
- **MiKTeX** (Windows)

Then compile:
```bash
pdflatex resume.tex
