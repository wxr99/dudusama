---
layout: archive
title: "CV"
permalink: /dudusama/files/cv.pdf
author_profile: true
redirect_from:
  - /resume
---

## Debug Information:
- Site URL: {{ site.url }}
- Site BaseURL: {{ site.baseurl }}
- Relative URL test: {{ '/files/cv.pdf' | relative_url }}
- Absolute URL test: {{ '/files/cv.pdf' | absolute_url }}

## Manual Links:
- [Link 1: ../files/cv.pdf](../files/cv.pdf)
- [Link 2: /dudusama/files/cv.pdf](/dudusama/files/cv.pdf)
- [Link 3: {{ site.baseurl }}/files/cv.pdf]({{ site.baseurl }}/files/cv.pdf)
- [Link 4: {{ '/files/cv.pdf' | relative_url }}]({{ '/files/cv.pdf' | relative_url }})

<script>
console.log("Current URL:", window.location.href);
console.log("Base URL:", "{{ site.baseurl }}");
</script>
