# ⚡ Relational Database Foundations - Interactive Lab

A premium, highly interactive single-page web simulator and live lecture companion designed for learning relational database models, normalization, joins, keys, and schemas. Built with rich animations, custom canvas visualizers, dynamic Venn diagrams, and a local SQL parser/executor.

🚀 **Live Deployment-ready for GitHub Pages!**

---

## ✨ Features

### 1. ⚡ Live SQL Mutation Playground
* Directly write and execute queries in a mock SQL terminal.
* Fully supports `SELECT` projections, `WHERE` filters, `LIMIT` clauses, and mutating statements like `INSERT INTO`, `UPDATE SET`, and `DELETE FROM`.
* Mutates an in-memory database array and refreshes canvas-rendered tables in real-time.

### 2. ⚡ Hands-on ER Schema Matcher
* An interactive, canvas-backed Entity-Relationship (ER) diagram matcher.
* Drag and click table column points to connect Primary Keys (PK ★) and Foreign Keys (FK →) across 5 related startup database tables.
* Dynamic vector bezier line drawing on canvas with instant validity feedback and particle confetti celebrations upon completion.

### 3. ⚡ Mathematically Correct JOIN Types Visualizer
* Toggle between `INNER JOIN`, `LEFT JOIN`, and `RIGHT JOIN` selectors.
* Renders accurate, dynamic SVG Venn diagrams showing exact overlapping set regions (utilizing SVG clip-paths).
* Highlights orphan/unmatched values as glowing red `NULL` blocks in the query results table.

### 4. ⚡ Holographic Primary Key Aadhaar Generator
* Type custom customer names (e.g. **Munna Kumar**) to generate unique, non-null, and stable Database Identity Cards.
* Explains the national scale Aadhaar Card analogy for database Primary Keys using a glowing hologram card layout.

### 5. ⚡ Live Sidebar Workspace Dashboard & Sparklines
* Shows real-time workspace engine status, table stats, established links count, and developer credentials (**Munna Kumar**).
* Features a live canvas-drawing sparkline chart simulating query transactions and database loads.

---

## 🛠️ Technology Stack
* **Markup**: Semantic HTML5 structure
* **Styling**: Vanilla CSS3 with customized CSS variables (neon-cyan, violet, and amber colors), custom grid systems, and a fully polished responsive glassmorphic Dark and Light theme layout.
* **Logic & Canvas**: Pure Javascript (ES6+) utilizing HTML5 Canvas API contexts for drawing connection maps, particle explosions, Venn shading, and dataset tables.
* **Math Rendering**: MathJax for LaTeX mathematical expressions.

---

## 📦 Deployment to GitHub Pages
To deploy this project to your GitHub Pages domain:
1. Initialize a git repository in this folder:
   ```bash
   git init
   git add .
   git commit -m "Initial commit - Database Interactive Lab"
   ```
2. Create a new repository on GitHub and link it:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git branch -M main
   git push -u origin main
   ```
3. Go to your repository settings on GitHub:
   * Navigate to **Settings** -> **Pages**.
   * Under **Build and deployment**, select **Deploy from a branch**.
   * Choose the **main** branch and `/root` folder, then click **Save**.
4. Your site will be live at `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/` in a few minutes!

---

## 🎓 Branding & Credits
* **Platform Branding**: CodeWithMunnaX (Data Science & AI Program)
* **Author**: Munna Kumar
* **Social Links**:
  * [Instagram](https://www.instagram.com/codewithmunnax?igsh=MWdqZWQxd3B1Yjlk)
  * [LinkedIn](https://www.linkedin.com/in/munna-kumar-93234b241)
  * [YouTube](https://www.youtube.com/@CodeWithMunnaX)
