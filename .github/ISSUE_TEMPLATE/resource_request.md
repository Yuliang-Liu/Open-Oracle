---
name: Add paper / dataset / resource
description: Suggest a new oracle bone inscription resource for Open-Oracle
title: "[Resource] "
labels: [resource]
body:
  - type: input
    id: title
    attributes:
      label: Title
      description: Paper, dataset, codebase, benchmark, or website title.
    validations:
      required: true
  - type: input
    id: venue
    attributes:
      label: Venue / year
      placeholder: e.g., ACL 2025, Scientific Data 2026, arXiv 2025
  - type: dropdown
    id: category
    attributes:
      label: Category
      options:
        - Dataset / benchmark
        - Recognition / classification
        - Detection / segmentation
        - Retrieval
        - Rejoining
        - Restoration / generation
        - Decipherment / interpretation
        - Survey / resource
        - Other
  - type: textarea
    id: links
    attributes:
      label: Links
      description: Official paper, DOI/arXiv/OpenReview, code, data, project page.
      placeholder: |
        Paper:
        Code:
        Data:
  - type: textarea
    id: summary
    attributes:
      label: One-line summary
      description: What should readers know about this resource?
    validations:
      required: true
