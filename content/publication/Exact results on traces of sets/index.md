---
title: "Exact Results on Traces of Sets"
authors:
- Mingze Li
- Jie Ma
- admin
date: "2024-06-27T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: |
For non-negative integers n, m, a and b, we write (n,m)→(a,b) if for every family F⊆ 2^[n] with |F|≥ m there is an a-element set T⊆[n] such that |F_|T|≥ b, where F_|T={F∩T:F∈F}. A longstanding problem in extremal set theory asks to determine m(s)=lim_{n→+∞} m(n,s)/n, where m(n,s) denotes the maximum integer m such that (n,m)→(n-1,m-s) holds for non-negatives n and s. In this paper, we establish the exact value of m(2^{d-1}-c) for all 1≤ c≤ d whenever d≥ 50, thereby solving an open problem posed by Piga and Schülke. To be precise, we show that

m(n,2^{d-1}-c) = 
{
  (2^d - c)/d * n for 1≤ c≤ d-1 and d does not divide n,
  (2^d - d - 0.5)/d * n for c=d and 2d does not divide n
}

holds for d≥ 50. Furthermore, we provide a proof that confirms a conjecture of Frankl and Watanabe from 1994, demonstrating that m(11)=5.3.

# Summary. An optional shortened abstract.

tags:
- Traces of Sets

featured: true

url_slides: '/files/slides.pdf'
url_pdf: https://arxiv.org/pdf/2406.18870
links:
  - name: arXiv
    url: https://arxiv.org/abs/2406.18870


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
