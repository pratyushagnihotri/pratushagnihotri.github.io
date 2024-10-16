---
title: 'ZeroTune: Learned Zero-Shot Cost Models for Parallelism Tuning in Stream Processing'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Pratyush Agnihotri, Boris Koldehofe, Paul Stiegele, Roman Heinrich, Carsten Binnig, Manisha Luthra

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2013-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Accepted and to be appeared in IEEE 40th International Conference on Data Engineering (ICDE)
publication_short:  Accepted and to be appeared ICDE

abstract: This paper introduces ZeroTune, a novel cost model for parallel and distributed stream processing that can be used to effectively set initial parallelism degrees of streaming queries. Unlike existing models, which rely majorly on online learning statistics that are non-transferable, context-specific, and require extensive training, ZeroTune proposes data-efficient zero-shot learning techniques that enable very accurate cost predictions without having observed any query deployment. To overcome these challenges, we propose ZeroTune, a graph neural network architecture that can learn from the structural complexity of parallel distributed stream processing systems, enabling them to adapt to unseen workloads and hardware configurations. In our experiments, we show when integrating ZeroTune in a distributed streaming system such as Apache Flink, we can accurately set the degree of parallelism, showing an average speed-up of around 5× in comparison to existing approaches.

# Summary. An optional shortened abstract.
summary: This paper introduces ZeroTune, a novel cost model for parallel and distributed stream processing that can be used to effectively set initial parallelism degrees of streaming queries.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/10598043'
url_code: 'https://github.com/pratyushagnihotri/ZeroTune'
#url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

