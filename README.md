# Belly-Button-Challenge

# Files

### Original Source Files

[Module 14 Challenge Files](https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/Starter_Code.zip)

### Solved Files

[Belly Button JavaScript File .js](https://github.com/BryanCarney/Belly-Button-Challenge/blob/main/static/js/app.js)

[HTML File](https://github.com/BryanCarney/Belly-Button-Challenge/blob/main/index.html)

### Background
In this assignment, you will build an interactive dashboard to explore the [Belly Button Biodiversity dataset](http://robdunnlab.com/projects/belly-button-biodiversity/), which catalogs the microbes that colonize human navels.
The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

### Instructions

**Complete the following steps:**

1. Use the D3 library to read in `samples.json` from the URL https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json.

2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

    • Use `sample_values` as the values for the bar chart.
    
    • Use `otu_ids` as the labels for the bar chart.
    
    • Use `otu_labels` as the hovertext for the chart.

![image](https://github.com/user-attachments/assets/434116b3-2038-401a-9c40-034e14eddac3)

3. Create a bubble chart that displays each sample.

    • Use `otu_ids` for the x values.
    
    • Use `sample_values` for the y values.
    
    • Use `sample_values` for the marker size.
    
    • Use `otu_ids` for the marker colors.
    
    • Use `otu_labels` for the text values.

![image](https://github.com/user-attachments/assets/39c987a5-30bf-45d9-aaee-fb1f4deb280c)

4. Display the sample's metadata, i.e., an individual's demographic information.

    • Loop through each key-value pair from the metadata JSON object and create a text string.
    
    • Append an html tag with that text to the `#sample-metadata` panel.

![image](https://github.com/user-attachments/assets/bc652051-1cda-433a-9486-7dd9fd149f38)

5. Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown as follows:

![image](https://github.com/user-attachments/assets/086148e3-f87e-47dd-a981-6c4bb3249425)

6. Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough `README.md` file

    •Note: If you haven't covered GitHub Pages yet in class (as this will be introduced in Class 15.3), don't worry! As long as the finalized code is in your GitHub repository, deploying it can be done in just a few clicks. Focus on completing your app and making regular commits for now. We'll walk through the easy deployment process together in class.

### Hints

   • Use console.log inside of your JavaScript code to see what your data looks like at each step.
    
   • Refer to the Plotly.js documentationLinks to an external site. when building the plots.
