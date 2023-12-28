---
title: 'Improving data quality of smartphone‐based activity–travel survey: A framework for data post‐processing'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Ying Song
  - Yingling Fan
  

# Author notes (optional)
author_notes:

date: '2021-11-02'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-11-02'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *Transactions in GIS*
publication_short: ''

abstract: The smartphone-based activity–travel survey has emerged as an approach to collect detailed data on individuals’ activities and trips throughout the day. The collected data are usually structured as a series of consecutive activity and trip episodes. Recent studies have used these data to advance our understanding of individuals’ activity–travel patterns. However, few studies have explicitly described how to handle new quality issues of such data. This article develops a framework and methods to systematically detect and handle quality issues in the smartphone-based activity–travel survey data to ensure attribute completeness and logical consistency. For attribute completeness, we check if each episode contains all the required thematic, temporal, and spatial attributes. For logical consistency, we check if two consecutive episodes are logically inconsistent regarding spatial and temporal continuity. We classify invalid episodes into distinct groups using mixture models, clustering, and a transition matrix. For each group, we propose specific improvement methods. To demonstrate our methods, we use data collected in the Twin Cities, Minnesota, USA, as a study case. The results show that our framework can systematically deal with various data quality issues. We also show how data before and after quality control may lead to different observations about individuals' behavior patterns.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://doi.org/10.1111/tgis.12865'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - data-quality

---
