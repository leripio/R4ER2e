# R for Economic Research <img src="images/cover.png" align="right" height="300"/>

**R for Economic Research** is a practical guide that teaches essential tools for data analysis and modeling in economics using the R programming language. The book is aimed at economists, researchers, and data professionals who want to enhance their analytical skills using open-source tools.

---

## 📦 Companion Package

All datasets used in the book are available in the R package [`R4ER2data`](https://github.com/leripio/R4ER2data).

You can install it directly from GitHub:

```r
install.packages(
  "https://github.com/leripio/R4ER2data/releases/download/v1.0.0/R4ER2data_1.0.0.tar.gz",
  repos = NULL,
  type = "source"
)
```

---

## 🔄 Reproducibility

This project uses the [`renv`](https://rstudio.github.io/renv/) package to manage the R package environment (see the `renv.lock` file in the repo).  
To reproduce the exact environment used in the book, you can run:

```r
renv::restore()
```

This will install all required packages with the correct versions as used in the code examples.

---

## 📖 License and Contributions

This project is open for contributions and feedback.  
For licensing information, see the [LICENSE](LICENSE) file.

---
