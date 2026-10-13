# README Authoring Guide & Fill-in Cheat Sheet

Use this reference alongside your `README.md` template. Each section below breaks down what content belongs there, guiding questions to answer, and real-world examples comparing an **academic project** versus a **creative project**.

---

## 1. Title & Tagline

### Purpose
Introduce the project instantly to an external reader, hiring manager, or evaluator.

### Guiding Questions
* What is the project named, and what does it actually accomplish in plain language?
* What domain does it belong to (e.g., computational linguistics, brand identity, interactive 3D web)?

### Examples
* **Academic:** 
  > `# Sentiment Drift in Clinical Trial Summaries`  
  > *A longitudinal NLP pipeline measuring framing shifts across open-access clinical trial abstracts between 2015 and 2024.*
* **Creative:** 
  > `# Solitude: Editorial Art Book & Visual Identity`  
  > *A 64-page print monograph and digital exhibition exploring urban isolation through brutalist architectural photography and custom typography.*

---

## 2. Visual Preview

### Purpose
Provide immediate visual evidence of the final product. GitHub renders images at the top of the repository, making this critical for engagement.

### What to Include
* **Primary (Hero) Image:** The best overall screenshot, print mockup, dashboard view, or high-level architecture diagram.
* **Secondary Side-by-Side Images:** Detail crops, mobile views, alternate design spreads, charts, or state comparisons (e.g., before vs. after).

### Tips
* Store images locally in an `assets/` or `docs/images/` directory inside the repo so links never break.
* Use descriptive `alt` text and brief captions explaining what the figure proves or displays.

---

## 3. Overview & Objectives

### Purpose
Frame the rationale behind the work so the reader understands why it was built.

### Section Breakdown
1. **Problem / Motivation:**
   * *Academic:* State the research gap, unanswered question, or limitation of previous studies.
   * *Creative:* State the creative brief, thematic catalyst, or user problem being solved.
2. **Scope:**
   * Detail boundary lines: what was built, what format it takes, and what was intentionally excluded.
3. **Core Takeaways:**
   * Summarize the primary empirical discovery, benchmark result, or creative impact.

---

## 4. Method & Architecture

### Purpose
Explain the technical workflow, design system, or experimental methodology.

### Academic Guidance
* Describe dataset curation, preprocessing steps, statistical models, validation techniques, and baseline comparisons.
* Focus on reproducibility and methodological rigor.

### Creative Guidance
* Outline the design phases (e.g., moodboarding, wireframing, component tokenization, production).
* Focus on visual hierarchy, aesthetic choices, user flow, or interaction mechanics.

### Deliverables Breakdown
* Highlight 2 to 4 tangible outcomes (e.g., *Interactive Web App*, *Statistical Notebook*, *Design System Kit*, *Trained Weights*).

---

## 5. Tools & Technologies

### Purpose
Quick reference table for recruiters or collaborators reviewing your technical stack.

### Recommended Categories
* **Design & Prototyping:** Figma, Adobe CC, Blender, Procreate.
* **Development & Frameworks:** Python, React, Next.js, PyTorch, Tailwind CSS.
* **Research & Analysis:** R, pandas, SciPy, Jupyter, Zotero.
* **Deployment & Build Tools:** Vercel, GitHub Actions, Docker, Netlify.

---

## 6. Project Structure

### Purpose
Helps visitors navigate the directory layout without guessing where scripts, papers, or assets live.

### Standard Template
```text
├── assets/             # Screenshots, renders, figures, fonts
├── data/               # Raw/cleaned data files or input text
├── docs/               # Research write-ups, briefs, notes
├── src/                # Implementation code, styles, notebooks
└── README.md           # Project documentation
```

---

## 7. Reflection & Retrospective

This section turns a generic project into a compelling case study.

### What I Learnt
* **Technical / Domain Knowledge:**
  * Did you learn a new library, algorithm, statistical method, or design technique?
  * *Example (Academic):* "Gained proficiency in adjusting for multi-class imbalance using focal loss rather than standard cross-entropy."
  * *Example (Creative):* "Learned how to design variable font axes to dynamically adjust legibility based on container width."
* **Process & Workflow:**
  * What did you discover about your own planning, version control, or execution speed?

### What I Would Have Done Differently
* **Architecture & Scoping:**
  * Where did you spend too much time? Which premature design or technical decisions created bottlenecks?
* **Alternative Approaches:**
  * If starting fresh today, what tool, model, or layout strategy would you use instead?
* **Future Iterations:**
  * Mention clear, prioritized next steps (e.g., adding accessibility audits, testing on an external dataset, introducing responsive mobile breakpoints).

---

## 8. Resources Used

### Academic References
* Cited journal articles, conference papers, preprints, or official datasets (include DOIs or direct URLs).

### Technical & Creative Resources
* Specific documentation pages, open-source libraries, UI asset kits, or reference tutorials that directly unblocked your progress.