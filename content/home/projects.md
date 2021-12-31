---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

title: Research
subtitle: 'Adventure and voyage of discovery'

content:
  # Page type to display. E.g. project.
  page_type: project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
  - name: All
    tag: '*'
  - name: Interpretable ML
    tag: Interpretable Machine Learning
  - name: Medical Imaging
    tag: Medical Imaging
  - name: Deep Learning
    tag: Deep Learning
  - name: Graph ML
    tag: Graph Machine Learning
  - name: Bioinformatics
    tag: Bioinformatics
  
design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---

We aim to develop translational AI technologies for better analysing multimodal data in healthcare and beyond, particularly multidimensional data and heterogeneous graphs in bioinformatics and medical imaging. More specifically, we build knowledge-aware machine learning tools for learning useful features from multidimensional data and analysing complex relationships in graphs/networks via tensor-based, graph-based, and related methods.

See selected research projects below, which can be filtered by the tags. Explore a [list of all projects >>](./project/)
