# belly-button-challenge
Step 1: Plotly

Use the D3 library to read in samples.json.

Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
Use sample_values as the values for the bar chart.
Use otu_ids as the labels for the bar chart.
Use otu_labels as the hovertext for the chart.
bar chart
![01](https://github.com/Mulugeta25/belly-button-challenge/assets/129996503/38f2027d-d4dd-46e1-9b4c-814014bc4cb5)

Create a bubble chart that displays each sample.
Use otu_ids for the x values.

Use sample_values for the y values.

Use sample_values for the marker size.

Use otu_ids for the marker colors.

Use otu_labels for the text values.

Bubble Chart
<img width="1416" alt="bubble_chart" src="https://github.com/Mulugeta25/belly-button-challenge/assets/129996503/09435439-2414-44b1-a100-9b2e8498bf84">

Display the sample metadata, i.e., an individual's demographic information.

Display each key-value pair from the metadata JSON object somewhere on the page.



Update all of the plots any time that a new sample is selected.
Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown below:

![02](https://github.com/Mulugeta25/belly-button-challenge/assets/129996503/6de39b71-7dfa-4f3c-9543-30da56045927)


Advanced Challenge Assignment (Optional)
The following task is advanced and therefore optional.

Adapt the Gauge Chart from https://plot.ly/javascript/gauge-charts/ to plot the weekly washing frequency of the individual.

You will need to modify the example gauge code to account for values ranging from 0 through 9.

Update the chart whenever a new sample is selected.

Weekly Washing Frequency Gauge
<img width="384" alt="gauge" src="https://github.com/Mulugeta25/belly-button-challenge/assets/129996503/0e2b127e-74b1-4a91-9ed6-e52716ad3728">

Deployment
Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo.

Hints
Use console.log inside of your JavaScript code to see what your data looks like at each step.

Refer to the Plotly.js documentation when building the plots.

About the Data
Hulcr, J. et al.(2012) A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable. Retrieved from: http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/
