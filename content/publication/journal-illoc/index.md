---
title: 'ILLOC: In-Hall Localization with Standard LoRaWAN Uplink Frames'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Dongfang Guo
  - Chaojie Gu
  - Linshan Jiang 
  - admin
  - Rui Tan

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2021-08-20T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-08-20T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: "*Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies*"
publication_short: "*Ubicomp'21*"

abstract: LoRaWAN is a narrowband wireless technology for ubiquitous connectivity. For various applications, it is desirable to localize LoRaWAN devices based on their uplink frames that convey application data. This localization service operates in an unobtrusive manner, in that it requires no special software instrumentation to the LoRaWAN devices. This paper investigates the feasibility of unobtrusive localization for LoRaWAN devices in hall-size indoor spaces like warehouses, airport terminals, sports centers, museum halls, etc. We study the TDoA-based approach, which needs to address two challenges of poor timing performance of LoRaWAN narrowband signal and nanosecond-level clock synchronization among anchors. We propose the ILLOC system featuring two LoRaWAN-specific techniques (1) the cross-correlation among the differential phase sequences received by two anchors to estimate TDoA and (2) the just-in-time synchronization enabled by a specially deployed LoRaWAN end device providing time reference upon detecting a target device’s transmission. In a long tunnel corridor, a 70 × 32 m2 sports hall, and a 110 × 70 m2 indoor plaza with extensive non-line-of-sight propagation paths, ILLOC achieves median localization errors of 6 m (with 2 anchors), 8.36 m (with 6 anchors), and 15.16 m (with 6 anchors and frame fusion), respectively. The achieved accuracy makes ILLOC useful for applications including zone-level asset tracking, misplacement detection airport trolley management, and cybersecurity enforcement like detecting impersonation attacks launched by remote radios.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags: []
tags:
  - Journal articles
# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://tanrui.github.io/pub/ILLOC-final.pdf'
# url_code: 'https://github.com/jiegev5/PhyAug'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: https://www.youtube.com/watch?v=LcIVBRx4x-o&ab_channel=CPS-IoTWeek-IPSN

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'System Overview'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - phyaug

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
<!-- 
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
