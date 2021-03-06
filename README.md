# Predicting Adult Obesity Rate from Food Environment Factors

The [FEA](https://www.ers.usda.gov/data-products/food-environment-atlas/) is a publicly available dataset compiled by the US Department of Agriculture. According to the website, 

>Food environment factors—such as store/restaurant proximity, food prices, food and nutrition assistance programs, and community characteristics—interact to influence food choices and diet quality. These interactions are complex and more research is needed to identify causal relationships and effective policy interventions.

>The objectives of the Atlas are:

>to assemble statistics on food environment indicators to stimulate research on the determinants of food choices and diet quality, and
to provide a spatial overview of a community's ability to access healthy food and its success in doing so."

This is a compilation of over 275 food environment indicators for every U.S. county. The data were collected from a variety of sources between the years 2007 and 2016. We supplement this data set with [2013 US Census data](https://www.census.gov/data/datasets/2013/demo/saipe/2013-state-and-county.html) on poverty and income per US county.

Objective: predict the 2013 adult obesity rate for each US county (see the [documentation](https://www.ers.usda.gov/data-products/food-environment-atlas/documentation/) for more details) based on the available data. 

![alt text](https://github.com/jieunchoi/food_env_atlas/blob/master/img/orate_prate.png)

Project inspired by the list [here](https://medium.com/datadriveninvestor/the-50-best-public-datasets-for-machine-learning-d80e9f030279).
Very loosely followed [this guideline](https://towardsdatascience.com/a-complete-machine-learning-walk-through-in-python-part-one-c62152f39420) for ML project workflow.

The project notebook can be viewed online [here](https://nbviewer.jupyter.org/github/jieunchoi/food_env_atlas/blob/master/FEA.ipynb) at https://nbviewer.jupyter.org/.
