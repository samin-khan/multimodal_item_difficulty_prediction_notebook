# Predicting Data Visualization Item Difficulty with Vision Language Models

This repository contains the analysis notebook and experimental code for a research project on predicting item difficulty in data visualization literacy assessments using large language models and vision language models.

This work was developed as part of the Stanford course: Data Science and the Science of Learning.

If referencing this work, please cite the associated paper:

Author: Samin Khan
Title: Using Vision + Language Models to Predict Item Difficulty
Year: 2026
Venue: arXiv
URL: 
---

## Overview

The goal of this project is to evaluate whether language models and vision language models can estimate performance on data visualization assessment items.

Specifically, we investigate:

* Whether models can predict item difficulty from text alone
* Whether incorporating visual information improves prediction accuracy
* How structured prompting and feature guidance impact performance

The core outcome variable is item difficulty, operationalized from response data.

---

* `dvl_vlms.ipynb`
  Main analysis notebook contains:

  * Data preprocessing
  * Model prompting
  * API calls
  * Prediction generation
  * Correlation and error analysis


Note: Dataset is not included in this repository as the data was provisioned through institutional access at Stanford University for course purposes. 