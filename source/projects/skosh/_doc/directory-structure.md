---
title: Directory Structure
template: documentation.twig::content_inner
chapter: 9
---
Example directory structure

```
skosh-project-root
├─── config.yml
├─── config_production.yml
├─── gulpfile.js
├─── package.json
├─── .env.yml
├─── .remote.yml
├─── skosh
└─── source
     ├─── about.textile
     ├─── index.twig
     ├─── sitemap.xml
     ├─── rss.xml
     ├─── _posts
     │    ├─── 2014-01-01-my-first-post.md
     │    └─── 2014-01-03-my-second-post.textile
     │
     ├─── news
     │    ├───  index.twig
     │    └─── _posts
     │         ├─── 2014-02-15-polar-vortex.md
     │         └─── 2014-01-24-muppets-take-manhattan.md
     │
     ├─── _includes
     │    ├─── footer.twig
     │    └─── topbar.twig
     │
     └─── _templates
          ├─── default.twig
          └─── post.twig
```
