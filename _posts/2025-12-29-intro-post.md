---
layout: post
title: "Introducing the Site, and How It Works"
date: 2025-12-29 10:00:00 +0000
categories: [Editorial]
tags: [engineering, motorsport, workflow, jekyll]
author: tomas
---

## Focus and approach

This site exists to document and discuss **how race cars actually work**, from an
engineering perspective.

Rather than focusing on news, rumours, or speculation, the intent is to analyse
vehicles as engineered systems. Geometry, physics, regulation constraints, and
operational trade-offs matter more here than headline numbers or marketing language.

Many articles will follow a **front-to-back** structure, moving from local design
choices to vehicle-level consequences. Others will focus on specific subsystems or
engineering principles, using real cars as case studies.

---

## A collaborative engineering effort

This is a collaborative project maintained by a small group of engineers working in
motorsport and related technical fields.

Articles may be written individually or jointly, but they share a common approach:
- Technical accuracy over speed
- Explicit assumptions
- Clear separation between analysis and interpretation
- Preference for robust, race-relevant behaviour over idealised peak conditions

Guest contributors are invited when they can add specific technical insight.

---

## Why the site is built this way

The site itself follows the same philosophy as the content:  
**simple, robust, transparent, and version-controlled**.

Rather than using a hosted publishing platform, the site is built as a static
documentation-style project.

### Core components

- **Markdown** for all articles  
- **Jekyll** as the static site generator  
- **Chirpy** as the theme and layout framework  
- **Git** for version control  
- **GitHub Pages** for hosting  

This means every article is:
- Plain text
- Reviewable
- Open-Source
- Reproducible
- Easy to maintain long-term


---

## Writing, review, and publication

Articles are written in Markdown and reviewed before publication. Figures, diagrams,
and imagery are included where they improve clarity, not decoration.

The typical workflow is:
1. Draft the article in Markdown or Notion
2. Review for technical correctness and clarity
3. Commit changes to the repository
4. Automatically build and deploy the site

Publishing is a consequence of merging content, not a separate action.

---

## Why not something simpler?

There are many platforms that make publishing easier. The trade-off is control.

By keeping the site static and text-based:
- Content remains portable
- There is no platform lock-in
- Formatting remains predictable
- Technical debt is minimal

This is closer to maintaining technical documentation than running a blog, which is
deliberate.

---

## What to expect next

Upcoming articles will cover:
- Aerodynamic architecture and flow control
- Cooling and thermal trade-offs
- Regulation-driven design decisions
- Historic and modern race car case studies
- System-level interactions that are often discussed only in isolation

The intent is depth, not volume.

---

## Closing note

If you work in motorsport or vehicle engineering and recognise some of these trade-offs,
you will likely feel at home here.

If you disagree with an analysis, that is even better. Engineering benefits from
explicit assumptions and informed discussion.

