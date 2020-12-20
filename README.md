# Helsinki Region Travel Time comparison application, the shinyapps.io deployment

This data analysis application was developed for my University of Helsinki Master's thesis, *Parking private cars and spatial accessibility in Helsinki Capital Region – Parking time as a part of the total travel time*.

## Contents

* [About this application](#about-this-application)
* [Application features](#application-features)
  * [User input (sidebar)](#user-input-sidebar)
  * [Map output (main panel)](#map-output-main-panel)
* [Known issues](#known-issues)
* [Associated repositories](#associated-repositories)
  * [Primary repositories](#primary-repositories)
  * [Appendixes](#appendixes)
  
## About this application

In this Master's thesis, as one of the research questions, I set out to find if there are differences in door-to-door travel times in two datasets, the Helsinki Region Travel Time Matrix 2018 and the research survey dataset collected by me for this thesis.

Presented in Salonen & Toivonen 2013, the door-to-door approach in travel time calculation includes all parts of a private car trip into account. Therefore, a trip in this research consists of:
- Walking from the origin to one's car
- Driving to destination
- Searching for parking
- Walking from one's parked car to the destination

In Helsinki Region Travel Time Matrix 2018, the searching for parking segment has been a static value of 0.42 minutes everywhere in the dataset. Using the collected survey data, the travel time comparison application presented in this repository calculates a wide variety of different scenarios using Helsinki Region Travel Time Matrix 2018 data, the research survey data, and comparisons of these two datasets.

**[The travel time comparison application is available for viewing at shinyapps.io](https://sampoves.shinyapps.io/comparison/)**.

The thesis is available as PDF at the Digital Repository of the University of Helsinki: **http://urn.fi/URN:NBN:fi:hulib-202010304366**. See the section [Associated repositories](#associated-repositories) for all GitHub repositories associated with this thesis.

## Application features

### User input (sidebar)

#### Private car travel chain origin

#### Symbology options

#### Layer options

### Map output (main panel)

#### Overview

#### Interactions

## Known issues

* *Map elements*: As the user changes app settings, the output map legend elements swap places in a chaotic fashion.

## Associated repositories

### Primary repositories

Please find the other GitHub repositories important to this thesis in the table below.

| Repository | Description | Web deployment |
| --- | --- | --- |
| https://github.com/sampoves/thesis-data-analysis | The thesis data analysis workflow, the main repository for all things programming in this thesis | See below |
| https://github.com/sampoves/Masters-2020 | The Master's thesis in its original LaTeX format | The Digital Repository of the University of Helsinki: **http://urn.fi/URN:NBN:fi:hulib-202010304366** |
| https://github.com/sampoves/parking-in-helsinki-region | The web based survey application | Hosted by the author: **https://parking-survey.socialsawblade.fi** |
| https://github.com/sampoves/thesis-analysis-shinyapps | shinyapps.io deployment of the survey data analysis and statistics application | shinyapps.io: **https://sampoves.shinyapps.io/analysis/** |
| https://github.com/sampoves/thesis-visitors-shinyapps | shinyapps.io deployment of the visitors analysis application | shinyapps.io: **https://sampoves.shinyapps.io/visitors/** |

### Appendixes

During the process of creating the thesis, the following side products came into being:

| Repository | Description | Language(s) |
| --- | --- | --- |
| https://github.com/sampoves/leaflet-map-survey-point | A variant of the survey application. Users place points on the map instead of postal code areas | HTML, Javascript, PHP |
| https://github.com/sampoves/msc-thesis-template | A barebones LaTeX thesis template in the style required by Department of Geosciences and Geography in the University of Helsinki | LaTeX |
