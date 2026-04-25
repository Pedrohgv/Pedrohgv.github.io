# CV Build Instructions

This directory contains `resume.tex` and the generated `resume.pdf`.

## Option 1: Build with Docker (recommended)

```bash
docker run --rm -v "$PWD/CV:/workdir" -w /workdir danteev/texlive latexmk -pdf -interaction=nonstopmode -halt-on-error resume.tex
```

## Option 2: Build with local TeX installation

Install dependencies (Ubuntu/Debian):

```bash
sudo apt-get update
sudo apt-get install -y latexmk texlive-latex-recommended texlive-fonts-recommended texlive-latex-extra
```

Then compile:

```bash
cd CV
latexmk -pdf -interaction=nonstopmode -halt-on-error resume.tex
```

## Output

- Source: `CV/resume.tex`
- Artifact: `CV/resume.pdf`
