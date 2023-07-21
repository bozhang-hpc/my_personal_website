---
title: 'Assembling Portable In-Situ Workflow from Heterogeneous Components using Data Reorganization'
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - bozhang
  - Pradeep Subedi
  - Philip E Davis
  - Francesco Rizzi
  - Keita Teranishi
  - Manish Parashar

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-07-19T00:00:00Z'
doi: 'https://doi.org/10.1109/CCGrid54584.2022.00013'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-07-20T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2022 22nd IEEE International Symposium on Cluster, Cloud and Internet Computing (CCGrid)*
publication_short: In *CCGrid 2022*

abstract: Heterogeneous computing is becoming common in the HPC world. The fast-changing hardware landscape is pushing programmers and developers to rely on performance-portable programming models to rewrite old and legacy applications and develop new ones. While this approach is suitable for individual applications, outstanding challenges still remain when multiple applications are combined into complex workflows. One critical difficulty is the exchange of data between communicating applications where performance constraints imposed by heterogeneous hardware advantage different data layouts. We attempt to solve this problem by exploring asynchronous data layout conversions for applications requiring different memory access patterns for shared data. We implement the proposed solution within the DataSpaces data staging service, extending it to support heterogeneous application workflows across a broad spectrum of programming models. In addition, we integrate heterogeneous DataSpaces with the Kokkos programming model and propose the Kokkos Staging Space as an extension of the Kokkos data abstraction. This new abstraction enables us to express data on a virtual shared space for multiple Kokkos applications, thus guaranteeing the portability of each application when assembling them into an efficient heterogeneous workflow. We present performance results for the Kokkos Staging Space using a synthetic workflow emulator and three different scenarios representing access frequency and use patterns in shared data. The results show that the Kokkos Staging Space is a superior solution in terms of time-to-solution and scalability compared to existing file-based Kokkos data abstractions for inter-application data exchange.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
