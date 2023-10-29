---
title: "Learning data-driven discretizations for partial differential equations"
date: 2019-07-16T00:00:00
draft: false

authors: [
"Yohai Bar-Sinai<sup class=tolstoy>&dagger;</sup>",
"Stephan Hoyer<sup class=tolstoy>&dagger;</sup>",
"Jason Hickey",
"Michael P Brenner"]
jointFirst: true

# Publication name and optional abbreviated version.
journal: "PNAS"

text_above_abstract: "<div style='background-color:beige; text-align:center; border-radius:10px;margin:0 30px 0 30px'><span> see also layman presentation in <a href='https://ai.googleblog.com/2019/07/learning-better-simulation-methods-for.html'> Google AI blogpost</a></span></div>"

# Abstract and optional shortened version.
abstract: "The numerical solution of partial differential equations (PDEs) is challenging because of the need to resolve spatiotemporal features over wide length- and timescales. Often, it is computationally intractable to resolve the finest features in the solution. The only recourse is to use approximate coarse-grained representations, which aim to accurately represent long-wavelength dynamics while properly accounting for unresolved small-scale physics. Deriving such coarse-grained equations is notoriously difficult and often ad hoc. Here we introduce data-driven discretization, a method for learning optimized approximations to PDEs based on actual solutions to the known underlying equations. Our approach uses neural networks to estimate spatial derivatives, which are optimized end to end to best satisfy the equations on a low-resolution grid. The resulting numerical methods are remarkably accurate, allowing us to integrate in time a collection of nonlinear equations in 1 spatial dimension at resolutions 4× to 8× coarser than is possible with standard finite-difference methods."
abstract_short: ""

url_pdf: "SuperResolution.pdf"
url_preprint: "http://arxiv.org/abs/1808.04930"
url_code: "https://github.com/google/data-driven-discretization-1d"
url_source: "http://dx.doi.org/10.1073/pnas.1814058116"

url_custom: [{name = "Google AI Blogpost", url = "https://ai.googleblog.com/2019/07/learning-better-simulation-methods-for.html"}]

bibtex: "@article{bar-sinai2019,
  title={Learning data-driven discretizations for partial differential equations},
  author={Bar-Sinai, Yohai and Hoyer, Stephan and Hickey, Jason and Brenner, Michael P},
  journal={Proceedings of the National Academy of Sciences},
  volume={116},
  number={31},
  pages={15344--15349},
  year={2019},
  publisher={National Acad Sciences}
}"
---
