# UFOs
## Project Overview
For this project, I was asked to develop a website to display and filter data about UFO sightings. Initially, I was asked to develop a website that allowed users to sort by date for various UFO sightings across the United States. The project was expanded to include other search criteria to help users navigate the data by filtering by city, state, country, and shape.

## Results
The webpage is very intuitive. Upon opening the page users can see the full data set, that they are welcome to puruse without using filters. As you can see in the image below, search filters are located to the left of the table. Users can input a particular date, location, or "shape" of the sighting to narrow down their search criteria.

<p align="center">
  <img src="https://github.com/liviblocker/UFOs/blob/main/Static/Images/Full_Page.png" width="600" />
</p>

### Example
If you are searching for all UFO sightings in the US, you'd simply type "us" in the "Country" field.

<p align="center">
  <img src="https://github.com/liviblocker/UFOs/blob/main/Static/Images/US_Search.png" width="600" />
</p>

To further narrow the search to those sighting in FL, you'd type "fl" in the "State" field.

<p align="center">
  <img src="https://github.com/liviblocker/UFOs/blob/main/Static/Images/FL_Search.png" width="600" />
</p>

Finally, to narrow down the search to all sighting in FL that had a "spherical" shape, you'd type "sphere" in the "Shape" field.

<p align="center">
  <img src="https://github.com/liviblocker/UFOs/blob/main/Static/Images/Sphere_Search.png" width="600" />
</p>


## Summary
### Drawback
This is a very simple, effective search tool, but one of the biggest drawbacks in the fact that the filter search is case-sensitive. In the data set, all words are lower case, so if we were to conduct a search for sightings in "FL" (as opposed to "fl") there would be no data returned.

### Recommendations
There is a lot of recommendations I would have for this webpage:
1. I would develop a feature for "sorting" data on the table for improved use. By sorting the data, we could look at the data from 
2. Until there is more data from other countries added, I would remove the "country" search filter. Currently all data is from the United States, and it's an unnecessary search field.
3. I would update the date search filter in order to search by year and month more broadly (as opposed to only inputting in the DD/MM/YYYY format). Also in this update, I would develop a date range search function.
4. Finally, I would add a sighting report page, where users could submit their own sightings to add to the data set.
