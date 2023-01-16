# UFOs

## Overview
Dana is a data journalist reporting on UFO sightings in her hometown. As part of her assignment, she would like to present a public page that details each UFO account which is handed to her in a JavaScript file. To do this she uses JavaScript to first display the data as a table, then adding a filter button in order to more efficiently sift through the large set of data. She then places the table with the filter on a public HTML webpage that is styled with Bootstrap for interactivity. Below is the result:

![This is an image](Images/with_filter_button.png)

Now, Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. The next task is to add table filters for the city, state, country, and shape, in addition to the date.

## Results

Below is the result of the page being updated to remove the filter button element with additional filters that listen for changes using D3.js

![This is an image](Images/added_filters.png)

Once you fill in the "date" and "state" filters for example, and tab over or hit enter, the table results update to include only that criteria, as shown in the image below.

![This is an image](Images/filter_example.png)

## Summary

The additional filters are helpful for anyone looking for a specific event or doing an investigation to get an understanding of the commanilities between the fields. For example, searching UFO sightings only in California, during the same month, and determining if they were all the same shape to show more credibility towards events. One drawback is that a user may not come in already knowing what they are looking for and the unfiltered table is pretty long. To improve the experience, some additional development can be done:
1. Update the filters to include drop down menus based on what actually present in the data.
2. Add a way to automatically clear/reset the filters to start over, instead of having to go back one by one to each field.
