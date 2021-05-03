# bergfex_snowalert_part_II
Part II of this project focusses on the visualisation of web-scraped data through Tableau.

![](/screen_shots/dashboard.jpg)

This repository showcases the visualisation of data obtained and prepared in our part I repository where we web-scraped the Bergfex webpage (mountain sports information webpage) adding snow level information to each activity. It was elaborated by Malwina San José and Sarah Dutschke. 
We use TableauPublic for creating single plots, dashboards and stories.

The information presented here is not approved for any kind of commercial use.

Project Team
-----------

[Sarah Dutschke](https://www.linkedin.com/in/sarah-dutschke/), 
[Malwina San José](https://www.linkedin.com/in/malwina-san-josé/)

Partners
 -------
[Bergfex](https://www.bergfex.com/) is a company that provides a wide range of information about mountains (such as mountain activities, weather information, accommodation options etc.).

Project description
-------------------
Planning hikes in winter time can be complicated in Switzerland. Sometimes hiking in the snow is an exciting adventure, but it can also be an unexpected surprise. In part I of our project, we web-scraped information of the different mountain activities and added information on current snow levels based on geospatial weather data. 
In this project, we focus on the visualisation of such data with Tableau, making the selection of the right activity more user-friendly.

Project Milestones
-------------------
### Data Preparation
Luckily, we have scraped, cleaned the information in part I of our project. However, for certain plots (line chart), we need to prepare the data in a different format. We take advantage of Python for a quick rearrangement of the data in a Jupyter Notebook.

### Milestone 1
We have created a How-to Tutorial (story) for building a "Trail Selector" Dashboard:
 - Creating single charts of interests in Tableau.
 - Creating an interactive dashboard in Tableau.
 - Formatting charts and dashboard in Tableau.

 ### Milestone 2
 We have created project with a statistical analysis of our web-scraped data:

 - 

Outcomes
---------
As the final outcome of this project, we created two Tableau Public files, accessible here:
- [How-To Tutorial 'Trail Selector'](https://public.tableau.com/profile/sarahd8102#!/vizhome/Bergfex_II_Final/How-tostory?publish=yes) 
- [Simple Stats](https://www.linkedin.com/in/malwina-san-josé/)

How-To Tutorial
![](/screen_shots/story.jpg)

Dashboard of Trail Selector
![](/screen_shots/dashboard.jpg)

Example plots
---------

Map
![](/screen_shots/map.jpg)

Bar Chart
![](/screen_shots/bar_chart.jpg)

Line Plot
![](/screen_shots/line_plot.jpg)

Text Table
![](/screen_shots/text_table.jpg)

Requirements
------------
The libraries required to run this product are the following (details in environment.yml and environment2.yml):
  - ipykernel
  - pandas

  
Repository Structure
------------
    ├── README.md           <- top-level README file for anybody interested in this project
    ├── data                <- csv file, created based part I of the [project](https://github.com/SarahDutschke/bergfex_snow_alert_part_I)
    ├── notebooks           <- notebook, needed for the data preparation in Milestone 1
    ├── screen_shots	  <- screenshots of the Tableau workbooks
    ├── environment.yml     <- environment file that lists the channels and dependencies needed for this project
    ├── environment2.yml    <- detailed environment file that contains specific versions used for this project
