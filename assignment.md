# PART B: POST-CLASS PRACTICE (2-3 hours)
## 📋 Apply, Practice, Assess

> ⏱️ **Estimated Time:** 2–3 hours | Complete this **after** working through the Lesson 1.10 notebook.

**Goal:** Deepen learning through exercises, real-world application, and self-assessment.

---

## B.1: Learning Consolidation Exercises (30 mins)

### Exercise B.1.1: Design Principles in the Wild
**Task:** Find a visualization in news/reports (takes 5 mins)

Analyze it:
1. **What chart type is used?** Is it the right choice?
2. **Does it follow the golden rule?** (Axes start at zero? Colors intentional?)
3. **Who is the audience?** What message is it trying to send?
4. **What would you improve?** List 2-3 changes

**Example:**
- Chart type: Pie chart with 12 slices (PROBLEM: hard to compare angles)
- Improvement: Use horizontal bar chart instead
- Audience: General public (therefore: remove jargon, add simple title)

---

### Exercise B.1.2: Three-Act Storytelling
**Task:** Take a dataset or finding you have (10 mins)

Structure it as a story:
- **Act 1 (Context):** What's the business/research context?
- **Act 2 (Problem/Opportunity):** What does your analysis reveal?
- **Act 3 (Action):** What should someone do with this insight?

**Example:** 
- "Quarterly revenue data shows growth slowing"
- "Analysis reveals 60% of decline comes from one customer segment"
- "Recommendation: Launch targeted retention program in that segment"

---

### Exercise B.1.3: Audience Pivot
**Task:** Take the story from B.1.2 (10 mins)

Tell it **three different ways** for three audiences:
1. **For an Executive:** Focus on ROI and decision path
2. **For a Manager:** Focus on specific action items
3. **For the Data Team:** Focus on methodology and data quality

Notice how the *data stays the same*, but *message changes* per audience.

---

## B.2: Real-World Application (60 mins)

### B.2.1: Critique Real Visualizations from Your Field

Find 3 visualizations from:
- Industry reports in your sector
- News articles on topics you care about
- Company/organizational dashboards
- Academic papers in your domain

For each, write a brief critique:
- **What works?** (Follows principles; clear story; appropriate audience)
- **What doesn't?** (Misleading, confusing, wrong chart type)
- **How would you improve it?**

**Sample critique:**
```
Visualization: Sales revenue by region (pie chart)
What works: Bright, eye-catching; shows total revenue in title
Doesn't work: Pie charts with 8+ slices are hard to compare
Improvement: Horizontal bar chart, sorted high→low, 
             with values labeled on bars
```

---

### B.2.2: Redesign Exercise

Pick ONE visualization from B.2.1 that could be improved.

Create a **written redesign proposal** (15-20 mins):
1. **Original problem:** What's confusing/misleading about current viz?
2. **Why the change:** Which principle does it violate?
3. **New design:** Describe your improved version
4. **Expected outcome:** How will viewers better understand?

This is what you'll do with Python code during future lessons.

---

## B.3: Self-Assessment Quiz (30 mins)

Answer these questions to gauge your understanding:

### Knowledge Questions

**Q1: Perception**
*Pre-attentive processing happens in what timeframe?*

A) 1-2 seconds
B) 200-500 milliseconds
C) 5-10 seconds
D) Instantly

<details>
<summary>💡 Answer</summary>

**B) 200–500 milliseconds.** Pre-attentive processing happens faster than conscious thought — your brain detects colour, size, and position differences before you deliberately look for them. Designing for this means key insights jump out without effort.

</details>

---

**Q2: Design — Chart Selection**
*When comparing values across categories, which chart is best?*

A) Pie chart
B) Line chart
C) Bar chart
D) Scatter plot

<details>
<summary>💡 Answer</summary>

**C) Bar chart.** Humans compare lengths far more accurately than angles (pie) or positions along a curve (line). Bar charts are the default for category comparisons.

</details>

---

**Q3: Design — Honest Visualisation**
*True or False: It's okay to truncate bar chart axes if it makes the chart fit better.*

