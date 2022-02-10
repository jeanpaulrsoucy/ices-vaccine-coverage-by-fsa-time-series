# ICES Vaccine Coverage in Ontario by FSA Time Series

This repository contains the code to create a time series of vaccine coverage in Ontario by FSA, derived from datasets made available on the [ICES COVID-19 Dashboard](https://www.ices.on.ca/DAS/AHRQ/COVID-19-Dashboard#vaccinecoverage).

It also contains an additional dataset with the following metrics: cumulative rates of cases, hospitalizations and mortality by FSA and whether the FSA was among the [114 identified for vaccine prioritization by the province in early April 2021](https://toronto.ctvnews.ca/full-list-of-ontario-neighbourhoods-where-the-covid-19-vaccine-will-be-available-to-those-18-1.5379755).

The final datasets are available in the `data` directory in wide format (`fsa_ts.csv`, `fsa_metrics_ts.csv`) and long format (`fsa_ts_long.csv`, `fsa_metrics_ts_long.csv`).

A brief report describes the data: [click here to read as HTML](https://jeanpaulrsoucy.github.io/ices-vaccine-coverage-by-fsa-time-series/fsa_ts.html).
