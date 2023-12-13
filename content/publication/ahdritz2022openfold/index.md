---
title: "OpenFold: Retraining AlphaFold2 yields new insights into its learning mechanisms and capacity for generalization"
authors:
  - Gustaf Ahdritz
  - Nazim Bouatta
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
  - Peter K Sorger
  - Emad Mostaque
  - Zhao Zhang
  - Richard Bonneau
  - Mohammed AlQuraishi

date: "2022-11-24T00:00:00Z"
doi: "https://doi.org/10.1101/2022.11.20.517210"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-07-20T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['artical']

# Publication name and optional abbreviated publication name.
publication: "bioRxiv"
publication_short: "bioRxiv"

abstract: AlphaFold2 revolutionized structural biology with the ability to predict protein structures with exceptionally high accuracy. Its implementation, however, lacks the code and data required to train new models. These are necessary to (i) tackle new tasks, like protein-ligand complex structure prediction, (ii) investigate the process by which the model learns, which remains poorly understood, and (iii) assess the model’s generalization capacity to unseen regions of fold space. Here we report OpenFold, a fast, memory-efficient, and trainable implementation of AlphaFold2, and OpenProtein-Set, the largest public database of protein multiple sequence alignments. We use OpenProteinSet to train OpenFold from scratch, fully matching the accuracy of AlphaFold2. Having established parity, we assess OpenFold’s capacity to generalize across fold space by retraining it using carefully designed datasets. We find that OpenFold is remarkably robust at generalizing despite extreme reductions in training set size and diversity, including near-complete elisions of classes of secondary structure elements. By analyzing intermediate structures produced by OpenFold during training, we also gain surprising insights into the manner in which the model learns to fold proteins, discovering that spatial dimensions are learned sequentially. Taken together, our studies demonstrate the power and utility of OpenFold, which we believe will prove to be a crucial new resource for the protein modeling community.

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
