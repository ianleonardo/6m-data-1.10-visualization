# PART A: ESSENTIAL PRE-CLASS (30 minutes)
## ⏱️ Quick Foundation Before Lesson 1.10

⏱️ **Estimated Duration:** 30 minutes
**Prerequisites:** Lesson 1.9 — Advanced EDA

> In Lesson 1.9 you transformed and aggregated data using groupby, pivot, melt, and time-series resampling. Now you'll learn how to *communicate* those findings visually. Data visualisation is where analysis becomes a story — this pre-class work gives you the design vocabulary to make that story clear and honest.

**Goal:** Build core vocabulary and concepts before working through the Python tools. No deep dives — just enough to understand *why* design choices matter.

**🎬 Watch This Video:** [The Architecture of Insight Data Visualisation & Storytelling](https://www.youtube.com/watch?v=-SaBG0sEtRA)

---

## A.1: The Three Pillars of Visualization (10 mins)

### 🧠 Pillar 1: PERCEPTION (How Humans See)

**Key Concept: Pre-attentive Processing**
- Your brain processes important visual elements in **200-500 milliseconds** (before you consciously "look")
- Important insights should **jump out** without effort
- Example: A red bar among gray bars catches your eye instantly

**Key Concept: Cognitive Load**
- Working memory can only hold **4-7 items** at once
- Remove clutter; highlight only what matters
- Result: Viewers understand faster with less frustration

**What to watch for in the lesson:** When you see code that removes gridlines, limits colors, or reorganizes subplots — that's cognitive load management being applied in Python.

---

### 🎨 Pillar 2: DESIGN (How to Show Data Honestly)

**Chart Selection Rule:**
| Goal | Chart | Why |
|------|-------|-----|
| Compare categories | Bar chart | Lengths are easy to compare |
| Show trends over time | Line chart | Continuity shows flow |
| Show correlation | Scatter plot | Position reveals relationships |
| Show distribution | Box/Violin plot | Reveals median, quartiles, outliers |

**The Golden Rule of Honest Visualization:**
❌ **NEVER:** Truncate bar chart axes (start anywhere but 0)  
✅ **ALWAYS:** Bar charts must start at 0 for accurate magnitude comparison

**Why?** Truncating distorts relative sizes and misleads viewers.

---

### 📖 Pillar 3: STORYTELLING (How to Communicate)

**Three-Act Structure:**
```
ACT 1: BEGINNING (Set Context)
  ↓ "Why should you care?"
ACT 2: MIDDLE (Show Problem/Opportunity)  
  ↓ "What does the data reveal?" (Use visualization here)
ACT 3: END (Propose Action)
  ↓ "What should we do next?"
```

**Example:**
- **Act 1:** "Our sales grew 15%, BUT customer retention dropped 8%"
- **Act 2:** "Analysis shows the loss concentrates in high-value customers"
- **Act 3:** "Let's implement a retention program targeting them"

---

## A.2: Common Mistakes to Avoid (10 mins)

**Mistake 1: Wrong Chart Type**
- ❌ Using pie charts with 10+ slices (hard to compare)
- ✅ Use bar chart instead

**Mistake 2: Truncated Axes**
- ❌ Bar chart Y-axis: 95-100% (exaggerates tiny differences)
- ✅ Start at 0; if you must truncate, clearly mark it

**Mistake 3: Too Much Color**
- ❌ Using 8+ colors in one chart (overwhelming)
- ✅ Limit to 3-5 colors max

**Mistake 4: No Story**
- ❌ Just showing a chart without explanation
- ✅ Frame data in narrative: "Here's the problem, here's what it means, here's what to do"

**Mistake 5: Forgetting Your Audience**
- ❌ Same message for executives and data scientists
- ✅ Executives care about ROI; Data scientists care about methodology

---

## A.3: Know Your Audience (10 mins)

**Different audiences need different messages:**

| Audience | Cares About | Your Message | Detail Level |
|----------|-------------|--------------|--------------|
| **Executive** | ROI, decision | "Impact on business, here's the choice" | High-level only |
| **Manager** | Implementation | "This is what to do, here's the impact" | Key drivers highlighted |
| **Data Team** | Methodology | "Here's how I analyzed it" | Full technical details |
| **General Public** | Relevance, clarity | "Why it affects you, here's the key insight" | Simple, no jargon |

**Before class:** Ask yourself: "Who are we talking to? What do they care about?"

---

## ✅ Pre-Class Checklist (5 mins)

Before moving on, can you answer these?

- [ ] What is pre-attentive processing? Why does it matter?
- [ ] Name 2 mistakes that make visualizations misleading
- [ ] What's the difference between a bar chart and a line chart?
- [ ] Describe the three-act storytelling structure
- [ ] How does your message change for different audiences?

<details>
<summary>💡 Suggested Answers</summary>

**Pre-attentive processing:** Your brain spots certain visual signals (colour, position, size) in 200–500 milliseconds — before you consciously look. It matters because insights that rely on pre-attentive attributes (e.g. a red bar among grey ones) are understood instantly, while insights buried in a table or a crowded chart require deliberate effort and may be missed entirely.

**Two mistakes that make visualisations misleading:**
1. Truncating a bar chart's y-axis (e.g. starting at 95 instead of 0) — makes tiny differences look dramatic.
2. Using a 3D chart — the perspective distorts perceived area/angle and makes accurate comparison impossible.

**Bar chart vs line chart:** A bar chart shows discrete, separate categories (e.g. sales per product). A line chart shows a continuous trend over time (e.g. daily revenue). Using a line chart for unrelated categories implies a connection that doesn't exist.

**Three-act structure:** Act 1 — set the context ("why should you care?"). Act 2 — reveal the data insight using a visualisation. Act 3 — propose an action ("what should we do?"). The visualisation usually lives in Act 2 as the evidence behind the argument.

**Audience-adjusted messaging:**
- Executive → ROI and the decision to make (high-level only).
- Manager → specific actions and key drivers.
- Data team → full methodology and data quality details.
- General public → simple language, no jargon, personal relevance.

</details>

**Missed some?** Skim that section again — it will make the Python lesson much more meaningful.

---

## 🎯 How This Connects to the Python Lesson

In Lesson 1.10 you'll work with **Matplotlib** and **Seaborn** — the two most widely used Python visualisation libraries. The principles you just reviewed are the *why* behind every code decision:

- Choosing `plt.bar()` vs `plt.plot()` — that's the chart selection rule.
- Calling `ax.grid(False)` or limiting the colour palette — that's cognitive load management.
- Writing a descriptive title and annotation — that's storytelling.

When you understand the principle, the code becomes a tool rather than a mystery. You're ready to begin.

---


### Useful Links

- [Data Visualization Introduction](https://www.tableau.com/learn/articles/data-visualization)
- [10 Best Data Visualization Examples from History & Today](https://www.tableau.com/learn/articles/best-beautiful-data-visualization-examples)
- [Best Practices for Effective Data Visualization](https://www.thoughtspot.com/data-trends/data-visualization/best-practices-and-tips-for-effective-data-visualization)
