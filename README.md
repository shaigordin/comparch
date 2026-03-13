# Shape in Time: Geometric Morphometrics for Archaeologists

**צורה בזמן: מורפומטריה גיאומטרית לארכאולוגים**

A 12-week undergraduate course in geometric morphometrics for archaeology students, taught in Hebrew at Ariel University. The course requires no prior coding experience and runs entirely in Google Colab (Python).

**Instructor:** Shai Gordin | Ariel University
**Branch:** [`2026`](https://github.com/shaigordin/comparch/tree/2026) | **Live site:** [shaigordin.github.io/comparch](https://shaigordin.github.io/comparch)

---

## Repository Structure

```
morphometrics/
├── _quarto.yml          # Quarto site configuration
├── index.qmd            # Course homepage
├── syllabus.qmd         # Full 12-week syllabus
├── resources.qmd        # Tools, readings, datasets
├── modules/             # 12 weekly module pages
│   ├── 01-what-is-shape.qmd
│   ├── 02-data-collection.qmd
│   ├── 03-ai-coding.qmd
│   ├── 04-procrustes.qmd
│   ├── 05-pca.qmd
│   ├── 06-coins.qmd
│   ├── 07-outlines-theory.qmd
│   ├── 08-axes.qmd
│   ├── 09-statistics.qmd
│   ├── 10-pottery.qmd
│   ├── 11-3d.qmd
│   └── 12-big-questions.qmd
├── slides/              # 12 Reveal.js slide decks
├── assignments/         # 5 graded assignments + final project
└── data/                # Dataset index and access instructions
```

---

## Datasets Used

### 1. Roman Denarii (Coins)
- **Contents:** 20 Hadrian + 15 Antoninus Pius denarii, 8 landmarks each, TPS format
- **Location:** `morphometrics/data/coins/`
- **Course use:** Modules 5–7 (GPA, PCA, shape space)
- **Rights:** Teaching dataset compiled for this course. If you use this dataset in your own work, please contact the instructor.

### 2. European Bronze Age Flanged Axes
- **Contents:** ~65 axe silhouettes (G3 and G4 typological groups), TIF images + TPS landmark files + EFA coefficient files
- **Location:** `morphometrics/data/flanged_axes/`
- **Course use:** Modules 8–9 (EFA, outline analysis, geographic distribution)
- **Source:** Digitized from published typological corpora. Original images © respective rights holders. Dataset compiled for educational use under fair use / teaching exemption.
- **Rights:** Please contact the instructor before redistributing.

### 3. Ogame Pottery — Loftus (2025)
- **Contents:** 243 Ogame jar silhouette profiles from Kyushu, Japan (kiln vs. burial contexts), Edo period (1600–1800 CE)
- **Location:** Downloaded directly from Zenodo in student notebooks
- **Zenodo DOI:** [10.5281/zenodo.15781166](https://doi.org/10.5281/zenodo.15781166)
- **Citation:**
  > Loftus, J. (2025). *Geometric morphometric data for Japanese Ogame jars*. Journal of Open Archaeology Data, 13, 13. https://doi.org/10.5334/joad.159
- **License:** CC BY 4.0 — free to reuse with attribution.

---

## Software & Tools

| Tool | Purpose | License |
|------|---------|---------|
| [Quarto](https://quarto.org) | Course website | MIT |
| [Google Colab](https://colab.research.google.com) | Student coding environment | Free |
| [morphops](https://github.com/vaipatel/morphops) | GPA, thin-plate splines | MIT |
| [pyefd](https://github.com/hbldh/pyefd) | Elliptic Fourier Descriptors | MIT |
| [scikit-learn](https://scikit-learn.org) | PCA, statistics | BSD-3 |
| [scikit-image](https://scikit-image.org) | Image processing / outline extraction | BSD-3 |
| [python-bidi](https://github.com/MeirKriheli/python-bidi) | RTL text rendering in matplotlib | LGPL |
| [FIJI / ImageJ](https://fiji.sc) | Landmark digitizing (Week 3 only) | GPL-2 |

---

## Key References

### Foundational Texts

Zelditch, M. L., Swiderski, D. L., & Sheets, H. D. (2012). *Geometric Morphometrics for Biologists: A Primer* (2nd ed.). Academic Press.

Bookstein, F. L. (1991). *Morphometric Tools for Landmark Data: Geometry and Biology*. Cambridge University Press.

Slice, D. E. (Ed.). (2005). *Modern Morphometrics in Physical Anthropology*. Kluwer Academic / Plenum Publishers.

### Methods Papers

Rohlf, F. J., & Slice, D. (1990). Extensions of the Procrustes method for the optimal superimposition of landmarks. *Systematic Zoology*, 39(1), 40–59. https://doi.org/10.2307/2992207

Kuhl, F. P., & Giardina, C. R. (1982). Elliptic Fourier features of a closed contour. *Computer Graphics and Image Processing*, 18(3), 236–258. https://doi.org/10.1016/0146-664X(82)90034-X

Bonhomme, V., Picq, S., Gaucherel, C., & Claude, J. (2014). Momocs: Outline Analysis Using R. *Journal of Statistical Software*, 56(13), 1–24. https://doi.org/10.18637/jss.v056.i13

### Archaeological Applications

Lycett, S. J., & von Cramon-Taubadel, N. (2013). A 3D morphometric analysis of surface geometry in Levallois cores. *Journal of Archaeological Science*, 40(4), 1928–1935.

Selden, R. Z., Dockall, J. E., & Shafer, H. J. (2018). Lithic morphological organisation: Gahagan bifaces from the Southern Caddo Area. *Digital Applications in Archaeology and Cultural Heritage*, 10, e00080.

---

## Course Citation

If you adapt or build on these materials, please cite:

> Gordin, S. (2026). *Shape in Time: Geometric Morphometrics for Archaeologists* [Course materials]. Ariel University. https://github.com/shaigordin/comparch

---

## License

**Course materials** (text, exercises, slide content):
© Shai Gordin, Ariel University, 2026. All rights reserved.
Contact the instructor for permission to adapt or redistribute.

**Code examples** in module notebooks:
Released under [MIT License](https://opensource.org/licenses/MIT) — free to reuse and adapt with attribution.

**Datasets**: See individual dataset rights statements above.

---

## Contact

**Shai Gordin** | Department of Land of Israel Studies and Archaeology, Ariel University
GitHub: [@shaigordin](https://github.com/shaigordin)
