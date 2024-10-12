---
title: "Dual Channel Dual Staging: Hierarchical and Portable Staging for GPU-Based In-Situ Workflow"
authors:
- bozhang
- Philip E Davis
- Zhao Zhang
- Keita Teranishi
- Manish Parashar
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2024-12-18T00:00:00Z"
# doi: "https://doi.org/10.1007/978-3-031-39698-4_22"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-10-11T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "In *2024 IEEE 31st International Conference on High Performance Computing, Data, and Analytics (HiPC)*"
publication_short: "In *HiPC 2024* (Accepted)"

abstract: In-situ workflows have emerged as an attractive approach for addressing data movement challenges at very large scales. Since GPU-based architectures dominate the HPC landscapes, porting these in-situ workflows, and, specifically, the inter-application data exchange, to GPU-based systems can be challenging. Technologies such as GPUDirect RDMA (GDR), which is typically used for I/O in GPU applications as an optimization that circumvents the CPU overhead, can be leveraged to support bulk data exchanges between GPU applications. However, current GDR design often lacks performance portability across HPC clusters built with different hardware configurations. Furthermore, the local CPU may also be effectively used as an auxiliary communication mechanism to offload data exchanges. In this paper, we present a dual channel dual staging approach for efficient, scalable, and performance-portable inter-application data exchange for in-situ workflows. This approach exploits the data access pattern within in-situ workflows along with the inherent execution asynchrony to accelerate data exchanges and, at the same time, improve performance portability. Specifically, the dual channel dual staging method leverages both the local CPU and the remote data staging server to build a hierarchical joint staging area and uses this staging area to transform blocking inter-application bulk data exchanges into best-effort local data movements between GPU and CPU. The dual channel dual staging is implemented as a portability extension of the Dataspaces-GPU staging framework. We present an experimental evaluation of its performance, portability, and scalability using this implementation on three leadership GPU clusters. The evaluation results demonstrate that the dual channel dual staging method saves up to 75\% in data-exchange time compared to host-based, GDR, and alternate portable designs, while maintaining scalability (up to 512 GPUs) and performance portability across the three platforms.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Source Themes
featured: false



# links:
# - name: "aaa"
  # url: ""
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

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
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
