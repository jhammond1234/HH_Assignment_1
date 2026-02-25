# Assignment 1: Reproducible Time-Series Analysis, Temporal Scaling, and Visualization

<img width="578" height="771" alt="image" src="https://github.com/user-attachments/assets/9f7ae445-653f-4ae1-93a3-365c56f1dfd2" />


## Overview
This repository contains the raw data and analysis for four streamgage locations in Idaho. The analysis for these locations is located in a Jupyter notebook within the notebooks folder. This analysis consists of three tasks: the first of which involved plotting the daily streamflow for each gauge against one another, for direct comparison, as well as on their own subplots, so that the patterns within each location could be more easily recognized. The second task had us temporally rescale the data, by converting the data to weekly averages and monthly volumetric values. The final task had us compare a site in a headwater catchment to a site below a reservoir. 

## Repository Structure
- 'data/' - raw or processed datasets (or instructions for download)
- 'notebooks/' - Jupyter notebooks containing analysis
- 'p310env.yml' - Conda environemnt file for reproducibility

## Environment Setup
To recreate the environment: 

'''bash 
conda env create -f p310env.yml
conda activate p310env

## Data
- ID 13306385 is NAPIAS CREEK BELOW ARNETT CREEK NEAR LEESBURG, ID. This is a HEADWATER site
- ID 13039500 is HENRYS FORK NR LAKE ID, below Henrys Lake. This a site below a reservoir
- ID 13237920 is MIDDLE FORK PAYETTE RIVER NR CROUCH ID. This is a HEADWATER site
- ID 13247500 is PAYETTE RIVER NR HORSESHOE BEND ID. This is below a damn somewhere upstream, but also has other upstream free flowing tributaries. 

