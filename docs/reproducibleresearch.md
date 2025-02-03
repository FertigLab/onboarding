---
layout: default
title: Reproducible Research
nav_order: 11
---

# Reproducible research
{: .no_toc }

{: .no_toc .text-delta }

1. TOC
{:toc}

---


## General expectations
FertigLab supports practices to facilitate reproducible research. New algorithms will be developed and deposited to R/Bioconductor packages or similar. Lab members are also encouraged to follow good coding practices, including commenting of code, readable variable names, etc. I encourage trainees to share emerging protocols for coding and reproducible research with the entire group. 

Computational lab members are expected to maintain their code on GitHub to maintain a record. All lab members working in the wet lab are expected to maintain a traditional lab notebook, in keeping with the procedures of the PI of that lab. These notebooks will be property of either the PI running that lab or Elana depending on the project.

## Code management
Lab members are expected to follow the present code management guidelines to ensure reproducible and maintainable code.

## Review
* Changes to packages and other important code repositories shall be reviewed; if the main branch of a repository is locked, it means the repository is important;
* Genomics studies of clinical data will undergo mandatory, independent code review prior to submission for publication
* A review is requested by adding a request in #codereview slack channel, review start/intention is confirmed with a ::looking:: and conclusion is marked with a ::white_check_mark:: emoji.

## General guidelines
* There shall be no absolute local paths in the shared code;
* Function lengths should generally not exceed 100 lines of code;
* Function and variable names shall be consistenly written in snake_case or camelCase unless other standard is specified;
* If an action is repeated multiple times, a function should be used instead of repeating code;
* In `R`, namespaces should be explicitly used, e.g. `Matrix::t()` instead of `t()`;
* It's a good idea to use a linter while writing code;
* No code should be left commented out - keep it or discard it;
* Comments in code should elaborate on the why and not the what, the latter should be understable from variable/function names;

## Additions for software Packages
* Package development generally should be done in a feature branch, following the creation of an issue with description of the new functinality;
* Issue descriptions should include a preamble, current state and desired state if applicable, bug issues shall include a reproducible example;
* Main / master branch should be locked if the package is released;
* Automated checks should be run via github actions;
* Regression tests should accompany changes in existing functionality;
* Unit tests should accompany new functions created;
* For bug fixing, consider test-driven development: create a test that fails (commit it to record the failure) and prove it's fixed by observing the test pass after working on the bug;

## Additions for ad-hoc analysis
* Analysis scripts should be able run on other than author computers out of the box;
* Environment managers such as `conda`, `venv` should be used to store and share package versions where possible (`python`), for R the result of `sessionInfo()` or a custom script should be used to export those; 




<!-- just_the_docs:
  # Define which collections are used in just-the-docs
  collections:
    # Reference the "tests" collection
    tests:
      # Give the collection a name
      name: Tests
      # Exclude the collection from the navigation
      # Supports true or false (default)
      # nav_exclude: true
      # Fold the collection in the navigation
      # Supports true or false (default)
      # nav_fold: true  # note: this option is new in v0.4
      # Exclude the collection from the search
      # Supports true or false (default)
      # search_exclude: true -->
