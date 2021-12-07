# Web Design Homework - Web Visualization Dashboard (Latitude)
<img width="1220" alt="Screen Shot 2021-12-06 at 10 13 57 PM" src="https://user-images.githubusercontent.com/91695375/144959590-cdd3fac1-61d6-4118-866d-874eda3394d0.png">

## Background

Data is more powerful when we share it with others! Let's take what we've learned about HTML and CSS to create a dashboard showing off the analysis we've done.

## Latitude - Latitude Analysis Dashboard with Attitude

For this homework we'll be creating a visualization dashboard website using visualizations we've created in a past assignment. Specifically, we'll be plotting [weather data](Resources/cities.csv).

In building this dashboard, we'll create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website Details! 

For reference, see the ["Screenshots" section](#screenshots) below.

* A [landing page](#landing-page): (Seen above! :heart:)
  * An explanation of the project.
  * Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.
* Four [visualization pages](#visualization-pages): (Also displayed above! Each graph is a clickable link!)
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](#comparisons-page):
 <img width="1213" alt="Screen Shot 2021-12-06 at 10 14 39 PM" src="https://user-images.githubusercontent.com/91695375/144959690-2bd57fd6-1e54-4716-8bd9-1da133dd6fbe.png">
* Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
  
* A ["Data" page](#data-page):
  * Displays a responsive table containing the data used in the visualizations.
<img width="1227" alt="Screen Shot 2021-12-06 at 10 23 17 PM" src="https://user-images.githubusercontent.com/91695375/144960450-9bd2cd50-c1b0-4a3e-8501-1ddaa64c958d.png">

The website must, at the top of every page, have a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive (using media queries). The nav must have similar behavior as the screenshots ["Navigation Menu" section](#navigation-menu) (notice the background color change).

Finally, the website must be deployed to GitHub pages.

When finished, submit to BootcampSpot the links to 1) the deployed app and 2) the GitHub repository.

Ensure your repository has regular commits and a thorough README.md file

### Considerations

* You may use the [weather data](Resources/cities.csv) or choose another dataset. Alternatively, you may use the included [cities dataset](Resources/cities.csv) and pull the images from the [assets folder](Resources/assets).
* You must use Bootstrap. This includes using the Bootstrap `navbar` component for the header on every page, the bootstrap table component for the data page, and the Bootstrap grid for responsiveness on the comparison page.
* You must deploy your website to GitHub pages, with the website working on a live, publicly accessible URL as a result.
* Be sure to use a CSS media query for the navigation menu.
* Be sure your website works at all window widths/sizes.
* Feel free to take some liberty in the visual aspects, but keep the core functionality the same.

## Rubric

[Unit 11 Rubric - Web Design Homework - Web Visualization Dashboard](https://docs.google.com/document/d/16RJehl9qVOxdj7o7hUwvdlsoyrA_-kaoB8CGwr9LX_Y/edit?usp=sharing)

- - -

## References

OpenWeatherMap.org. (2012). Сurrent weather and forecast. Retrieved from [https://openweathermap.org/](https://openweathermap.org/)

- - -
