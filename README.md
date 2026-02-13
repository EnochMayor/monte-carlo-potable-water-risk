# Discerning Potable Water Sources using Monte Carlo Simulation (Health Risk Assessment)

## Overview
This project evaluates potable water safety by comparing **boreholes (BHs)** and **hand-dug wells (HWs)** using **deterministic + Monte Carlo probabilistic** health risk assessment.

## Objective
Assess heavy-metal exposure risk (adults vs children) and determine which groundwater source is safer for long-term consumption.

## Approach
- Compiled heavy metal concentration data for BHs and HWs
- Computed non-carcinogenic risk using **Hazard Index (HI)**
- Computed carcinogenic risk using **Lifetime Cancer Risk (LTCR)**
- Ran **Monte Carlo simulation** to quantify uncertainty and probability of exceeding risk thresholds
- Interpreted pollution indices and source apportionment (natural vs anthropogenic contributors)

## Key findings (high level)
- **Children show substantially higher risk sensitivity** than adults under the same exposure assumptions.
- **Boreholes generally indicate better water quality**, while **hand-dug wells are more impacted**, driven by metals such as Pb, Zn, and Cr.
- Under probabilistic assessment, risk exceedance likelihood was notably higher for children in specific exposure pathways.

## Why this matters
This workflow supports evidence-based decisions on **which source is safer**, and highlights where monitoring, treatment, or source protection is most urgent—especially for child health protection.

## Tools
Python (simulation + risk calculations) • statistical analysis • reporting workflow

