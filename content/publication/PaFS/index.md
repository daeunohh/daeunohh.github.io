---
title: "Flash-based storage systems exploiting the data period for performance and security enhancement"
authors:
- Jung-Hoon Kim
- Suhwan Kim
- admin
date: "2024-06-25T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-01-24T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["Poster Presentation"]

# Publication name and optional abbreviated publication name.
publication: "Flash-based storage systems exploiting the data period for performance and security enhancement"
# publication_short: ""

abstract: "When deleting data in the storage, the host system creates I/O requests for the data and sends them to the storage. Besides, if the host system sanitizes the data, it should also handle other I/O processes. Since the deletion processes might burden the host system, the file system in the host system could store its small metadata only in the storage to minimize the overhead. This kind of data management could be effective for better performance. However, in this case, the data supposed to be deleted cannot help but remain in the storage. In our flash-based storage system, we propose a novel scheme to eliminate all the I/O resources for the deletion processes in the host system. Moreover, this new flash-based storage thoroughly sanitizes the data without other specified I/O commands. Consequently, we experimented with the new flash-based storage called PaFS and compared the overall performance with the legacy storage."

# Summary. An optional shortened abstract.
summary: ""

tags:
- Storage Secure Erase Optimization

featured: true

links:
- name: Conference Link
  url: https://61dac.conference-program.com/presentation/?id=ETPOST121&sess=sess233
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://images.unsplash.com/photo-1721333091042-85101e0dba20?q=80&w=1335&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)'
  focal_point: ""
  preview_only: false

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

This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
