<!-- README.md is generated from README.Rmd. Please edit that file -->
**Network Regularization (netreg)**
===================================

The netreg algorithm is a continually maintained R package.

Program developers are invited to submit changes here at the GitHub
repository.

**The Basics**
==============

-   Missing data is not a problem.

-   Heterogeneous data is not a problem:

    -   No “group” or “common” network map will be forced unless it
        truly describes the majority.

    -   Individual-level nuances will surface after a group or common
        network map is derived (provided one exists).

    -   If desired, subgroups of individuals with similar patterns of
        effects will be generated to aid the researcher in finding
        similar patterns among the varied individual models.

-   Supports a large number of observed variables (capable of estimating
    a whole-brain network map).

    -   Alternatively can support interaction effects between endogenous
        variables, or between exogenous and endogenous variables.

-   Can be freely downloaded by installing the package “netreg” in R.

**Running netreg**
==================

**1. Create two new folders (i.e., directories)**

-   Create a source folder for your time series. This can be anywhere
    that you have permission to read and write.

-   Nothing can be in the source folder other than the time series data.

-   Create an output folder for your results. This must be different
    from the above folder. Alternatively, specifying an output folder
    will cause one to be created if permissions allow.
