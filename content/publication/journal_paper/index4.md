---
title: 'Visualizing, clustering, and characterizing activity-trip sequences via weighted sequence alignment and functional data analysis'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ying Song
  - Siyang Ren
  - Julian Wolfson
  - admin
  - Roland Brown
  - Yingling Fan
  

# Author notes (optional)
author_notes:

date: '2021-05-01'
doi: 'https://doi.org/10.1016/j.trc.2021.103007'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-05-01'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *Transportation Research Part C Emerging Technologies*
publication_short: ''

abstract: Smartphone-based activity-travel surveys have enabled the collection of continuous, multi-day data on individuals’ trips and activities with high spatial and temporal resolution. However, the multi-dimensional nature of these data makes it challenging to compare activity-travel patterns and identify clusters of individuals with similar patterns and use them to study behaviors and forecast travel demands. To address this challenge, we adopt a discrete, step-based view on time and transform the episodic-based diary into a sequence of states observed at a sample interval. The resulting sequences can visually characterize variations in activity-travel patterns across days of a week and among different individuals. Motivated by techniques in genomics and data science, we apply sequence alignment methods to measure the pairwise similarity between these activity-trip sequences. To address its practical implementation in transportation studies, we define and compare four weighting schemas (1) the unit-cost distance, which assigns equal weights to all substitution operations between states; (2) the fixed-flexible weighted distance based on the time geography framework, where costs differ for substitutions involving fixed and flexible activities; (3) the trip-activity weighted distance considering travel as a derived demand, where costs differ for substitutions between trips and activities; and (4) transition-based weighted distance, where costs are based on the global or time-varying activity and trip transition rates estimated from the data. Then, we calculate the pairwise distances between individuals’ sequences and use them as inputs to a hierarchical clustering algorithm to group individuals with similar sequences. We visualize the state distributions of the identified clusters to infer and compare behavior patterns, and use functional data regression methods to estimate the time-dependent probabilities of engaging in various activities and trips. To demonstrate our methods, we analyze a smartphone-based survey dataset collected in the Minneapolis-St. Paul metropolitan area. We also conduct sensitivity analysis on the selection of cost metrics and sample intervals to ensure the robustness of our methods and discuss their implications in practice. By identifying population subgroups with distinct daily activity-travel patterns and explaining how these patterns vary over one day and depend on user profiles, our weighted sequence alignment approach provides an intuitive and flexible method for extracting and characterizing individuals’ activity-travel behaviors for use in transportation planning.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://doi.org/10.1016/j.trc.2021.103007'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---
