# 📚 Lesson 1.10: Data Visualisation & Storytelling

## Session Overview

| | |
|---|---|
| **Duration** | 3 hours |
| **Format** | Flipped Classroom + Guided Coding in Jupyter |
| **Tools** | VS Code + `pds` conda environment |
| **Notebook** | `notebooks/data_visualization_lesson.ipynb` |

## Agenda

| Time | Part | Topic |
|------|------|-------|
| 0:00 – 0:40 | Part 1 | Data Storytelling — Conceptual (Slides + Discussion) |
| 0:40 – 2:30 | Part 2 | Data Visualisation in Python — Hands-On (Notebook Code-Along) |
| 2:30 – 3:00 | Part 3 | Applied Examples — Real-world scenarios + Wrap-Up |

## 🎯 Learning Objectives

By the end of this session, you will be able to:

1. Apply the three storytelling pillars (Perception, Design, Storytelling) to evaluate and improve visualisations.
2. Create charts using Matplotlib's Figure-Axes-Plot hierarchy with proper customisation.
3. Use Seaborn to produce statistical graphics appropriate for different data types and questions.
4. Select the right visualisation type for a given analytical context and audience.

---

## Before You Start

**Have you completed Part A (Essential Pre-Class)?**
- ✓ Understand the 3 pillars: Perception, Design, Storytelling
- ✓ Know the golden rule (bar charts start at 0)
- ✓ Review common mistakes to avoid
- ✓ Consider: Who is your audience?

If not, please review the [Pre-Class Guide](./pre-class.md) before continuing (30 minutes).

**Technical Setup:**
- Conda environment: `pds`
- Notebook file: `notebooks/data_visualization_lesson.ipynb`
- Open in VSCode and select the `pds` kernel

---

## 🏃 Part 1: Data Storytelling (30–40 min)

**Format:** Slides + Discussion

### What you'll learn

- Why storytelling matters in data visualisation
- The three-act structure applied to data
- How to choose what to visualise (context, problem, action)
- Connecting audience to outcome

### During this part

- Follow along with the slides and examples
- Think about: "What story am I trying to tell?"
- Notice: How does the narrative frame the data?

### 💬 Discussion Questions

- How does framing data as a story change the way an audience interprets it?
- Think of a visualisation you've seen recently — what was the intended message? Did the design support it?

---

## 🏃 Part 2: Data Visualisation in Python (60–90 min)

**Format:** Code-Along in Notebook

Open `notebooks/data_visualization_lesson.ipynb`.

> Code along with the instructor — don't just watch. Try modifying parameters to see what changes, and connect each visualisation back to the principles from Part 1.

### Notebook Sections

**1. Setup & Imports** — Understanding the visualisation stack

**2. Matplotlib Primer** — Basic structure (Figure → Axes → Plot)
- Creating figures and axes
- Line plots, bar charts, scatter plots
- Titles, labels, legends

**3. Seaborn Fundamentals** — Statistical visualisation patterns
- Distribution plots (histplot, boxplot, violinplot)
- Categorical plots (barplot, countplot, stripplot)
- Relational plots (scatterplot, lineplot)

**4. Applied Examples** — Real-world visualisation scenarios
- "Why did we choose a bar chart here?"
- "How does color help pre-attentive processing?"
- "What story does this visualisation tell?"

**5. Customisation & Polish** — Making publication-quality plots
- Figure sizing and DPI
- Color palettes and themes
- Annotations and callouts

---

## 🏃 Part 3: Applied Examples & Wrap-Up (30 min)

Continue in the notebook with the applied examples section.

### 💬 Reflection Questions

- When would you choose Seaborn over Matplotlib? When would you use both together?
- What visualisation would you use to show: (a) the distribution of salaries, (b) how sales changed over 12 months, (c) the relationship between height and weight?
- How do the Perception, Design, and Storytelling pillars show up in the charts you built today?

---

## 🎯 Wrap-Up

**Key Takeaways:**
1. A good visualisation starts with a clear question — "What am I trying to show?" — before touching any code.
2. Matplotlib gives you control; Seaborn gives you speed for statistical graphics. Use both.
3. Perception principles (pre-attentive attributes, colour, alignment) are not just aesthetics — they determine whether your audience understands your chart in 5 seconds or misreads it entirely.

**Next Steps:**
- Complete the [Assignment](./assignment.md) — visualisation critique, redesign challenge & self-assessment quiz.
- Reference the [Reference Sheet](./reference.md) for Matplotlib & Seaborn cheat sheets and a chart selection guide.
