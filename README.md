# How Jupyter makes experimental and computational collaborations easy

This repository contains the slides and materials for my talk at JupyterCon 2017.


## Slides

If you have internet connection, you can view the slides online here: [zsailer.github.io/jupytercon-2017]

To run these slides locally, clone the repo and uses `npm` to install and serve.

```
git clone https://github.com/Zsailer/jupytercon-2017
cd jupytercon-2017
git submodule update --init
npm install
npm start
```

## Abstract

### Who is this presentation for?

Principal investigators, members of computational research groups, and graduate students

### Prerequisite knowledge

A basic knowledge of Python and the Jupyter Notebook

### What you'll learn

* Learn how to create simple-to-repeat, accessible notebooks for research collaborators, how to deploy JupyterHub on a local server for a small research group, and how to write simple graphic interfaces using ipywidgets that can help collaborators navigate your analyses
* Understand best practices for publishing notebooks as supplements to research publications

### Description

Collaboration between computational and experimental research groups is foundational to science. The most effective collaboration involves experimentalists gathering data, computational scientists developing code to analyze that data, and the two groups working together to interpret the results. However, computational scientists recognize this can be challenging, as their experimental collaborators do not find staring at code quite as helpful.

If you want a headache-free collaboration between experimental and computational research groups, you need to get code out of the way. How do you develop simple-to-repeat, accessible programs that make your collaborators happy?

Zach Sailer highlights various ways in which the Jupyter “sphere” has improved collaboration with experimental groups and shares a real-world example of working together with experimentalists in Australia to tackle the problem of predicting drug resistance in unknown malarial strains. Zach explains how the team used JupyterHub to host a private, centralized server that was shared with their collaborators, making uploading and downloading data and analyses simple and secure, how they used the Jupyter Notebook and ipywidgets to make their computational analyses more accessible, interactive, and reproducible for their collaborators, and how they openly shared Jupyter notebooks upon publication, using external web services like GitHub and Binder.

### About Me

**Zach Sailer** (University of Oregon)

Zach Sailer is graduate student at the Harms Lab at the University of Oregon, where he studies the mechanisms that shape protein evolution from a biophysical perspective. Previously, he was a core developer for the IPython/Jupyter team at Cal Poly San Luis Obispo. Zach has created and contributed to various scientific open source projects and is also a strong advocate for open science, working hard to promote and practice open science in all aspects of his research.
