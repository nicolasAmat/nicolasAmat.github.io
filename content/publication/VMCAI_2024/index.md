---
title: "Project and Conquer: Fast Quantifier Elimination for Checking Petri Net Reachability"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Silvano Dal Zilio
- Didier Le Botlan


date: "2024-01-15T00:00:00Z"
doi: "10.1007/978-3-030-99524-9_28"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-04-06T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Verification, Model Checking, and Abstract Interpretation"
publication_short: "VMCAI"

abstract: "We propose a method for checking generalized reachability properties in Petri nets that takes advantage of structural reductions and that can be used, transparently, as a pre-processing step of existing model-checkers. Our approach is based on a new procedure that can project a property, about an initial Petri net, into an equivalent formula that only refers to the reduced version of this net. Our projection is defined as a variable elimination procedure for linear integer arithmetic tailored to the specific kind of constraints we handle. It has linear complexity, is guaranteed to return a sound property, and makes use of a simple condition to detect when the result is exact. Experimental results show that our approach works well in practice and that it can be useful even when there is only a limited amount of reductions."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Petri nets", "Quantifier elimination", "Reachability problems"]

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
projects: ["Octant"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---


