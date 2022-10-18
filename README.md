# Web-Design-Visualization-Dashboard

## Overview:

Data is more powerful when we share it with others! Created a dashboard uisng HTML and CSS to showcase the analysis done.<br>

## Latitude - Latitude Analysis Dashboard with Attitude:
* Created a visualization dashboard website using HTML and CSS for the [weather data](https://columbia.bootcampcontent.com/columbia-bootcamp/cu-nyc-data-pt-05-2020-u-c/-/blob/master/Homework/11-Web/Instructions/Resources/cities.csv).<br>
* For building this dashboard, I created individual pages for each plot and a means by which it can be navigated. These pages will contain the visualizations and their corresponding explanations. I also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.<br>

## Website:
The website consists of 7 pages total including:
* A landing page containing:
    * An explanation of the project.
    * Links to each visualizations page.

* Four visualization pages, each with:
    * A descriptive title and heading tag.
    * The plot/visualization itself for the selected comparison.
    * A paragraph describing the plot and its significance.
    
* A "Comparisons" page that:
    * Contains all of the visualizations on the same page so we can easily visually compare them.
    * Uses a bootstrap grid for the visualizations.
        * The grid has two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.

* A "Data" page that:
    * Displays a responsive table containing the data used in the visualizations.
        * The table is a bootstrap table component. 
        * The data was exported from the .csv file as HTML using pandas.<br>
        
The website, at the top of every page, has a navigation menu that:
* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page.
* Provides two more links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page.
* Is responsive (using media queries). 

## Website Deployed :
The website is deployed to [GitHub pages](https://dsb011.github.io/Web-Visualization-Dashboard-Latitude/)

## Visualizations:
<img src = "https://github.com/DSB011/Web-Visualization-Dashboard-Latitude/blob/master/Images/landingResize.png"> <br><br>
<img src = "https://github.com/DSB011/Web-Visualization-Dashboard-Latitude/blob/master/Images/comparison-lg.png"><br><br>

## Tech Environment Used:
HTML, CSS, Bootstrap, VSCode, GitHub, GitHub pages.


