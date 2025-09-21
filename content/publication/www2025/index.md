---
title: "Semantics-Aware Cookie Purpose Compliance"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Baiqi Chen
  - admin
  - Tingmin Wu
  - Mohan Baruwal Chhetri
  - Guangdong Bai
# Author notes (optional)
# author_notes:
#   - "Equal contribution"
#   - "Equal contribution"

date: "2025-04-22T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-04-22T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the ACM on Web Conference 2025*
publication_short: In *WWW 2025 Proceedings of the ACM on Web Conference 2025*

abstract: Websites commonly display cookie banners to inform users about the use and purposes of cookies. However, they may still, whether intentionally or unintentionally (e.g., due to third-party libraries imported), mis-declare cookies that may be abused for tracking. In this work, we introduce COOVER (<u>coo</u>kie <u>v</u>alue examin<u>er</u>) to assess the non-compliance between the website-declared purpose and the semantic-intended purpose of cookies (denoted as potential cookie purpose violation ). We advocate that the value of the cookie is a more reliable indicator of its semantic-intended purpose compared to other features such as expiration time. COOVER decomposes the cookie value into primitive segments representing minimal semantic units, and fine-tunes a GPT-3.5 model to automatically interpret their value-inferred semantics. Based on the interpretation, it classifies cookies into four GDPR-defined purposes. COOVER achieves an F1 score of 95%, significantly outperforming other methods. We employ COOVER to analyze Alexa Top 1k websites to understand the status quo of potential cookie purpose violation on the web. Remarkably, out of 15,339 cookies across these websites, only 3.1% quality as truly necessary cookies, while 44.1% of websites suffer from issues of potential purpose violation.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
#   - Large Language Models

# Display this page in the Featured widget?
featured: false

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1145/3696410.3714746

# Custom links
links:
  - type: pdf
    url: "https://dl.acm.org/doi/10.1145/3696410.3714746"
  # - type: code
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: dataset
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: slides
  #   url: https://www.slideshare.net/
  # - type: source
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: video
  #   url: https://youtube.com
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
#   focal_point: ""
#   preview_only: false

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
# slides: ""
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
