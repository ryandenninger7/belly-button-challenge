# belly-button-challenge

This project presents an interactive web dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels. The data reveals that a small handful of microbial species (operational taxonomic units, or OTUs) are present in more than 70% of people, while the rest are relatively rare. Our dashboard provides a detailed and interactive way to visualize and explore the microbial communities found in human belly buttons.

Features: 

-Sample Selection: A dropdown menu allows users to select an individual sample from the dataset.

-Bar Chart: Displays the top 10 OTUs found in the selected individual, providing a quick glimpse into the microbial diversity of their navel.

-Bubble Chart: Each sample's microbial species are displayed in a bubble chart, using OTU IDs for the x-axis and sample values for both y-axis and marker size. Marker colors vary by OTU ID, offering a rich, visual representation of species prevalence and diversity.

-Demographic Information: Displays selected individual's demographic information, enriching the context for data exploration.

Technologies Used:

-D3.js: For reading the samples.json data and manipulating the DOM based on the dataset.

-Plotly.js: To create interactive charts that visualize the biodiversity data.

-Bootstrap: For styling and responsive layout.

*Deployed on GitHub Pages: removes the need to run on a local server*


How to Use:

1) Select a Sample: Use the dropdown menu to select a sample number. The dashboard will automatically update to display data for the selected individual.
2) Explore the Charts: Hover over chart elements to see additional details about each microbial species.
3) View Demographic Information: Read the demographic information panel to learn more about the selected individual.


Future Improvements: 
-Integration of advanced statistical analysis to identify potential correlations between microbial species and demographic factors.
-Expansion of the dataset to include more samples and potentially new study areas related to human microbiome diversity.

Project Structure:
-index.html: The entry point of the application, containing the layout and structure of the dashboard.
-static/js/app.js: Contains all the JavaScript code to render the charts based on the selected sample.
-samples.json: The dataset used in this project, including OTU IDs, sample values, and metadata for each individual.
