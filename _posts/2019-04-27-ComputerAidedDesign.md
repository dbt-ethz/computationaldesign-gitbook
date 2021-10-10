---
title: Computer Aided Design
author: Tao He
date: 2019-04-27
category: Jekyll
layout: post
---

GitBook is an amazing frontend style to present and organize contents (such as book chapters
and blogs) on Web. The typical to deploy GitBook at [Github Pages][1]
is building HTML files locally and then push to Github repository, usually to the `gh-pages`
branch. However, it's quite annoying to repeat such workload and make it hard for people do
version control via git for when there are generated HTML files to be staged in and out.

<p class="codepen" data-height="300" data-default-tab="result" data-slug-hash="XWaWZja" data-user="modellstadt" style="height: 300px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;">
  <span>See the Pen <a href="https://codepen.io/modellstadt/pen/XWaWZja">
  Untitled</a> by modellstadt (<a href="https://codepen.io/modellstadt">@modellstadt</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>

This theme takes style definition out of generated GitBook site and provided the template
for Jekyll to rendering markdown documents to HTML, thus the whole site can be deployed
to [Github Pages][1] without generating and uploading HTML bundle every time when there are
changes to the original repository.

[1]: https://pages.github.com


{% include test.html content="This is my sample note." %}

{% include babylon.html content="This is my sample note." %}

