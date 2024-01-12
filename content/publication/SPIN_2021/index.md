---
title: "Accelerating the Computation of Dead and Concurrent Places Using Reductions"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Silvano Dal Zilio
- Didier Le Botlan


date: "2021-07-12T00:00:00Z"
doi: "10.1007/978-3-030-84629-9_3"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-07-12T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "International Symposium on Model Checking Software"
publication_short: "SPIN"

abstract: We propose a new method for accelerating the computation of a concurrency relation, that is all pairs of places in a Petri net that can be marked together. Our approach relies on a state space abstraction, that involves a mix between structural reductions and linear algebra, and a new data-structure that is specifically designed for our task. Our algorithms are implemented in a tool, called Kong, that we test on a large collection of models used during the 2020 edition of the Model Checking Contest. Our experiments show that the approach works well, even when a moderate amount of reductions applies.

# Summary. An optional shortened abstract.
summary:

tags: ["Petri Nets", "Concurrent Places", "Structural Reductions"]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'slides/SPIN_2021.pdf'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image: ""
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  # focal_point: ""
  # preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ["Kong"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---