A) True
B) False

<details>
<summary>💡 Answer</summary>

**B) False.** Bar charts must start at zero because the visual message is encoded in *length*. Truncating the axis (e.g. starting at 95 instead of 0) makes small differences look enormous and actively misleads viewers about relative magnitudes.

</details>

---

**Q4: Storytelling — Three Acts**
*Which act typically contains the visualisation?*

A) Act 1 (Beginning)
B) Act 2 (Middle)
C) Act 3 (End)
D) All acts

<details>
<summary>💡 Answer</summary>

**B) Act 2 (Middle).** The visualisation is the *evidence* for your argument. Act 1 sets the context so viewers care; Act 2 reveals what the data shows; Act 3 proposes action based on that evidence.

</details>

---

**Q5: Audience**
*If presenting to an executive, you should emphasise:*

A) Detailed methodology
B) Technical data quality issues
C) Business impact and decision path
D) All data points equally

<details>
<summary>💡 Answer</summary>

**C) Business impact and decision path.** Executives need enough to make a decision — not the technical details. Lead with the bottom-line insight, then briefly state what action it implies.

</details>

---

### Application Questions

**Q6: Scenario**
You're showing a chart revealing that customer churn increased in Q4. Your audience is a regional manager. What should your message emphasise?

<details>
<summary>💡 Expected Answer</summary>

Focus on **specific actions they can take** to address churn in their region, clear metrics showing the scale of the impact, and a realistic timeline for implementation. Avoid raw methodology — managers need the "what to do" more than the "how you calculated it".

</details>

---

**Q7: Critique**
Look at this chart description: "A 3D pie chart comparing market share of 15 companies." What principle violations do you spot?

<details>
<summary>💡 Expected Answer</summary>

- **3D distorts angles** — perspective makes slices at the back appear smaller than slices at the front even when they have the same value (visual integrity violation).
- **15 slices are impossible to distinguish** — humans can only accurately compare about 5–7 items (cognitive load violation).
- **Recommended fix:** Replace with a horizontal bar chart, sorted high → low, with values labelled on each bar.

</details>

---

### Scoring

**6–7 correct:** Excellent foundation. Ready for advanced practice.
**4–5 correct:** Good understanding. Review the sections you missed before moving on.
**< 4 correct:** Re-read Part A carefully, focusing on the concepts you found hardest.

---

## B.4: Reflection & Integration (30 mins)

### Reflection Prompt

Write 200–300 words on — or share your thoughts in the **#peer-reviews** Discord channel:

**"How will I use these visualisation principles in my work?"**

Consider:
- Your field/industry
- Types of data you typically work with
- Audiences you present to
- Common mistakes you've seen
- One principle you'll prioritize

### Integration Exercise

Review your Python code from today's lesson. For ONE visualization you created:

1. **Identify the principle:** Which visualization principle did you implement?
   - Example: "I reduced cognitive load by removing gridlines"
   
2. **Explain the choice:** Why did you make that code decision?
   - Example: "plt.grid(False) because the gridlines competed with the data"
   
3. **Consider audience:** How would you adjust the visualization for different audiences?
   - Example: "For an executive, I'd add a title explaining the business implication"

This bridges theory (Part A/B) to practice (Python code).

---

## ✅ Post-Class Completion Checklist

After completing Part B:

- [ ] Completed Exercise B.1 (design analysis, storytelling, audience pivot)
- [ ] Completed Exercise B.2 (real-world critiques, redesign proposal)
- [ ] Scored 4+ on B.3 quiz (self-assessment)
- [ ] Completed reflection exercise (B.4)
- [ ] Can explain 3 visualization principles to a colleague
- [ ] Can identify violations of design principles in real charts
- [ ] Can structure a data insight using three-act narrative

**Checked all boxes?** You've integrated the theory into practice. ✓

Share your critique from B.2 or your reflection from B.4 in **#peer-reviews** on Discord to get feedback from fellow learners. For questions, post in **#questions**.

---
