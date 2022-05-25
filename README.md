# UFO Sightings
## Overview of Project
We are given a data set that holds a multitude of information surrounding the topic of UFO sightings. The provided data is transformed into a dynamic data table that can be refined by date. Each row holds information that is relevant to a sighting; each entry having provided City, State, Country, Shape, Duration, and Comments. The purpose of this project is to widen the criteria by which the data set can be filtered to include location and Shape; all of which are displayed and can in a webpage format. (see example: fig. 1) 
</br>
</br>

## Results

Note: The "Filter Search" box highlighted in green displays evenly with the Table on the true webpage version.
![](/static/images/webpage.jpg)
<div style="text-align: right"> (fig. 1) </div>
The update added 4 additional text search boxes that allow the user to further refine the data beyond just the date. The shadow of an example filter is displayed in the text input boxes above highlighted in green. The box will accept input that follows the format of the shadow; it will filter the data in real time when a filter criteria has been met. The input boxes can be cleared by refreshing the page or manually deleting each boxes contents. Once clear and/or empty, the data table will stop being filtered and return to displaying all sightings.  

## Summary
Each criteria outlined above has been met, and the web page operates in the method outlined above. What *doesn't* this webpage do?

### Drawbacks
&emsp;Quick Fixes: 
* Lacking a quick built-in solution to clear input boxes
* Text inputs must be in lower case
* "Spacey" and rudimentary webpage styling </br>

&emsp;Longer Term Recommended Fixes:
* Add maps/pin-drops/images/additional external information beyond the provided comments
* Add search area functionality: 
    * Only one state can be selected at a time
    * There is no functionality to support a date range
    * Lacking functionality to support quantitative or corolary analysis 
* Create a "map lasso" interface to promote further analysis by outlining an area on a map and returning all sightings in a given date range. 
* Provide statistics for dates/date ranges such as: number of sightings, number of similar sightings (matching shape, similar comments, etc.), heat map statistics of sightings occurring in areas on given date ranges. 
