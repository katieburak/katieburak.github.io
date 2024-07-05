---
title: "Bootstrapping generalized linear models to accommodate overdispersed count data"
authors:
- admin
- Adam B. Kashlak
date: "2024-03-29T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-29T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: In *Statistical Papers*
publication_short: ""

abstract: When modelling counts or rates using Poisson regression, it is common to find overdispersion in data. Overdispersed count data is prevalent in a variety of applied research areas such as ecology and finance when the variance of the response is higher than the Poisson distribution allows. While there are models that are capable of handling data of this nature, conducting inference when presented with overdispersed data poses some challenges. Classical parametric approaches to inference may fail to be reliable when computing bounds for confidence regions as the mean-variance assumption of the Poisson distribution may not be satisfied. Bootstrap approaches are a viable alternative and we explore the performance of the one-step residual and wild bootstrap as a means to perform inference for regression parameters. Furthermore, we adopt an analytic approach to bootstrapping that is able to accommodate overdispersion, while being preferable from an efficiency perspective.


tags:
-

featured: true

links:
- name: Link
  url: https://link.springer.com/article/10.1007/s00362-024-01534-4


# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
