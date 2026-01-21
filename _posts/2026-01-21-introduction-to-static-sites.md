---
title: "Introduction to Static Sites"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - S26
  - Github Pages
  - static sites
---

## What are Static Sites?

Static sites are web pages that are delivered directly to the user's browser exactly as they are stored. Unlike dynamic sites that generate content on-the-fly using databases and server-side processing, static sites consist of fixed HTML, CSS, and JavaScript files. This simplicity offers numerous advantages for digital humanities and sustainable web practices.

This course site is an example of a very simple static site built in Jekyll in Github Pages. 

Here are some more customized ones: 
- [The Programming Historian](https://programminghistorian.org/) - also Jekyll and in Github.
- [Stanford Literary Lab](https://litlab.stanford.edu/) - they explain why they adopted a static site [here](https://litlab.stanford.edu/techne/new-litlab-website/)

<!--more-->

## Advantages of Static Sites

**Performance & Speed**: Static files load quickly since there's no server-side processing or database queries required.

**Cybersecurity**: They have fewer moving parts and no dynamic backend processing, so static sites have fewer vulnerabilities to manage.

**Simplicity**: Static sites are straightforward to understand, maintain, and deploy. No complex server configurations or database management needed.

**Version Control**: Because static sites are typically plain text files (often Markdown), they integrate with version control systems, enabling collaborative development.

**Sustainability**: Minimal server requirements mean lower resource consumption and environmental impact—ideal for sustainable digital humanities projects.

**Cost-Effective**: Hosting static sites is inexpensive, with many platforms offering free hosting options like GitHub Pages.

## Static Sites and GitHub Pages

[GitHub Pages](https://pages.github.com/) is a hosting service that makes it easy to publish static sites directly from a GitHub repository and without cost. Combined with Jekyll, a static site generator, GitHub Pages enables you to:

- Write content in Markdown
- Version your entire site in VSCode
- Deploy changes with a simple push in VSCode or Github Desktop (for an added sanity check)
- Use themes for your site's appearance, and when you grow more confident, pass on to customization
- Maintain a complete history of all changes

## Getting Started

To create your own static site on GitHub Pages, you'll need:

1. A GitHub account
2. A text editor (we will use VS Code, etc.)
3. Git and GitHub Desktop installed
4. Basic familiarity with Markdown

This approach is particularly valuable for course sites, portfolios, project documentation, and archival materials where content stability and preservation matter.

## Sustainability, Static Sites and Digital Humanities

As Wikle and Williamson argue in their [Code4Lib Journal article](https://journal.code4lib.org/articles/18372), static web methodology represents a shift in how digital humanities practitioners approach infrastructure. Rather than investing significant time and resources in maintaining complex platform infrastructure, a static web approach emphasizes:

- **Minimal Infrastructure**: Static sites can be deployed on free hosting services like GitHub Pages, eliminating ongoing server maintenance costs
- **Preservation-Ready Data**: Content stored in plain text files and open formats can be easily migrated and preserved for the future
- **Reduced Technical Barriers**: By minimizing the complexity of platform administration, more scholars and students can engage directly in web development and digital project creation
- **Agility and Iteration**: Low-cost deployment enables rapid prototyping and iterative development without prohibitive resource constraints
- **Sustainability Focus**: The approach prioritizes investing resources in people and skills development rather than maintaining expensive systems

This philosophy aligns with principles of minimal computing in the digital humanities—asking what is truly necessary when developing digital scholarship under real-world constraints.

## Understanding Minimal Mistakes Template Components

The [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) Jekyll theme, which powers this course site, is built from several key components:

- **Layout Files** (`_layouts/`): HTML templates that define the structure of different page types (default, post, archive, etc.)
- **Include Files** (`_includes/`): Reusable HTML snippets (navigation, footer, header) that are embedded into layouts to avoid repetition
- **Assets** (`assets/`): Stylesheets (CSS), JavaScript files, and images that control the site's appearance and functionality
- **Configuration** (`_config.yml`): The main settings file controlling site title, theme, plugins, and other global behaviors
- **Content** (`_posts/`, `_pages/`): Your actual content files written in Markdown that Jekyll processes into HTML pages
- **Data Files** (`_data/`): YAML or JSON files containing structured information (like navigation menus) that templates can access and display

When you start with Minimal Mistakes, these components work together without issue. If you change things too quickly in the beginning you can break the site. As you gain confidence, however, you can customize individual pieces—changing colors in the CSS, modifying navigation structure in `_data/navigation.yml`, or adjusting layouts to create unique page designs—all without needing to rebuild the entire system.

Let's start by looking at a few elements `_data/navigation.yml`, `_pages`, `_posts` and `_config.yml`.

## Learn More

- [Jekyll Documentation](https://jekyllrb.com/)
- [GitHub Pages Guide](https://pages.github.com/)
- [Markdown Syntax](https://www.markdownguide.org/)

> **To read**: [Static Web Methodology as a Sustainable Approach to Digital Humanities Projects](https://journal.code4lib.org/articles/18372) by Olivia Wikle and Evan Peter Williamson (Code4Lib Journal, 2025). This article provides insight into why static web approaches are gaining traction in academic and digital humanities contexts, over web publishing methods such as WordPress or Drupal.