---
layout: page
title: "Search"
permalink: /search/
---
<div>
<input type="text" id="search-input" placeholder="Search anything..">

<ul id="results-container"></ul>

<script>
    var sjs = SimpleJekyllSearch({
    searchInput: document.getElementById('search-input'),
    resultsContainer: document.getElementById('results-container'),
    json: '/search.json'
  })
</script>
</div>
