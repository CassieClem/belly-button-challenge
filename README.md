# belly-button-challenge
## Module 14 Challenge

In this assignment, I created an interactive dashboard to dive into the Belly Button Biodiversity dataset. This dataset deals with the microbes that are found in the human navel.

The data reveals that a handful of microbial species are present in more than 70% of people, while the rest can be seen as relatively rare. These are called operational taxonomic units, or OTUs in this study. 

## Horizontal Bar Chart

The D3 library to used to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.
A horizontal bar chart with use of the dropdown menu allows the top 10 OTUs to be shown per sample.
Sample_values was used as the values for the bar chart.
Otu_ids was used as the label for the bar chart.
Otu_labels was used as the hovertext for the chart.

## Bubble Chart

A bubble chart was created to display each sample. The 'otu_ids' was used the for x values and the colors for the markers. 
The 'sample_values' was used for the y values as well as the marker size. The 'otu_labels' for the text values was used. 
The sample metadata, i.e., an individual's demographic information was used to display the information.

![demographic](https://github.com/CassieClem/belly-button-challenge/blob/main/photos/Demographic%20Info.jpg)

Then the display was made for each key-value pair from the metadata JSON object on the page.
The plots in case a new sample is selected. Additionally, a layout was created for the dashboard. 

![bubble](https://github.com/CassieClem/belly-button-challenge/blob/main/photos/Bubble%20Chart.jpg)


To see the static page, please see the following: 
[GitHub Pages](file:///C:/Users/knuck/OneDrive/Desktop/belly-button-challenge/index.html)


## Gauge Chart

The Gauge Chart was adapted from [Plotly](https://plotly.com/python/gauge-charts/) to plot the weekly washing frequency of each individual.
The example gauge code seen on the website took into account for values ranging from 0 through 9. Also, the chart updated in case a new sample is selected. 
Here is the result: 
![gauge](https://github.com/CassieClem/belly-button-challenge/blob/main/photos/Gauge%20Chart.jpg)
