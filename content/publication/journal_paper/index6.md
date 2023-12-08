---
title: 'Superpixel-based optimal seamline detection in the gradient domain via graph cuts for orthoimage mosaicking'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Li Li
  - Jian Yao
  - Shuzhu Shi
  - Shenggu Yuan
  - admin
  - Jie Li
  

# Author notes (optional)
author_notes:

date: '2018-05-15'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2018-05-15'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *SSM - Population Health*
publication_short: ''

abstract: This paper presents an optimal seamline detection method for orthoimage mosaicking. To ensure that the detected optimal seamlines avoid crossing many obvious objects, we first design a simple but effective criterion in the gradient domain in lieu of the traditionally used intensity domain to measure the visibility of the seam. Thereafter, we fuse this new criterion into the graph cuts energy minimisation framework to globally find the last optimal seamlines. Instead of finding the optimal solutions of seamlines in overlap regions via graph cuts among the entire set of pixels, we first find them among superpixels created from input images and then refine them in the pixel level, which greatly improves the efficiency of the global graph cuts energy optimisation because the number of elements in graph cuts dramatically decreases. Experimental results on orthoimages show that our proposed method is capable of finding high-quality seamlines for orthoimage mosaicking, and outperforms state-of-the-art algorithms and software.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://doi.org/10.1080/01431161.2018.1447164'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---
