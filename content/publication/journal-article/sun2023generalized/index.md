---
title: "Generalized Multiphase-Shift Transient Modulation for Dual-Active-Bridge Series-Resonant Converter"
authors:
- admin
- Junwei Liu
- Xingyue Jiang
- Lingling Cao
- Yun-Chong Wang
- Jian-Xin Shen
- Ka-Hong Loo
author_notes:
- "https://orcid.org/0000-0001-9454-9480"
- "https://orcid.org/0000-0002-0158-1228"
- "https://orcid.org/0000-0003-2420-3526"
- "https://orcid.org/0000-0001-8441-7652"
- "https://orcid.org/0000-0001-7100-9705"
- "https://orcid.org/0000-0001-9652-8894"
- "https://orcid.org/0000-0003-0111-6665"
date: "2023-04-14T00:00:00Z" 
doi: "10.1109/TPEL.2023.3267297"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-04-14T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Power Electronics, 38*(7)"
publication_short: "IEEE TPEL"

abstract: Given the wide-range applications of bidirectional dual-active-bridge series-resonant converter (DABSRC), its complex nonlinear dynamic behavior is an interesting phenomenon that deserves attention of power electronics engineers. It is observed that if the control variables (i.e., phase-shift angles) are directly updated through conventional transient modulation, large-amplitude transient oscillations and dc offsets will be induced in the high-frequency-link voltages and currents during transient stage, which can ultimately degrade the converter's waveform quality significantly. The relatively few prior works in studying the transient oscillatory behavior of DABSRC have only focused on single-phase-shift modulation. In this article, a new transient modulation method referred to as generalized trajectory-switching modulation (GTSM) is first proposed for enhancing the transient performance of multiphase-shift modulated DABSRC. GTSM can simultaneously mitigate the problems of transient oscillations and dc offsets regardless of operation modes and power-flow directions, thus always ensuring safe transient operation. It also enables the resonant voltages and currents as well as magnetizing current to seamlessly reach the desired new steady-state values swiftly. Finally, the said theoretical claims are verified experimentally under both open loop and closed loop with model predictive control, and the influence of deviations from nominal resonant tank's parameters on GTSM is also considered.

# Summary. An optional shortened abstract.
summary: Generalized trajectory-switching modulation for simultaneous suppression of transient oscillations and dc offsets in dual-active-bridge series-resonant dc-dc converters.

tags:
- Dynamics of DAB Converters
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://chuansun-pe.github.io/content/publication/journal-article/sun2023generalized/sun2023generalized.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://ieeexplore.ieee.org/abstract/document/10102581'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://ieeexplore.ieee.org/abstract/document/10102581/figures#figures)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click on the **PDF** button above to view the full text.
{{% /callout %}}

{{% callout note %}}
Click the **Cite** button above to import publication metadata into the reference management software.
{{% /callout %}}