# 📚 Lesson 1.10: Data Visualisation & Storytelling

**Theme:** Making Data Speak — turning numbers into narratives with Python

---

## 📅 Lesson Overview

| Section | Duration | Topic / Activity |
|---------|----------|-----------------|
| **Part 1: Data Storytelling** | 55 min | Perception, Design, and Storytelling pillars; the 3-act structure |
| **Part 2: Matplotlib Fundamentals** | 55 min | Figure → Axes → Plot; customisation; publication-quality charts |
| **Part 3: Seaborn for Statistical Visuals** | 55 min | Distribution plots; categorical plots; faceting |

---

## 🎯 Learning Outcomes

By the end of this lesson, you will be able to:

1. **Apply** the three storytelling pillars (Perception, Design, Storytelling) to evaluate and improve visualisations.
2. **Create** charts using Matplotlib's Figure-Axes-Plot hierarchy with proper customisation.
3. **Use** Seaborn to produce statistical graphics appropriate for different data types and questions.
4. **Select** the right visualisation type for a given analytical context and audience.

---

## 📂 Course Materials

| Material | Description | Est. Time |
|----------|-------------|-----------|
| [Pre-Class](./pre-class.md) | Perception, Design, Storytelling pillars; common chart mistakes | 30–45 min |
| [Lesson Plan](./lesson.md) | Instructor guide for the 3-hour coding session | 3 hours |
| [Assignment](./assignment.md) | Visualisation critique, redesign challenge & self-assessment quiz | 2–3 hours |
| [Reference](./reference.md) | Matplotlib & Seaborn cheat sheet; chart selection guide | As needed |

---

## 🛠️ Tools & Setup

- **[VS Code](https://code.visualstudio.com)** + Python + Jupyter extensions *(recommended)*.
- **[Google Colab](https://colab.research.google.com)** *(alternative)*.
- **Notebook:** `notebooks/data_visualisation_lesson.ipynb` — select the `pds` kernel in VS Code.
- **Environment:** `conda env create -f environment.yml` then `conda activate pds`.
- **Dataset:** Located in `data/` folder within the repository.

---

## Quick Comparison: Matplotlib, Pandas Plotting, Seaborn
| Feature | **Matplotlib** | **Pandas (Built-in Plotting)** | **Seaborn** |
|---------|----------------|--------------------------------|-------------|
| **Core Purpose** | Low-level, foundational Python plotting library; full control over every plot element | High-level plotting **built directly on Matplotlib**; designed for quick visualization of DataFrames/Series | High-level statistical plotting library **built on Matplotlib**; optimized for statistical data & aesthetic plots |
| **Plot Type Focus** | All basic plots (line, bar, scatter, histogram, pie, subplots, custom charts) | Fast, exploratory plots from DataFrames (line, bar, hist, box, area, heatmap) | Statistical plots (boxplot, violinplot, heatmap, pairplot, facetgrid, regression plots) |
| **Ease of Use** | Steeper learning curve; requires manual setup for axes, labels, styling | **Extremely easy**; 1-line plotting from DataFrames (no manual data prep) | Simple syntax; minimal code for beautiful statistical plots |
| **Customization** | **Maximum control** (tweak every pixel: colors, fonts, ticks, layouts, annotations) | Limited built-in customization; can pass Matplotlib arguments for tweaks | Moderate-high; built-in themes + Matplotlib compatibility for full control |
| **Data Input** | Works with lists, arrays, NumPy arrays | **Native DataFrame/Series support** (direct plotting without data conversion) | Works with DataFrames, arrays, lists; optimized for tabular/statistical data |
| **Aesthetics (Default)** | Plain, basic default styles | Basic Matplotlib defaults (simple, functional) | **Beautiful, professional defaults** (themes, color palettes, clean design) |
| **Best For** | Full custom plots, publication-quality figures, complex subplot layouts | Fast exploratory data analysis (EDA), quick DataFrame visualizations | Statistical analysis, correlation plots, categorical data, polished reports |
| **Dependency** | Standalone | Depends on **Matplotlib** | Depends on **Matplotlib + Pandas** |
| **Code Complexity** | Verbose (more lines for full setup) | Minimal (1–2 lines) | Minimal (1–2 lines for statistical plots) |
| **Ideal Use Case** | Custom scientific visualizations, fine-tuned charts | Quick data exploration during data cleaning/analysis | Statistical reporting, EDA with insights, presentation-ready plots |
