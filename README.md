# Python Data Science Cheat Sheet

A complete, self-contained cheat sheet website covering **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn** — from basics to advanced — with specific working code examples for every topic.

## 🚀 Hosting on GitLab Pages

### Option 1: Automatic (CI/CD)
1. Create a new GitLab repository
2. Upload `index.html` and `.gitlab-ci.yml` to the root
3. Push to `main` branch — GitLab automatically deploys
4. Your site goes live at: `https://<your-username>.gitlab.io/<repo-name>/`

### Option 2: Manual
1. Go to your GitLab project → **Settings → Pages**
2. Upload the `index.html` directly

### Verify deployment
- Go to **Deploy → Pages** in your GitLab project sidebar
- The URL appears there once the pipeline succeeds (~1-2 minutes)

## 📁 File Structure

```
.
├── index.html          ← The entire website (single file, no dependencies)
├── .gitlab-ci.yml      ← GitLab Pages CI configuration
└── README.md           ← This file
```

## ✨ Features

- **4 Library tabs** — Pandas, NumPy, Matplotlib, Seaborn
- **Sticky sidebar** with section navigation
- **Search** — filter topics in real time
- **Copy button** on every code block
- **Scroll animations** — cards fade in as you scroll
- **Active link highlighting** — sidebar tracks your position
- **Level badges** — Basic / Intermediate / Advanced
- **Dark theme** — easy on the eyes
- **Zero dependencies** — no npm, no bundler, no external JS required

## 📚 Topics Covered

### Pandas
- Import & Create (DataFrame, Series)
- Read/Write (CSV, Excel, JSON, Parquet, SQL)
- Inspect & Explore (info, describe, nulls, value_counts)
- Select & Filter (loc, iloc, query, boolean masks)
- Clean & Fill (dropna, fillna, ffill, duplicates)
- Transform & Apply (apply, map, np.where, np.select, sort, rank)
- GroupBy & Aggregation (agg, named agg, transform, filter, pivot_table)
- Merge & Join (inner/left/right/outer, concat)
- String Methods (str accessor, regex extract)
- Time Series (date_range, resample, rolling, ewm)
- Advanced (MultiIndex, melt/pivot, chunked reading, pipe)

### NumPy
- Array Creation (zeros, ones, eye, arange, linspace, random)
- Indexing & Reshaping (slice, fancy index, reshape, stack, split)
- Math Operations (element-wise, trig, clip)
- Statistics (sum/mean/std with axis, percentile, histogram)
- Linear Algebra (matmul, inv, det, solve, eig, SVD, QR)
- Advanced (broadcasting, views vs copies, masks)

### Matplotlib
- Setup & Figures (styles, rcParams, subplots)
- Plot Types (line, bar, scatter, histogram, box, violin)
- Styling (annotations, reference lines, twin axes)
- Layouts (GridSpec, tight_layout)
- Advanced (colormaps, 3D plots, animation)

### Seaborn
- Setup & Themes (set_theme, color palettes)
- Distribution (histplot, kdeplot, rugplot, ecdfplot)
- Categorical (boxplot, violinplot, stripplot, barplot)
- Relational (scatterplot, lineplot, regplot, lmplot)
- Matrix Plots (heatmap, pairplot, jointplot)
- Advanced (FacetGrid, figure-level functions, clustermap)

## 🛠 Local Development

No build step required. Just open `index.html` in any browser:

```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Or use Python's built-in server
python3 -m http.server 8000
# then visit http://localhost:8000
```
