# The Mathematics Behind ML/AI — A Weighted Map

**→ [enkodprime.github.io/ml-math-map](https://enkodprime.github.io/ml-math-map/)**

An interactive, bilingual (EN / БГ) map of the mathematics that actually carries
weight in machine learning. One self-contained HTML file — no build step, no
dependencies, no network calls.

## What is in it

- **88 mathematical topics**, each weighted 1–10 by how often it shows up in real
  ML/AI work: reading papers, reading model code, debugging a training run.
  Weight is not difficulty — the definite integral is weight 7 but easier than
  SVD at weight 8.
- **A radial map** of eight branches — linear algebra, calculus, optimization,
  probability, statistics, information theory, discrete math, geometry &
  numerics. Radius encodes weight: 10 at the centre, 1 at the rim. The thin arcs
  are prerequisites, so the map doubles as a study order.
- **Per topic:** the formula, a symbol-by-symbol table, a worked numeric example,
  an illustration, and an ego graph of the ML/AI concepts that lean on it.
- **70 ML/AI concepts** in 8 groups, clickable in reverse: pick a concept and see
  the mathematics it needs, ordered by how central each piece is.
- **A 64-entry symbol glossary** — click any sign for how it is read, what it
  means, an example and a diagram.
- **EN / БГ switch**, light and dark themes, keyboard accessible, works on
  phones.

## Where to start

Work outward from the centre of the map: vectors → matrix multiplication → dot
product and norms → partial derivatives → gradient → chain rule → expectation →
distributions → maximum likelihood → cross-entropy. Those ten unlock roughly 80%
of ML paper reading.

## Local viewing

Open `index.html` in any browser. `file://` is fine — there is nothing to serve.

## Deployment

GitHub Pages serves the repository root from `main` — Settings → Pages →
Source: *Deploy from a branch* → `main` / `(root)`. `.nojekyll` keeps Jekyll
from touching the file. Any push to `main` republishes it.

---

Author: **EnkodPrime**
