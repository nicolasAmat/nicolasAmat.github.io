---
title: "A Toolchain to Compute Concurrent Places of Petri Nets"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Pierre Bouvier
- Hubert Garavel


date: "2023-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Petri Nets and Other Models of Concurrency"
publication_short: "ToPNoC"

abstract: "The concurrent places of a Petri net are all pairs of places that may simultaneously have a token in some reachable marking. Concurrent places generalize the usual notion of dead places and are particularly useful for decomposing a Petri net into synchronized automata executing in parallel. We present a state-of-the-art toolchain to compute the concurrent places of a Petri net. This is achieved by a rich combination of various techniques, including: state-space exploration using BDDs, structural rules for concurrent places, quadratic over- and under-approximation of reachable markings, and polyhedral abstraction of the state space based on structural reductions and linear arithmetic constraints on markings. We assess the performance of our toolchain on a large collection of 850 nets originating from the 2022 edition of the Model Checking Contest."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Nested-unit Petri nets", "Model checking", "Reachability problems", "Concurrency theory", "Abstraction techniques", "Structural reductions", "State-space exploration"]

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
