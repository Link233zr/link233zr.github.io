---
# ─────────────  REQUIRED FRONT-MATTER  ─────────────
layout: page                 # “home” shows blog posts; “page” is a static landing page
title: "Dexuan Hu"           # text that appears in the browser tab + header
subtitle: "Mathematician · Logic · Aspiring Quant"   # subtitle under the main title
# cover-img: "assets/img/hero.jpg"  # hero image (optional). Put a file here or delete line
---

<!-- ==========  HERO SECTION  ========== -->
<!-- Change the paragraphs below to introduce yourself. -->
I’m a fifth-year PhD candidate at **Cornell University** working in descriptive set theory.  
My current passion is applying rigorous probability and algorithmic thinking to quantitative
finance problems—if the maths is deep and the data is messy, I’m in!

> *“Mathematics is the music of reason.”* — James Joseph Sylvester

---

## Quick Links   {#quick-links}
<!-- Update the paths only if you rename the pages. -->
[**CV / Résumé**](/cv/) · 
[**Research**](/research/) · 
[**Teaching**](/teaching/) · 
[**Blog**](/blog/)

---

## Research Interests
* Determinacy axioms and their measure-theoretic consequences  
* Descriptive combinatorics on Polish spaces  
* Applications of set-theoretic methods to **risk-neutral pricing**

*(See the [research page](/research/) for papers and preprints.)*

---

## Teaching Snapshot
| Term | Course | Role |
|------|--------|------|
| Fall 2024 | *MATH 4340 – Honors Abstract Algebra* | Instructor of Record |
| Spring 2024 | *MATH 3110 – Intro Real Analysis* | Teaching Assistant |
| Fall 2023 | *Calculus I* | Recitation Leader |

Full syllabi and student feedback live on the [teaching page](/teaching/).

---

## Latest Blog Posts
<!-- Shows your three most-recent posts automatically. No edits needed here. -->
{% for post in site.posts limit:3 %}
* **[{{ post.title }}]({{ post.url }})** <small>{{ post.date | date: "%Y-%m-%d" }}</small>  
  {{ post.excerpt }}
{% endfor %}

[&nbsp;→ All posts](/blog/)

---

## Contact
* ✉️ dexuan@example.com  
* 🐙 [GitHub](https://github.com/link233zr) · [LinkedIn](https://linkedin.com/in/dexuanhu)

<!-- Feel free to remove any section you don’t need. Happy editing! -->
