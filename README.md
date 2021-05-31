# UFO_analysis

## Purpose
From an exisitng webpage, Dana has requested us to build more filter tables from the table of data that we inserted into her webpage. She wanted to be able to filter not only date, but also by city, state, country, and shape.

## Objectives
The goals of this challenge are to:

* Create, update, and deploy JavaScript functions to provide additional table filters.
* Update and deploy forEach (for loop) to loop through the filters and update them with user input.
* Update and populate the dynamic filters and table using JavaScript and HTML.

## Analysis
I started by adding list items for the filters that were required (city, state, country, shape).  These were added to the unordered list section in the .html file that already held the user input area for the date/ time filter we developed in the module.  Once this was completed, I built the Javascript code to grab the user input from these items and append a JS object (named "filters").  The .toLowerCase() method was useful to make sure the user input was in the correct state to match up the filters. Once we have this object, we can loop through it by converting the object to an array (in this case an array of key/value pair arrays) to build the filtered data.  We then return to the buildTable function where we pass the filteredData as the parameter.  

## Conclusion
While the addition of filter tables help filter the table by certain data. The next step to make the website cleaner would be able to create a drop down menu under the filtered tbles section so that a user can select what they want to to search by. The data table should also be formatted to be another column section of the web page so that it is islaoted from other sections of the webpage. 

The webpage does its function well, but the webpage is still a little clunky and messy and can definitely undergo imrpovements in the future down the line.
