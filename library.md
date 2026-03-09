---
layout: page
title: Library
subtitle: Browse our collection of nearly 1,000 Hungarian children's books.
description: Browse and borrow from the Bocskai Hungarian School library catalogue.
permalink: /library/
---

<section class="section">
  <div class="container">
    <div class="section-header">
      <h2>Our Library Collection</h2>
      <p>
        The Bocskai Hungarian School library holds nearly 1,000 Hungarian children's books
        across five reading levels — from picture books for toddlers to chapter books for teens.
        Students can borrow books to take home and keep the language alive between classes.
        Library membership is included with enrolment.
      </p>
    </div>

    <div style="display:flex;gap:2rem;align-items:center;margin-bottom:2rem;flex-wrap:wrap;">
      <div style="flex:1;min-width:260px;">
        <img src="{{ '/assets/images/bocskai-library.png' | relative_url }}" alt="Bocskai Hungarian School library" style="width:100%;border-radius:8px;object-fit:cover;">
      </div>
      <div style="flex:1;min-width:260px;display:flex;flex-direction:column;gap:1rem;">
        <p>Browse our full catalogue online and find your next Hungarian read. Students can borrow books to take home — library membership is included with enrolment.</p>
        <a href="{{ site.library_url }}" target="_blank" rel="noopener" class="btn btn-primary" style="align-self:flex-start;">Open Library Catalogue</a>
      </div>
    </div>

    <iframe
      src="{{ site.library_url }}"
      width="100%"
      height="1024px"
      style="border:none">
    </iframe>

    <p style="text-align:center;margin-top:1.5rem;">
      <a href="{{ site.library_url }}" target="_blank" rel="noopener" class="btn btn-primary">Open Library Catalogue in New Tab</a>
    </p>
  </div>
</section>
