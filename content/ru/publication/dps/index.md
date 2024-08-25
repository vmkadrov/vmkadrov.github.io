---
title: "On the Selection of Weights for Difference Schemes to Approximate Systems of Differential Equations"
authors:
- admin
- Mikhail Malykh
- Alexander Zorin
doi: "10.3390/math12142287"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-08-01"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Mathematics 2024, 12(14), 2287"

abstract: We consider the problem of determining the weights of difference schemes whose form is specified by a particular symbolic expression. The order of approximation of the differential equation is equal to a given number. To solve it, it was propose to proceed from considering systems of differential equations of a general form to one scalar equation. This method provides us with some values for the weights, which we propose to test using Richardson’s method. The method was shown to work in the case of low-order schemes. However, when transitioning from the scalar problem to the vector and nonlinear problems, the reduction of the order of the scheme, whose weights are selected for the scalar problem, occurs in different families of schemes. This was first discovered when studying the Shanks scheme, which belongs to the family of explicit Runge–Kutta schemes. This does not deteriorate the proposed strategy itself concerning the simplification of the weight-determination problem, which should include a clause on mandatory testing of the order using the Richardson method.

url_pdf: "https://www.mdpi.com/2227-7390/12/14/2287"
url_code: 'https://github.com/vmkadrov/dps'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  focal_point: ""
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ["dps"]
---