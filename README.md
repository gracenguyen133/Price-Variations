# Sourdough Bread Price Analysis in Toronto

## Overview

This repo contains analysis of sourdough bread pricing patterns across major retailers in Toronto from February to July 2024. The analysis explores market segmentation and pricing strategies using Bayesian regression modeling.

## File Structure

The repo is structured as:

-   `data/raw_data` contains the raw data obtained from Project Hammer [@filipp_2024_project].
-   `data/analysis_data` contains the cleaned and standardized price dataset.
-   `model` contains fitted Bayesian regression models and diagnostics.
-   `other` contains LLM interactions and preliminary sketches.
-   `paper`  contains the Quarto document, bibliography, and PDF of the final paper.
-   `scripts` contains R scripts for simulation, data processing, and analysis.

## Statement on LLM usage

This project was developed with assistance from ChatGPT by OpenAI. The LLM was used for
-	Code formatting and optimization
-	Data interpretation
-	Model building
The complete chat history is available in other/llm_usage/usage.txt.

## Reproducibility

All analyses can be reproduced by running the numbered scripts in sequence:
-	Run scripts 00-03 for data preparation
-	Run scripts 04-05 for analysis
-	Run scripts 06-07 for model fitting and validation
-	Render paper.qmd for final output