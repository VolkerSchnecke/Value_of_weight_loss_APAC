# Value of weight loss models for countries in Asia

Estimating the clinical and economic benefit of weight loss for Australia, South Korea, Thailand, and India

### Introduction

People living with obesity have a high risk of being diagnosed with obesity-related comorbidities (ORCs), such as type 2 diabetes, hypertension, sleep apnoea, or hip/knee osteoarthritis.
Using real-world data, in particular electronic medical records, it has been shown that weight loss is associated with lower risk of future diagnoses of ORCs while individuals age.
The simulation models in this repository attempt to quantify the clinical and economic benefit of weight loss for representative cohorts of individuals living with obesity in four countries in the Asia-Pacific (APAC) region.

### Model background

The simulation models estimate the burden of obesity for four countries in region APAC and visualise the 10-year outlook for two scenarios:

* **Stable-weight scenario:** Expected incidence ORC diagnoses and associated treatment costs for the cohort with today's weight distribution.

* **Weight-loss scencario**: Expected incidence ORC diagnoses and associated treatment costs if today's cohort had a uniform lower weight.

The value of the weight loss are the reduction in treatment costs when comparing the weight-loss scenario with the stable-weight scenario.

The estimation of incidence diagnoses is based on an risk engine derived from UK electronic medical records. 
The simulation cohorts of people with age 20-69 years and BMI 25-50 were generated based local demographics and available obesity and/or type 2 diabetes prevalence.

### Publication

The risk engine used in the simulation is an extension of the model described in https://dom-pubs.pericles-prod.literatumonline.com/doi/10.1111/dom.15154.

Details in the simulation for the four APAC countries can be found in a manscript that is currently under review.

