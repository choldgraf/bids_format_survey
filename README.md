# The BIDS neuro data format survey

A repository to share and analyze the BIDS format survey data.

**Run this interactively in Binder by clicking the badge below**

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/choldgraf/bids_format_survey/master)

## Site structure

* `data/counts_current.csv` - A cleaned version of the data formats that respondants currently use.
* `data/counts_future.csv` - A cleaned version of the data formats that respondants would be *willing* to use.
* `data/counts_kind.csv` - A cleaned version of the modality that respondants use.
* `data/institutions.csv` - A list of the location of all institutions in responses (inferred from geopy).
* `analyze_bids_survey.ipynb` - A notebook that runs some simple analyses / visualizations on the response data.