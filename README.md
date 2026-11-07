## Project structure

- `data/student_performance.csv` — found in the data folder
- `reports/homework3.qmd` — executable Quarto report.
- `reports/homework3.html` — HTML output accompanying the report.
- `_quarto.yml` — sets execution directory to project root so relative paths work consistently.

## To reproduce this project:

Run from the repository root in an environment with Quarto, Python, NumPy, pandas, and Jupyter available:

```bash
quarto render reports/homework3.qmd
```

### If Quarto is not in installed run the following in your terminal:

wget https://github.com/quarto-dev/quarto-cli/releases/download/v1.10.19/quarto-1.10.19-linux-amd64.deb

then:

sudo apt-get install -y ./quarto-1.10.19-linux-amd64.deb

Check the installation by running:

quarto --version



