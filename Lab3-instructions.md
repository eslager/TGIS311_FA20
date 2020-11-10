# Lab 3: Web Mapping with MapBox GL JS

### Introduction

For this lab you will create a single HTML page containing two maps that use the Mapbox GL JS API. Although Mapbox is different from Leaflet in some of its specifics, the basic process of initializing and controlling web maps with this framework is similar to Leaflet, so you will be able to apply what you learned in Lab 2 to the basic steps of Lab 3. For this reason, Lab 3 asks you to incorporate some more advanced functionality into your maps with fewer step-by-step instructions.  

Like lab 2, this lab requires you to use different data sources of your choice in your web maps. In winter quarter, we will learn more about how to collect and create your own data to display in web maps, but for now, you will be downloading vector data sets of your choice. I suggest you read all of these instructions before brainstorming the kinds of data set you might want to use. 

### Lab Requirements

For this lab, please submit a URL link to single webpage that includes two maps. The maps and webpage must meet the following requirements:

* The page should contain a title(s) and accompanying text to describe what is being mapped

* At least one map should use a custom styled base map that you have created using MapBox Studio

* At least one of the maps should have a clickable data layer that displays additional information in popups when clicked
* At least one of the maps should use custom icons for a point layer
* Between the two maps, you must implement at least two of the following advanced functionality features: 
  * A timeslider (this requires data that has a temporal attribute)
  * Conditional styling by data property (such as proportional symbol or choropleth map)
  * An address geocoder that lets a user enter an address and locate that address on the map
  * A layer control to toggle either vector layers or basemap layers on and off
  * Another feature of your choice (please clear your choice with me before submission!)

The reason for requiring two maps on one page is to give you practice working with differently named map variables and map div IDs. Your maps may be, but do not have to be, about a related theme or topic, and they may use the same, or some of the same, data sets if they visualize those data in different ways. 

Tutorials/code examples for using the advanced functionality features are linked in the Resources section of these instructions, but it is your responsibility to figure out how to implement these with your specific maps and data layers. (Of course, I am always available to help you troubleshoot your code!) 

Bonus points may be awarded for exceptional implementation of advanced functionality, for particularly effective incorporation of multiple maps and data sets, or for exceptional design. 

### Resources

Examples/tutorials for implementing advanced functionality with Mapbox GL: 

* Basemap styling: https://docs.mapbox.com/help/tutorials/create-a-custom-style/
* Custom icons: https://docs.mapbox.com/mapbox-gl-js/example/custom-marker-icons/ or https://docs.mapbox.com/mapbox-gl-js/example/add-image/

* Display a popup on click: https://docs.mapbox.com/mapbox-gl-js/example/popup-on-click/

* Geocoder: https://docs.mapbox.com/mapbox-gl-js/example/mapbox-gl-geocoder/

* Conditional styling: https://docs.mapbox.com/help/tutorials/mapbox-gl-js-expressions/

* Toggle vector layers: https://docs.mapbox.com/mapbox-gl-js/example/toggle-layers/

* Toggle base map layers: https://docs.mapbox.com/mapbox-gl-js/example/setstyle/

* Time slider: https://docs.mapbox.com/mapbox-gl-js/example/timeline-animation/

### Grading Rubric

I’m going to try to get you used to less detailed rubrics as the program goes on. This is because being able to discern evaluation criteria from qualitative descriptions of expectations is an important professional skill. Further, as you get more accustomed to my grading style, this will become easier and easier for you to do. As we move in that direction, I will still provide a rough breakdown of how I will assign points for labs in this fall quarter.

This lab will be worth 20 points:

* 7 points will be possible for having two maps with at least one custom base map, custom icons, and a clickable layer
* 9 points will be possible for successful implementation of at least two advanced functionality features

* 4 points will be for general matters like code and file organization, overall page styling with CSS, and explanatory text/title(s)

* Bonus points will be assigned on a case-by-case basis
