# Train Smart, Train Even

**What Gym Exercises Reveal About Muscle Imbalances**

This project analyzes over 1,000 categorized gym exercises to uncover which muscle groups are most frequently targeted — and which are consistently neglected. Using R, Quarto, and ggplot2, I created a fully interactive dashboard that visually communicates these imbalances and provides training recommendations backed by data.

🔗 **Live Dashboard:** [Visit Dashboard](https://yourusername.github.io/train-smart-train-even)

---

## 📊 What’s Inside

- 📥 **Data Source:** Custom Excel dataset with exercise names, difficulty levels, equipment used, and muscle targeting (prime, secondary, tertiary).
- 🧹 **Data Cleaning:** Parsed multiple muscle columns into tidy rows using `separate_rows()` in R.
- 📈 **Visualizations:**
  - Top 15 most frequently trained muscles
  - Top 5 most neglected muscles
  - Top 4 muscles trained within each body region (faceted chart)
- 📋 **Interactive Summary Table** built with `DT::datatable()`
- 🧠 **Training Recommendations** based on actual data patterns

---

## 🧰 Tools Used

- **R**: Data cleaning, transformation, and visualization
- **Tidyverse**: Data wrangling and summaries
- **ggplot2**: All visualizations
- **readxl**: Reading Excel data
- **tidytext**: `reorder_within()` for clean facet plots
- **Quarto**: Documented and published the full analysis as a dashboard
- **DT**: For searchable, filterable muscle summary table

---

## 💡 Key Findings

- **Glutes, abs, and quads** are the most frequently trained muscles
- **Stabilizers** like the transverse abdominis, serratus anterior, and posterior delts are often neglected
- Push movements dominate — **pulling and balance work** are underrepresented
- Visual muscle groups receive more attention than postural or functional ones

---

## 📦 Folder Structure
