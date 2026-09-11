---
layout: about
title: about
permalink: /

profile:
  align: right
  image: prof_pic.jpg
  image_circular: true # crops the image to make it circular

selected_papers: false # the full publication list is placed in the page body below instead
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<style>
  /* One-page site: keep section titles clear of the fixed menu bar when jumping to them. */
  .post h2[id] { scroll-margin-top: 4.5rem; }
  @media (prefers-reduced-motion: no-preference) { html { scroll-behavior: smooth; } }
</style>

Hello!
I am Yi (Owen) Yang, a fourth-year Ph.D. candidate in [Computer Science](https://cs.duke.edu/) at [Duke University](https://duke.edu/), where I am fortunate to be advised by Professor [Jian Pei](https://sites.google.com/view/jpei/jian-peis-homepage).
Before joining Duke, I obtained my Bachelor of Science degree in [Computer Science](https://computerscience.emory.edu/) from [Emory University](https://www.emory.edu/home/index.html), where I am fortunate to be advised by Professor [Carl Yang](https://www.cs.emory.edu/~jyang71/).

My research interest spans the fascinating intersection of multimodal data mining, data storytelling, data-efficient machine learning, and bioinformatics.
Currently, my research focuses on automatic paradox discovery in multi-attribute datasets and pattern recognition in sparse tabular data.

I love discussing research ideas and exploring new collaborations! Feel free to reach out if you'd like to talk about potential projects or just chat about recent developments in the field. I'm always happy to connect.

<!--
  Each section id below must match an anchor in _data/navigation.yml (the menu).
  The dated sections reuse the publication-list styling: each <li> has a badge with the dates,
  a bold "title" line, an "author" line for the organization, and "periodical" lines for details.
-->

## Publications {#publications}

<div class="publications">

{% bibliography --group_by none %}

</div>

## Education {#education}

<div class="publications">
<ol class="bibliography">
  <li>
    <div class="row">
      <div class="col col-sm-2 abbr"><abbr class="badge rounded w-100">2023–now</abbr></div>
      <div class="col-sm-10">
        <div class="title">Ph.D. in Computer Science</div>
        <div class="author">Duke University, Durham, NC</div>
        <div class="periodical">Advisor: <a href="https://sites.google.com/view/jpei/jian-peis-homepage">Jian Pei</a> · GPA 4.00/4.00</div>
      </div>
    </div>
  </li>
  <li>
    <div class="row">
      <div class="col col-sm-2 abbr"><abbr class="badge rounded w-100">2019–2023</abbr></div>
      <div class="col-sm-10">
        <div class="title">B.S. in Computer Science and Mathematics</div>
        <div class="author">Emory University, Atlanta, GA</div>
        <div class="periodical">GPA 3.92/4.00 · Dean's List: Fall 2021, Spring 2022, Fall 2022</div>
      </div>
    </div>
  </li>
</ol>
</div>

## Work Experience {#work-experience}

<div class="publications">
<ol class="bibliography">
  <li>
    <div class="row">
      <div class="col col-sm-2 abbr"><abbr class="badge rounded w-100">Summer 2026</abbr></div>
      <div class="col-sm-10">
        <div class="title">Applied Scientist Intern, Customer Relation Management</div>
        <div class="author">Amazon, Seattle, WA</div>
        <div class="periodical">May – Aug 2026</div>
        <div class="periodical">Developed an evidence-based explanation framework for LLM-based household attribute prediction from large-scale e-commerce behavior data, to improve interpretability and guide more reliable fine-tuning.</div>
      </div>
    </div>
  </li>
  <li>
    <div class="row">
      <div class="col col-sm-2 abbr"><abbr class="badge rounded w-100">Summer 2025</abbr></div>
      <div class="col-sm-10">
        <div class="title">Research Engineer Intern, Mobile Platform and Solutions</div>
        <div class="author">Samsung Research America, Mountain View, CA</div>
        <div class="periodical">Jun – Aug 2025</div>
        <div class="periodical">Developed a heterogeneous GNN framework that models low-level behavioral activities of Android apps, reaching 97.44% multi-class malware classification accuracy across 11,598 APK samples, and built an Android client that runs the detection pipeline on the mobile CPU.</div>
      </div>
    </div>
  </li>
  <li>
    <div class="row">
      <div class="col col-sm-2 abbr"><abbr class="badge rounded w-100">2021</abbr></div>
      <div class="col-sm-10">
        <div class="title">Portfolio Analyst Intern</div>
        <div class="author">C8 Technologies, Shanghai, China</div>
        <div class="periodical">Jan – Aug 2021</div>
        <div class="periodical">Prepared reports on the fundamentals and mathematical intuitions of industry-standard asset management strategies, and redesigned the front end of the company's online portfolio allocation toolbox with a scalable backend for regression analysis and prediction of portfolio returns.</div>
      </div>
    </div>
  </li>
</ol>
</div>

## Teaching Experience {#teaching-experience}

<div class="publications">
<ol class="bibliography">
  <li>
    <div class="row">
      <div class="col col-sm-2 abbr"><abbr class="badge rounded w-100">Spring 2025</abbr></div>
      <div class="col-sm-10">
        <div class="title">Computational Imaging</div>
        <div class="author">Duke University</div>
        <div class="periodical">Teaching Assistant</div>
      </div>
    </div>
  </li>
  <li>
    <div class="row">
      <div class="col col-sm-2 abbr"><abbr class="badge rounded w-100">Fall 2024</abbr></div>
      <div class="col-sm-10">
        <div class="title">Introduction to Databases</div>
        <div class="author">Duke University</div>
        <div class="periodical">Teaching Assistant</div>
      </div>
    </div>
  </li>
  <li>
    <div class="row">
      <div class="col col-sm-2 abbr"><abbr class="badge rounded w-100">2021–2022</abbr></div>
      <div class="col-sm-10">
        <div class="title">Data Structures and Algorithms</div>
        <div class="author">Emory University</div>
        <div class="periodical">Teaching Assistant, Fall 2021 &amp; Fall 2022</div>
      </div>
    </div>
  </li>
</ol>
</div>

## Services {#services}

- **Journal Reviews:**
  - IEEE Transactions on Neural Networks and Learning Systems (TNNLS), 2023, 2024, 2025, 2026.
  - ACM Transactions on Knowledge Discovery from Data (TKDD), 2024.
  - Neurocomputing, 2022, 2023.

- **Conference Reviews:**
  - IEEE International Conference on Data Mining (ICDM), 2023, 2024.
  - Pacific Symposium on Biocomputing (PSB), 2024.

<!-- ClustrMaps visitor tracker, carried over from the old site (hidden) -->
<div style="height: 0; width: 0; overflow: hidden;">
  <script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=NgvMLYKIHjwAzbgvXnKj-o5rclmQCnoBr9XLu4RLAxg"></script>
</div>
