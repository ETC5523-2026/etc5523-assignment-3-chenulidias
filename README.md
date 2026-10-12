# ETC5523 Blog Assessment: Personal website and blog post

Prepared by: Chenuli Duasha Dias Muthukuda Arachchige\
Live website: <https://etc5523-2026.github.io/etc5523-assignment-3-chenulidias/>

## Overview

This repository contains my personal Quarto website, published with GitHub Pages. It includes a themed homepage, an about page, and a blog post titled *Climate change has nearly doubled the chance of Black Summer-level fire weather*. The blog post summarises a peer-reviewed attribution study by van Oldenborgh et al. (2021). It explains how much more likely the extreme fire weather behind the 2019–20 Black Summer bushfires has become since the early 1900s, which weather ingredients are driving the change, the study's key limitations, and what the findings mean for people living near the bush.

## Audience statement

This blog post is written for people living in bushfire-prone areas of southeastern Australia, with no background in climate science, who want to understand how climate change is affecting the fire risk where they live.

## Repository structure

etc5523-assignment-3-chenulidias/

- `_quarto.yml` — Website settings (title, navbar, GitHub link, theme)
- `styles.css` — Custom theme (colours, fonts, navbar, title banner and references section)
- `index.qmd` — Homepage (automatically lists blog posts)
- `about.qmd` — About page with bio and links
- `profile.jpg` — Avatar used on the about page
- `posts/welcome/index.qmd` — Blog post source (text, figure and table code)
- `posts/welcome/references.bib` — References for the blog post
- `posts/welcome/thumbnail.jpg` — Thumbnail shown on the homepage
- `docs/` — Rendered website, published via GitHub Pages
- `_freeze/` — Saved results of the R code used by Quarto
- `blog-template.Rproj` — RStudio project file
- `README.md` — This file

## Source of evidence

van Oldenborgh, G. J., Krikken, F., Lewis, S., et al. (2021). Attribution of the Australian bushfire risk to anthropogenic climate change. *Natural Hazards and Earth System Sciences, 21*(3), 941–960. https://doi.org/10.5194/nhess-21-941-2021

The figure and table are built from results reported in this paper (probability ratios and the stated contribution of each weather variable), entered directly in R. No raw climate data is re-analysed.

## Generative AI declaration

I used ChatGPT to help plan and develop the website and blog post. This included assistance with CSS styling, Quarto YAML and page layout, grammar and clarity of written text, and explaining or troubleshooting R code. I also used ChatGPT to help refine tables and visual presentation. I independently evaluated and revised every suggestion for all code, figures, tables and written content submitted.

## Image credit

Thumbnail photo by [Deep Rajwar](https://www.pexels.com/photo/photo-of-burning-forest-4621457/) on Pexels.
