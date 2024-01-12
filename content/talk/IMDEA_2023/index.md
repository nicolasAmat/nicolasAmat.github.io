---
title: "What is polyhedral reduction? ...and how we use it to accelerate the verification of reachability problems for Petri nets."

event: Invited Talk at IMDEA Software Institute
event_url: https://software.imdea.org/events/invited-talks/

location: Madrid, SPAIN

summary: "Invited Talk at IMDEA Software Institute"
abstract: "In this talk, we present a new framework, called polyhedral abstraction, for checking safety properties on Petri nets, that is checking if some reachable state satisfy a property of interest. This is an important and difficult problem with many practical applications: obviously for the formal verification of concurrent systems, but also for the study of diverse types of protocols (such as biological or business processes), the verification of software systems, the analysis of infinite state systems, etc. In this framework, we propose a novel approach that involves reducing the size of the model under study. The key advancement lies in the computation of a set of linear equations, which permits to trace back the reachable states of the original net based on those of the reduced net. We also introduce a new graph structure called Token Flow Graph, specifically designed to capture our reduction equations, for which we address reachability problems by playing a “token game” on the graph. To conclude the presentation, we provide a live demonstration of the tool SMPT, an SMT-based model checker that actively participates in the Model Checking Contest. An exciting feature of the tool is its ability to generate certificates of invariance."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2023-06-20T00:00:00Z"
date_end:
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: "2023-06-20T00:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
---

