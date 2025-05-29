---
# ─────────────  REQUIRED FRONT-MATTER  ─────────────
layout: page                 # “home” shows blog posts; “page” is a static landing page
title: "Dexuan Hu"           # text that appears in the browser tab + header
subtitle: "PhD Candidate · Logic · Movies · Games   "   # subtitle under the main title
# cover-img: "assets/img/hero.jpg"  # hero image (optional). Put a file here or delete line
---

<!-- ==========  HERO SECTION  ========== -->
<!-- Change the paragraphs below to introduce yourself. -->
I’m a sixth-year PhD candidate in mathematics at **Cornell University**.  My research focues on mathematical logic and more specifically Descriptive Set Theory.
I'm interested in using descriptive set theoretic tools to study the underlying structures in objects from other areas of mathematics.
One example of such is this: consider the real number R as Q-vector space, take two uncountable Borel Q-vector subspaces of it. Abstractly these spaces are linearly isomorphic because they have the same cardinality. If we require isomorphisms to be Borel, is it true that they are still isomophic? You can find the answer on the bottom of the page. 



---

## Quick Links   {#quick-links}
<!-- Update the paths only if you rename the pages. -->
[**CV / Résumé**](/cv/) · 
[**Research**](/research/) · 
[**Teaching**](/teaching/) · 
[**Blog**](/blog/)

---

## Research Interests
* Lascar Strong Types and their descrptive set theoretic complexities  
* Analytic P-ideals, their Tukey/Borel-reducibility structures and applications
* Puzzles about foundamental mathemitical objects, such as sets, natural numbers, linears orders and etc

*(See the [research page](/research/) for papers and notes.)*



## Latest Blog Posts
<!-- Shows your three most-recent posts automatically. No edits needed here. -->
{% for post in site.posts limit:3 %}
* **[{{ post.title }}]({{ post.url }})** <small>{{ post.date | date: "%Y-%m-%d" }}</small>  
  {{ post.excerpt }}
{% endfor %}

[&nbsp;→ All posts](/blog/)

---

## Contact
* ✉️ dexuan.hu0928@gmail.com  
* 🐙 [GitHub](https://github.com/link233zr) · [LinkedIn](https://linkedin.com/in/dexuanhu)

<!-- Feel free to remove any section you don’t need. Happy editing! -->
