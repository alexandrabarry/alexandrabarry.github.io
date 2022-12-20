---
layout: post
title: Project Introduction
subtitle: Overview of Methods and Background
gh-repo: alexandrabarry/alexandrabarry
tags: [intro]
comments: true
---

## Background
Air pollution has been documented to adversely effect human health and has been estimated to be responsible for five to ten percent of total annual premature mortality in the United States. The most prevalent types of air pollution include fine particulate matter (PM) and ozone, which are responsible for more than 90% of air-pollution related deaths. Within the United States, air pollution varies on several factors including differences in states' prominent industries, population density and personal vehicle use. Although cross-state air pollution does exist, primarily from Wyoming, North Dakota and West Virginia as measured on a per capita basis3, this project evaluates premature death as measured by air pollution by state to assess regional and state-specific trends.


## Data Overview
To assess this primary question, I evaluated data from City Health Dashboard, a project created by the NYU Grossman School of Medicine's Department of Population Health, which aggregates and releases data on over 40 measures of health and drivers of health for 841 cities across the United States4. The dashboard incorporates data from both private and publicly available data sources across the United States in addition to census tract data. The most recent data release from City Health incorporates data from the 2010 and 2020 census data, although data from 2010 was used for this project on account of summarizing a wider range of demographic covariates as compared to 2020.

## Analysis Overview
Evaluated several types of linear regressions were evaluated for best model fit. Each covariate is measured as a percentage of the state population, with further details of estimate calculations reported in the City Health Technical Report. On account of having continuous outcome data (lifespan) and multiple continuous covariates, a linear regression was identified as the optimal model. Upon evaluation of a generalized linear model, a cubic spline, quadratic and generalized additive model were evaluated on account of the distribution of the data. Model selection was based off of visual fit and AIC, which identified the generalized additive model to best fit the data.
