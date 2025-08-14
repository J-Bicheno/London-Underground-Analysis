# London Underground Usage: Analysis and Visualisation

**London Underground Usage: Analysis and Visualisation** is a deep dive into 2 datasets with the purpose of gaining insights into how the Underground is used throughout an annual period

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Dataset Content
* I chose 2 datasets for this project, one was the 2024-2025 Station Footfall data from TfL (Transport for London)
* The other was a list of all Underground stations and their lat and lon coordinates

## Business Requirements
* My top requiremnt was for the dataset to be visulaised at the end in the easiest to understand format possible with as much information as possible

## Hypothesis and how to validate?
* My Hypothesis is that overall usage would go up over time, as more and more jobs are created everyday in London as well as the population increasing
* The best way to validate this would be a line chart of Date vs Entry Count 

## Project Plan
* My first step was to find a dataset that fit my requiremnts, this ended up being two
* I endeavoured to keep the integrity of the data as best as possible through the ETL and manipulation processes

## The rationale to map the business requirements to the Data Visualisations
* I decided on a scatter map box plot to map the business requirement. having the stations with the backdrop of the map makes it easy to spot geographical patterns.

## Analysis techniques used
* I employed descriptive and diagnostic analysis in my approach to understand the data and the reasons for it being that way.
* I started off with descriptive analytics for each visualisation to give an overview of what the data tells us, then employed diagnostic methods to understand the cause
* Initially the first dataset was a limitation as it had no coordinates, but this was quickly fixed by merging a dataset with the necessary information
* I primarily used gen AI such as ChatGPT to brainstorm potention routes for analysis as well as what data visualisations to use

## Ethical considerations
* The dataset was obtained from the TfL open data website 

## Development Roadmap
* I noticed during the ETL stage that the Kings Cross St Pancras station could cause a problem, its a hybrid station and an international hub as well as an underground station but the data for Underground footfall was not seperate. As this would be a major outlier and could prove to give false insights I decided to exclude it from my analysis as it's purely focus on Underground stations
* I'm really going to focus on data visulaisation techniques as I found the stage difficult in comparison to ETL

## Main Data Analysis Libraries
* Pandas for ETL and data manipulation
* Matplotlib for basic plots like line and bar plots
* Seaborn for advanced plots like heatmaps and violin plots
* Plotly for interactive plots like box and map scatter plots
