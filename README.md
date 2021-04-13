# bergfex_snowalert_part_II
Part II of this project focusses on the visualisation of webscraped data through Tableau.

![](/screen_shots/Tableau_teaser.png)

This repository showcases the visualization of data obtained and prepared in our part I repository where we webscraped the Bergfex webpage (mountain sports information webpage) adding snow level information to each activity. It was elaborated by Malwina San José and Sarah Dutschke. 
We use TableauPublic for creating single plots, dashboards and stories.###### 
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
Planning hikes in winter time can be complicated in Switzerland. Sometimes hiking in the snow is an exciting adventure, but it can also be an unexpected surprise. In part I of our project, we webscraped information of the different mountain activities and added information on current snow levels based on geospatial weather data. 
In this project, we focus on the visualization of such data with Tableau, making the selection of the right activity more userfriendly.

Project Milestones
-------------------
### Data Preparation
Luckily, we have scraped, cleaned the information in part I of our project. However, for certain plots (line chart), we need to prepare the data in a different format. We take advantage of Python for a quick rearrangement in a Jupyter Notebook.

### Milestone 1
Creating single charts of interests in Tableau.

 ### Milestone 2
 Creating an interactive dashboard in Tableau.
 
 ### Milestone 3
Formatting charts and dashboard in Tableau.

Outcomes
---------
As the final outcome of this project, we created a Tableau Public file (####link).
![](/screen_shots/dashboard.jpeg)

Example plots
---------
![](/screen_shots/map.jpeg)
![](/screen_shots/stats.jpeg)
![](/screen_shots/line_plot.jpeg)

Requirements
------------
The libraries required to run this product are the following (details in environment.yml and environment2.yml):
  - ipykernel
  - pandas

XXX to update
  
  
Repository Structure
------------
├── README.md       <- top-level README file for anybody interested in this project
├── data                     <- csv file, created based part I of the [project](https://github.com/SarahDutschke/bergfex_snow_alert_part_I)
├── notebooks           <- notebook for the data preparation

