# Workplace-Project-ExploreAI
# Insurance Fraud

![](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white)

## Table of contents
* [1. Project Overview](#project-description)
* [2. Dataset](#dataset)
* [3. Packages](#packages)
* [4. Environment](#environment)
* [5. Team Members](#team-members)

## 1. Project Overview <a class="anchor" id="project-description"></a>
Insurance plays a vital role in the economy by providing financial security and stability, which enables economic growth and development.Insurance fraud not only affects insurance companies but also has broader economic and social impacts, leading to higher costs for consumers, financial instability, and reduced accessibility to insurance.

Insurance fraud occurs when individuals collaborate to submit false or inflated claims for property damage or personal injuries after an accident. Common tactics include orchestrating accidents intentionally, using ‘phantom passengers’ who were not present at the scene but claim severe injuries, and exaggerating the extent of personal injuries to receive higher compensation.

## 2. Dataset <a class="anchor" id="dataset"></a>
The dataset contains the details about various insurance claims and whether they was fraud reported on the claim or not.

**Key Dataset Features:**
- policy_bind_date: Starting date of the insurance policy.
- policy_csl: Combined Single Limits - This is the maximum value of the insurer will pay out per incident.
- policy_annual_premium: The total dollar amount for the yearly premium.
- umbrella_limit: Extra insurance that provides protection beyond existing limits and coverages of other policies.
- auto_make: Vehicle brand.
- auto_model: Vehicle model.
- insured_education_level: Highest qualification of the insurer.
- policy_deductable: Excess payment before a payout or service is conducted.
- insured_occupation: The profession in which the insurer works.
- Fraud_reported: Y - a fraudelent or false claim, N - a legit and valid claim.



## 3. Packages <a class="anchor" id="packages"></a>

To carry out all the objectives for this repo, the following necessary dependencies were loaded:
+ `Pandas 2.2.2` and `Numpy 1.26`
+ `Matplotlib 3.8.4`
 

## 4. Environment <a class="anchor" id="environment"></a>

It's highly recommended to use a virtual environment for your projects, there are many ways to do this; we've outlined one such method below. Make sure to regularly update this section. This way, anyone who clones your repository will know exactly what steps to follow to prepare the necessary environment. The instructions provided here should enable a person to clone your repo and quickly get started.

### Create the new evironment - you only need to do this once

```bash
# create the conda environment
conda create --name <env>
```

### This is how you activate the virtual environment in a terminal and install the project dependencies

```bash
# activate the virtual environment
conda activate <env>
# install the pip package
conda install pip
# install the requirements for this project
pip install -r requirements.txt
```
