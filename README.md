# AURORA Portfolio

**A one-page portfolio for an AI-assisted content practice: short videos, ad creative, and SEO articles.**

[![Live site](https://img.shields.io/badge/site-GitHub%20Pages-2ea44f)](https://aghorbani84.github.io/aurora-portfolio/)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
[![GitHub stars](https://img.shields.io/github/stars/aghorbani84/aurora-portfolio?style=flat)](https://github.com/aghorbani84/aurora-portfolio/stargazers)

**Live site:** https://aghorbani84.github.io/aurora-portfolio/

## Overview

AURORA is a solo content practice that makes short product videos, ad carousels and stories, and SEO articles
with AI assistance and human editing. This repository is its portfolio site: a single static page
(`index.html` + `style.css`) with the sample work stored alongside it.

> **About the samples.** Every sample is made for a fictional demo brand (FlowBoard, Loopdesk, Kiln & Co).
> None of it is client work, and there are no real clients, results, or testimonials on the site.

## What's inside

- **Services**: short product videos, ad carousels and stories, and SEO articles.
- **Video samples**: a 60-second SaaS explainer, a 60-second product video, and a 15-second teaser,
  with caption files (`.vtt` / `.srt`) and their scripts.
- **Ad creative**: a 3-slide carousel, a 5-card carousel, and a set of vertical stories.
- **Writing sample**: a long-form SEO article.
- **Contact** section.

## Tech stack

Plain HTML and CSS, with no build step and no JavaScript framework. Hosted on GitHub Pages.

## Running locally

```bash
git clone https://github.com/aghorbani84/aurora-portfolio.git
cd aurora-portfolio
python3 -m http.server 8000
# open http://localhost:8000/
```

Opening `index.html` directly in a browser also works.

## Project structure

```
index.html            the portfolio page
style.css             styles
assets/
  videos/             MP4 samples with VTT/SRT captions
  carousel-3/         3-slide ad carousel
  carousel-5/         5-card ad carousel
  stories/            vertical story set
  text/               video scripts and SEO article sample (Markdown)
```

## Author

Built by [Abolfazl Ghorbani](https://github.com/aghorbani84).
