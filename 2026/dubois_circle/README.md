# 🎨 Recreating History with Data: W.E.B. Du Bois Spiral Chart

What if data visualization wasn’t just about numbers — 
but about visualizing the explosive growth of a community against all odds?

In 1900, W.E.B. Du Bois and his students created a series of hand-drawn data visualizations for the Paris Exposition — not just to inform, but to challenge racial stereotypes and tell a different story.

This project is a modern recreation of Du Bois's iconic spiral chart, visualizing the **Household Value Owned by Negroes in Georgia (1875–1899)**, bringing that powerful narrative into today’s tools.

## 🖼️ Modern vs. Original Comparison

![Recreation of the Du Bois spiral in R](figures/du_bois_circle.png)
*(Insert your side-by-side image here if you have one, or just keep the generated plot)*

## 📖 The Story

### 🧠 Historical Context
At the 1900 Paris Exposition, Du Bois presented data visualizations to showcase the economic and social progress of African Americans after emancipation. 

This specific chart visualizes the staggering increase in property value owned by Black households in Georgia over a 24-year period. The spiral form is not just an aesthetic choice; it represents accumulation, momentum, and an upward trajectory that defied the systemic oppression of the Jim Crow era.

These works were not just charts — they were:
* A political statement
* A design innovation ahead of its time
* One of the earliest examples of data storytelling

This project revisits that legacy through a modern lens, using code to honor the hand-drawn precision of the original.

## 🛠️ Tech Stack

* **Language:** R
* **Framework:** Quarto
* **Libraries:** `tidyverse`, `ggplot2`, `showtext`, `sysfonts`
* **Environment:** RStudio / Local R Environment

## 🚀 What I Did

* Recreated the original spiral visualization using modern programmatic tools.
* Reverse-engineered the concentric ring geometry and linear scaling of the original artwork.
* Simulated a hand-drawn texture (pencil/brush strokes) using statistical distributions (Beta distribution for natural stroke scattering).
* Preserved the original aesthetic, color logic, and typographic hierarchy.
* Explored how early data storytelling techniques translate into today’s design principles.

## 🎨 Design Philosophy

To honor Du Bois's original aesthetic and the "Mother Crown" touch of his data portraits, I utilized:

* **Concentric Ring Geometry:** Mapping the largest value (1899) to the innermost ring, allowing the spiral to grow outward in time and value.
* **Linear Scaling:** Preserving the dramatic visual contrast between the early years (1875) and the peak (1899) to emphasize the explosive economic growth.
* **Custom Texture:** Simulating organic, hand-drawn strokes rather than flat digital fills, using alpha-blending and randomized stroke paths.
* **Historical Typography:** Using serif fonts (IM Fell English) and handwritten accents (Caveat) to mirror the 1900s feel.
* **Du Bois Color Palette:** Muted, earthy tones (Red, Gold, Beige, Slate) that complement the antique paper background.

## 💭 Reflections

Working on this project made me realize:

> Data visualization is not just about clarity — 
> it’s about power, narrative, and perspective.

Du Bois wasn’t just visualizing data. He was reshaping perception. By coding this spiral, I didn't just replicate a chart; I traced the mathematical proof of resilience.

## 📊 Data Sources

* **Historical Data:** Household Value Owned by Negroes in Georgia (1875-1899), sourced from the original 1900 Paris Exposition datasets.
* **Reference:** "W.E.B. Du Bois's Data Portraits: Visualizing Black America" by Whitney Battle-Baptiste and Britt Rusert.

## 🚀 How to Run

1. Clone the repository.
2. Ensure you have R and Quarto installed.
3. Open `du_bois_circle.qmd` in RStudio.
4. Render the document to HTML to view the interactive layout and generate the final PNG.

---

*Authored for TidyTuesday / DataViz Society.* ✨

*Recreations inspired by: "W.E.B Dubois's Data Portraits, Visualizing Black America" by Whitney Battle-Baptiste and Britt Rusert (ISBN 978-1-61689-706-2).*
*The original plates may be accessed at the Library of Congress.*
