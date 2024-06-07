# Table of Contents
L1 == Lecture 1; T3 == Task 3


| Topic                          | Lecture                                                                                                                                                           | Hands-on                                                                                                                                            |
|:-------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------|
| Intro                          | L01: Why, what, how<br>  What we cover<br>  F(inputs) -> outputs<br>                                                                                              |                                                                                                                                                     |
|                                |                                                                                                                                                                   |                                                                                                                                                     |
| Get hands dirty                |                                                                                                                                                                   | T01: Start coding a glacier mass balance model: the melt function                                                                                   |
|                                |                                                                                                                                                                   |                                                                                                                                                     |
| Version control with Git       | L02: What is version control<br> Why use it <br>Short intro to git <br>How to collaborate on code<br>As we go along: more advanced git (merge, pull request, etc) | T02: team up someone, create a git repository on GitHub<br> give access to the other person<br> add melt function                                   |
|                                |                                                                                                                                                                   |                                                                                                                                                     |
|                                |                                                                                                                                                                   | T03: work separately on precipitation function and lapse rate function.  Merge to code with git                                                     |
|                                |                                                                                                                                                                   |                                                                                                                                                     |
| Testing code                   | [L03:](lectures/testing.md) Why testing code is a good idea<br>Unit tests, integration tests<br>examples                                                          | T04: test the mel, precipitation and lapse function with "assertions"                                                                               |
|                                |                                                                                                                                                                   |                                                                                                                                                     |
|                                |                                                                                                                                                                   | T05: review, correct and accept Pull Request for integrated mass balance functions                                                                  |
|                                |                                                                                                                                                                   |                                                                                                                                                     |
|                                |                                                                                                                                                                   | T06: make an example, including a plot of the synthetic temperature                                                                                 |
|                                |                                                                                                                                                                   |                                                                                                                                                     |
| Folder structure of model code | L04: How to best structure the files & directories for model code (and other package-like code)                                                                   | T07: update folder structure of code                                                                                                                |
|                                |                                                                                                                                                                   |                                                                                                                                                     |
| Reproducible model runs        | L05: Storing information about the current repo state with results                                                                                                | T08: make a function which returns a file-name containing the Git-hash of the current commit.<br>Store the temperature plot using such a file name. |
|                                |                                                                                                                                                                   |                                                                                                                                                     |
| Dependency management          | [L06:](lectures/dependencies,md) Dependency management: how to install and keep track of code dependencies                                                                                   | T09: make a project environment (with conda, renv or Pkg); Add the plotting library as dependency                                                   |
|                                |                                                                                                                                                                   |                                                                                                                                                     |
| Documentation                  | [L07:](lectures/documentation.md) Writing pragmatic documentation                                                                                                 | T10: write docs: docs strings, Readme (why don't you try ChatGPT)                                                                                   |
|                                |                                                                                                                                                                   |                                                                                                                                                     |
| Licenses                       | L08: Why do I need a license?  What license to choose?  Opens source licences                                                                                     | T11: add LICENSE file, including a copyright notice                                                                                                 |
|                                |                                                                                                                                                                   |                                                                                                                                                     |
| Doing a science project        | L09: How to do science with our model? Keeping track of things.  Folder structure.<br>  Making it reproducible                                                    | T12: setup a suitable folder structure.  Move the code git repository to `code/`                                                                    |
|                                |                                                                                                                                                                   |                                                                                                                                                     |
| Reproducible data handling I   | L10: How can input data be handled such that it provenience and (pre)processing is clear: script it all                                                           | T13: make a data download function; make a post processing function (here just unzip)                                                               |
|                                |                                                                                                                                                                   |                                                                                                                                                     |
|                                |                                                                                                                                                                   | T14: get the data: temperature data, digital elevation model, glacier-mask                                                                          |
|                                |                                                                                                                                                                   |                                                                                                                                                     |
| Reproducible data handling II  | L11: Real data is complicated, what about all the edge cases, hand edits, etc?                                                                                    |                                                                                                                                                     |
|                                |                                                                                                                                                                   |                                                                                                                                                     |
|                                |                                                                                                                                                                   | T15: running it all                                                                                                                                 |
|                                |                                                                                                                                                                   |                                                                                                                                                     |
|                                |                                                                                                                                                                   | T16: share the code with another team and make it run                                                                                               |
|                                |                                                                                                                                                                   |                                                                                                                                                     |
| Publishing your data and code  | L12: How to publish your open science.  Envidat, ResearchCollection, Zenodo, etc.                                                                                 |                                                                                                                                                     |