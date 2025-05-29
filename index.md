---
# ─────────────  REQUIRED FRONT-MATTER  ─────────────
layout: page                 # “home” shows blog posts; “page” is a static landing page
title: "Dexuan Hu"           # text that appears in the browser tab + header
subtitle: "PhD Candidate · Logic · Dreamer   "   # subtitle under the main title
# cover-img: "assets/img/hero.jpg"  # hero image (optional). Put a file here or delete line
---

<!-- ==========  HERO SECTION  ========== -->
<!-- Change the paragraphs below to introduce yourself. -->
I am a final-year PhD cadidate in mathematical logic at Cornell. I’ve spent years absorbed in the structure and beauty of mathematics, especially descriptive set theory. 
Now, I'm pivoting to industry research roles — where mathematical insight, algorithmic precision, and logical rigor intersect. I’m excited to apply these skills to real-world challenges and make an impact beyond academia. 

Outside of mathematics, I have a deep appreciation for art, cinema and museums. 
I'm particularly moved by films and artworks that linger on memory, time, and the edge of perception — scenes where people and places drift together across distance or decades. 
I think often about reality, beauty, and truth — not as fixed things to define, but as questions that keep unfolding the more closely I look. These moments of abstraction feel very close to what draws me to math.


---

## Some Links   {#quick-links}
<!-- Update the paths only if you rename the pages. -->
For my academic CV and industry resume, see 
[**CV / Résumé**](/cv/) 

For my research insterests, papers and notes, see
[**Research**](/research/) ·

Follow my job preparation logs and random thoughts.
[**Blog**](/blog/)

---

## Research Interests

I'm interested in undersatnding the descriptive set theoretic structures of objects from other areas of mathematics.

* Descriptive set theoretic complxity of Lascar strong types from model theory  
* Analytic P-ideals, their Tukey/Borel-reducibility structures, and essential appilcations to Polish modules
* Puzzles about foundamental mathemitical objects, such as sets, natural numbers, linears orders and etc

Question: Consider the real number R as Q-vector space, take two uncountable Borel Q-vector subspaces of it. Abstractly these spaces are linearly isomorphic because they have the same cardinality. If we require isomorphisms to be Borel, is it true that they are still isomophic? 

*(For the answer to this and my papers and notes, see the [research page](/research/))*



## Latest Blog Posts
<!-- Shows your three most-recent posts automatically. No edits needed here. -->
{% for post in site.posts limit:3 %}
* **[{{ post.title }}]({{ post.url }})** <small>{{ post.date | date: "%Y-%m-%d" }}</small>  
  {{ post.excerpt }}
{% endfor %}

[&nbsp;→ All posts](/blog/)

---

## Contact
* dexuan.hu0928@gmail.com  
* [LinkedIn](https://linkedin.com/in/dexuanhu)

<!-- Feel free to remove any section you don’t need. Happy editing! -->
