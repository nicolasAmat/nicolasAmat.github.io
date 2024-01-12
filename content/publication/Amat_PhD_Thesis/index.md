---
title: "PhD Thesis: A polyhedral Framework for Reachability Problems in Petri Nets"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin


date: "2023-12-04T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-06-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: "INSA Toulouse"
publication_short: ""

abstract: "We propose and study a method to accelerate the
verification of reachability problems in Petri nets based on structural
reductions. This approach, that we call polyhedral reduction, relies on a state space abstraction that combines
structural reductions and linear arithmetic constraints on the marking of
places.\n

The correctness of this method is based on a new notion of equivalence
between nets. Combined with an SMT-based model checker, one can transform a
reachability problem about some Petri net, into the verification of an
equivalent reachability property on a reduced version of this net. We also
propose an automated procedure to prove that such an abstraction is correct,
exploiting a connection with a class of Petri nets with Presburger-definable
reachability sets.\n

In addition, we present a data structure, called Token Flow Graph
(TFG), that captures the particular structure of constraints stemming from
structural reductions. We leverage TFGs to efficiently solve two problems.
First, to eliminate quantifiers that appear during our transformation, in the
updated formula to be checked on the reduced net. Second, to compute the
concurrency relation of a net, that is all pairs of places that can be marked
simultaneously in some reachable marking.\n

We apply our approach to several symbolic model checking procedures
and introduce a new semi-decision procedure for checking reachability properties
in Petri nets based on the Property Directed Reachability (PDR) method. A
distinctive feature of this PDR method is its ability to generate verdict
certificates that can be verified using an external SMT solver.\n

Our approach and algorithms are implemented in four open-source tools:
SMPT for checking reachability properties; Kong for accelerating the computation
of concurrent places; Octant for eliminating quantifiers; and Reductron for
automatically proving the correctness of polyhedral reductions. We give
experimental results about their effectiveness, both for bounded and unbounded
nets, using a large benchmark provided by the Model Checking Contest. We focus
on the reproducibility of our results and provide an accompanying artifact that
covers all our experiments."


# Summary. An optional shortened abstract.
summary: ""

tags: []

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
url_slides: 'slides/Amat_PhD_Thesis.pdf'
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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---


