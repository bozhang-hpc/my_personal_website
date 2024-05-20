---
title: "OpenFold: Retraining AlphaFold2 yields new insights into its learning mechanisms and capacity for generalization"
authors:
  - Gustaf Ahdritz
  - Nazim Bouatta
  - Christina Floristean
  - Sachin Kadyan
  - Qinghui Xia
  - William Gerecke
  - "Timothy J O’Donnell"
  - Daniel Berenberg
  - Ian Fisk
  - "Niccolò Zanichelli"
  - bozhang
  - Arkadiusz Nowaczynski
  - Bei Wang
  - "Marta M Stepniewska-Dziubinska"
  - Shang Zhang
  - Adegoke Ojewole
  - Murat Efe Guney
  - Stella Biderman
  - Andrew M Watkins
  - Stephen Ra
  - Pablo Ribalta Lorenzo
  - Lucas Nivon
  - Brian Weitzner
  - "Yih-En Andrew Ban"
  - Shiyang Chen
  - Minjia Zhang
  - Conglong Li
  - Shuaiwen Leon Song
  - Yuxiong He
  - Peter K Sorger
  - Emad Mostaque
  - Zhao Zhang
  - Richard Bonneau
  - Mohammed AlQuraishi

date: "2024-05-14T00:00:00Z"
doi: "https://doi.org/10.1038/s41592-024-02272-z"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-05-20T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: "Nature Methods"
publication_short: "Nature Methods"

abstract: AlphaFold2 revolutionized structural biology with the ability to predict protein structures with exceptionally high accuracy. Its implementation, however, lacks the code and data required to train new models. These are necessary to (1) tackle new tasks, like protein–ligand complex structure prediction, (2) investigate the process by which the model learns and (3) assess the model’s capacity to generalize to unseen regions of fold space. Here we report OpenFold, a fast, memory efficient and trainable implementation of AlphaFold2. We train OpenFold from scratch, matching the accuracy of AlphaFold2. Having established parity, we find that OpenFold is remarkably robust at generalizing even when the size and diversity of its training set is deliberately limited, including near-complete elisions of classes of secondary structure elements. By analyzing intermediate structures produced during training, we also gain insights into the hierarchical manner in which OpenFold learns to fold. In sum, our studies demonstrate the power and utility of OpenFold, which we believe will prove to be a crucial resource for the protein modeling community.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Source Themes
featured: false

# links:
# - name: Custom Link
#   url: http://example.org
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
