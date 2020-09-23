# Web Visualization Dashboard
## Deployment Link
https://jiuhe2020.github.io/Web-Design-Challenge

## Challenge Instructions
Web Visualization Dashboard of weather in 500+ cities at different latitudes relative to the equator line.
* In building this dashboard, individual pages are created for each plot, which contain the visualizations and their corresponding explanations, together with a means by which the navigation is available between different pages.
* The visualizations show temperature, humidity, cloudiness, and wind speed using HTML5, CSS3, and Bootstrap4.
* There is also a landing page showing a comparison of all of the plots, and another page displaying the data used to build them.

## Website Content
1. A landing page containing:
- An explanation of the project.
- Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.
2. Four visualization pages, each with:
- A descriptive title and heading tag.
- The plot/visualization itself for the selected comparison.
- A paragraph describing the plot and its significance.
3. A "Comparisons" page that:
- Contains all of the visualizations on the same page so we can easily visually compare them.
- Uses a Bootstrap grid for the visualizations.
  - The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
4. A "Data" page that:
- Displays a responsive table containing the data used in the visualizations.
  - The table must be a bootstrap table component. Hint
  - The data must come from exporting the .csv file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called to_html that allows you to generate a HTML table from a pandas dataframe. See the documentation here
5. At the top of every page, there is a navigation menu that:
- Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
- Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
- Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
- Is responsive (using media queries). The nav must have similar behavior as the screenshots "Navigation Menu" section (notice the background color change).

---
### Copyright
Jiuhe Zhu © 2020. All Rights Reserved.
