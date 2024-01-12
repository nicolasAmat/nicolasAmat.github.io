---
title: "A Polyhedral Abstraction for Petri nets and its Application to SMT-Based Model Checking"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Bernard Berthomieu
- Silvano Dal Zilio


date: "2022-10-24T00:00:00Z"
doi: "10.3233/FI-222134"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-10-24T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Fundamenta Informaticae"
publication_short: "FI"

abstract: "We define a new method for taking advantage of net reductions in combination with a SMT-based model checker. Our approach consists in transforming a reachability problem about some Petri net, into the verification of an updated reachability property on a reduced version of this net. This method relies on a new state space abstraction based on systems of constraints, called polyhedral abstraction. We prove the correctness of this method using a new notion of equivalence between nets. We provide a complete framework to define and check the correctness of equivalence judgements; prove that this relation is a congruence; and give examples of basic equivalence relations that derive from structural reductions. Our approach has been implemented in a tool, named SMPT, that provides two main procedures: Bounded Model Checking (BMC) and Property Directed Reachability (PDR). Each procedure has been adapted in order to use reductions and to work with arbitrary Petri nets. We tested SMPT on a large collection of queries used in the Model Checking Contest. Our experimental results show that our approach works well, even when we only have a moderate amount of reductions."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Petri nets", "Model Checking", "Reachability", "SMT solving", "Abstraction techniques"]

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
projects: ["SMPT"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
