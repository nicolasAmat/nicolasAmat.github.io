---
title: "Leveraging polyhedral reductions for solving Petri net reachability problems"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Silvano Dal Zilio
- Didier Le Botlan


date: "2022-12-22T00:00:00Z"
doi: "10.1007/s10009-022-00694-8"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-12-22T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "International Journal on Software Tools for Technology Transfer"
publication_short: "STTT"

abstract: "We propose a new method that takes advantage of structural reductions to accelerate the verification of reachability properties on Petri nets. Our approach relies on a state space abstraction, called polyhedral abstraction, which involves a combination between structural reductions and sets of linear arithmetic constraints between the marking of places. We propose a new data structure, called a Token Flow Graph (TFG), that captures the particular structure of constraints occurring in polyhedral abstractions. We leverage TFGs to efficiently solve two reachability problems: first to check the reachability of a given marking and then to compute the concurrency relation of a net, that is, all pairs of places that can be marked together in some reachable marking. Our algorithms are implemented in a tool, called Kong, that we evaluate on a large collection of models used during the 2020 edition of the Model Checking Contest. Our experiments show that the approach works well, even when a moderate amount of reductions applies."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Petri nets", "Structural reductions", "Reachability", "Concurrent places"]

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
url_slides: ''
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
