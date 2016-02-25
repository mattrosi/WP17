# Abstract

- new generation in under-served areas often to high
- we compare survey estimation to observed electricity use


# Introduction

## Global Topic

- global electricity access is poor
- many areas require private capital to install electricity
- part of problem is upfront investment cost
- due to perceived business risk, upfront capital is costly [@JaramilloReview2015]

## Oversizing

- generation is frequently allocated at levels that are too high
- oversized microgrids based on overestimated demand that cannot meet
    revenue targets contribute to this perception [@USAID2015]
- Schnitzer has shown the consequences of generators with excess
    capacity on microgrid operation [@Schnitzer2014]
- Schnitzer Haiti Thesis data can provide evidence
- quantify the level and frequency of generator mismatch
- to avoid excess capacity, systems must be sized appropriately
- accurate sizing requires accurate demand estimation

## Demand estimation informs sizing

- estimating demand in areas without access is challenging (citation)
- through more accurate appliance estimation, we may achieve more
    accurate energy estimation
- with more accurate energy estimation, a micro-utility can reduce
    the variance in revenue
- reductions in revenue variance should lead to lower-cost capital
    [@JaramilloReview2015]
- we explore methods for bottom up estimation of appliance ownership
    and compare to observed electricity consumption

## Contribution

- more accurate forecasting of appliance purchases, use, and resulting
    electricity demand can improve financial performance by improving
    the procurement of power generation equipment
- we use surveys of rural household appliance ownership and compare to
    observed electricity consumption to verify the accuracy of a
    bottom-up method

## literature review of rural energy forecast theory and results

- Schnitzer Thesis
- Paatero
- ASHRAE Fundamentals Ch. 19
- World Bank WPS4866


# Methods

## Overview

- Collect survey data on current per household appliance ownership
- Extrapolate energy usage based on a stochastic simulation of power and
    time of use
    - assume a distribution for the average power use of appliances
    - assume a distribution of average times for appliance usage
- Compare predicted to observed energy usage from metered villages

## This approach

- We compare observed electricity consumption with a bottom-up
    estimation based on appliance survey data

## survey of appliance ownership results

- we observe appliance ownership by household
- appliance ownership varies by connection type
- we observe hours per day and days per week of use
- we assume the power level of appliances
- from this, we create an estimate of the energy per day consumed if all
    appliances working and grid has 100% uptime
- we focus on the five villages covered by grid data

## Appliance Survey Basic Detail

- The survey collected data on electricity use and assets for 1184
    households in the Lake Sentani region
- Electricity access among the surveyed households ranged from grid
    access to village-level access, to only household-level sources of energy
- For the appliance measurements we detail below, we have 417 grid
    surveys, 160 microgrid surveys, and 182 surveys with no
    village-level access
- Of the total households available in a given village, the percentage
    surveyed ranged from 45% to 75%
- We are especially interested in comparisons between different levels
    of access to energy
- The survey was designed and administered by Advancing Energy and Cenderwash University
    as part of an electrification effort in the Lake Sentani region
- The survey used the ODK platform which allows for the electronic
    collection of data from hand-held tablet devices
- The data was stored online using Ona
- We downloaded the data in an Excel format for local analysis

## Basic Survey Results

- 26 Villages were surveyed
- Range of village sizes from X to Y
- Range of percentage of households surveyed per village
- Average households surveyed per village
- Percentage of households surveyed per village
- Percentage of households by access type
- label: summary_table: table with number of villages by access type and number of households

## Survey Questions

- The survey was designed to ask questions relevant to the electricity
    needs of the community
- The survey collects factors on income, assets, appliance ownership,
    willingness to pay, and intention to purchase appliances
- Do you currently own appliance X?
- If electricity available, will you buy appliance X?
- We demonstrate several approaches to estimating eventual ownership

## electricity consumption results

- We observe electricity consumption by village
- Electricity consumption varies by connection type
- We observe 85% or greater uptime for grid connected villages
- We observe 15% to 25% uptime for microgrids

## comparison of predicted and observed electricity use

- Do these low uptimes constrain appliance use and invalidate the study
    predictions?
- How sensitive are our predictions to the assumptions about appliance
    power and the number of light bulbs?

## accuracy of appliance surveys as a prediction tool

- point estimates
- probabilistic estimates


# Results

## Bottom up electricity estimation

- using survey results we estimate the electricity production
- using distributions for appliance power and time of use we create a
    probability distribution of energy use per day

## Appliance ownership variation

### Method
- We observe the overall reported percentage of household reporting
    ownership of each appliance using survey questions
- We report for lighting, mobile phones, television, radio,
    refrigerators, fans, and rice cookers
- We then split the dataset and assign each village to an access type
    (grid, microgrid, no central access)
- We observe the reported percentage of appliance ownership in each
    access type by summing the yes/no response and dividing by the
    number of respondents
- We report the number of valid responses in each category

### Results

- We observe a low variation for TV, lighting, and mobile phone
    ownership across access types
- These are highly desirable services with modest energy requirements
- We observe higher variation for rice cookers and refrigerators with
    ownership concentrated in areas with grid connections
- Since these appliances require greater power and energy, we expect
    grid locations
- We observe variation in radio ownership with concentration of
    ownership in off-grid and community run microgrid areas
- No explanation for this observation
- label: appliance-ownership-by-access-type

![Percent Ownership: Plots percentages of households reporting ownership
of each type of appliance based on current electricity access type.
](figures/appliance-ownership-by-access-type.png)



# Discussion and Conclusion

## Impacts

- this forecasting comparison is valuable to practitioners
- refining estimates will improve revenue and cost of capital long term

## Future work

- longitudinal observations will allow us to observe the growth of
    appliance ownership through acquisition and the accompanying growth
    in electricity use
