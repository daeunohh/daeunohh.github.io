---
title: "The measurement of the impact of soft error in SSD's OS layer"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jung-Hoon Kim

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2023-07-01T00:00:00Z'
doi: 'Oh, D., & Kim, J. hoon. (2023). The measurement of the impact of soft error in SSD's OS layer. Korean Semiconductor Testing Society Academic Conference Proceedings, 24, 298–302.'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-07-03T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Korean Semiconductor Test Conference*
publication_short: In *ICW*

abstract: SSD is an effective device for storing data, and various fields have chosen to use SSD. However, as the hardware components of SSD get more concentrated, SSD becomes more vulnerable to soft errors. A soft error on the SSD can cause malfunctions and SSD performance reductions. Previous studies investigated the impact of soft error on the application level. However, this study investigates the effect of soft error at the OS level. The experiment uses an in-house simulator, Flash OS, and a soft error manager, which is the overall executor of the investigation. While a virtual SSD, which is Flash OS, runs its task, the soft error manager injects a soft error by changing the context information of the task thread of the SSD. After the soft error occurs, the soft error manager traces errors in the OS layer. This process can measure the sensitivity of the OS component by the type of soft error injected task. The result shows that the vulnerability is concentrated on a particular OS component, depending on the task. Surprisingly, 68-71% of errors occurred in the most vulnerable OS component. This fact can hint at finding an effective and reliable method at the OS level to protect software functions from soft errors.

# Summary. An optional shortened abstract.
summary: ''

tags:
  - SSD Softerror Detection

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.linkedin.com/in/daeun-oh-2685b1277/overlay/1635555937294/single-media-viewer/?profileId=ACoAAEOKrzABAVIVIO792m4F8SsG0b7EGzfCUpQ'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'The measurement of the impact of soft error in SSD's OS layer'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - []]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
