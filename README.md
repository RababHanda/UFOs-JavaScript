# UFOs-JavaScript

## Overview of Project
This project presents UFO sightings data on a webpage

### Purpose

This project represents data of UFO sightings in a tabular format on webpage. The project deploys HTML to create a webpage, JavaScript to filter the table according to changes made on the page as well as CSS styling to customize the webpage.

## Results

### How to Use The Webpage

##### Parts of the Webpage
The following page open once the html file is opened

<p align="left">
<img src="/Resources/intro.png" width="75%" height="75%">
</p>

##### Use the Filter(s)
Scroll down a little to view all the filtering option on the left hand side of the table. 

The filter is designed to be able to take anywhere from 0 to 5 filters at a time. Without an filters, all the data will appear and the user can scroll through if they wish to take a look at the entirety of the table.

The format that each filter needs to be entered in is already highlighted in the tabs, follow the format and enter the attribute you'd like to filter by:

<p align="left">
<img src="/Resources/filter_format.png" width="30%" height="70%">
</p>

Hit *enter* to update the filtered table

##### Results of the Filter(s)

If any data containing the filter exists, the resulting will be displayed in the table. However, if no data exists, an empty table will apear

| Condition | Result | 
| --- | --- |
| Data Exists | ![Filter Valid](/Resources/filter_valid.png) |
| Data Does not Exist | ![Filter Unalid](/Resources/filter_unvalid.png) |


## Summary

Although the webpage is functional enough for simple data such as the one used in the tabl. However, a major drawback is that:

> The current design doesn't let the user download the filtered data in one of the common formats of excel (.csv, .xls, .xlsx etc.) For someone using filters for an analysis of their own, this is a must-have feature

The design can be improved and made more user-friendly by:

1. **Adding options menu:** Adding options to each of the filtering criteria will help the user by communicating what all the acceptable options are. For eg., in the *shape* filter, *light* and *formation* aren't really shapes but they do exist under the column. A user unfamiliar with them will never use that piece of data unless they were to come across it by accident. 

2. **Adding multiple attributes of a fitler:** The design can be improved by allowing the user to enter multiple attributes of the same filter. For eg., someone looking for *circular* and *triangular* shapes of UFO sightings can enter both at the same time and view the consolidated resutls of the two, as opposed filtering for each one by one.