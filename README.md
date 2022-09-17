# UFO Sightings Analysis

Using Javascript, HTML, CSS, Bootstrap and D3 to analyze UFO sightings and create a website to share information

## Overview of Project

An analysis of UFO Sightings Data to provide a searchable table on a website. Website was stylized using HTML and Bootstrap pairings. Javascript was utilized to create a table with filters for high user experience.

### Purpose

Dana is a Data Journalist is from McMinnville, Oregon. McMinnville is famous for UFO sightings and even has an annual gathering of UFO enthusiasts. Dana has a large Javascript file with sighting information. She would like a website that displays the data and allows filters to be placed to sift through the data for the end users. Finally, the website is displayed in an HTML page. The final website will include an article, a table of data, and easy to use filters to fine-tune the results.

## Results

#### *Welcome Page and Article*
![welcome and article](https://user-images.githubusercontent.com/108373151/190875399-79bd823c-9c1b-455b-b38b-cc8e5339e18f.png)

The welcome page is stylized with a dark background and white text which is a more modern way to display applications or websites. The banner includes a nice image from NASA which catches the eye and encourages the reader to continue on the page. The article that Dana has written introduces the subject of the webpage in a clear and concise way.

#### *Sample Complete Table*
![sample table](https://user-images.githubusercontent.com/108373151/190875405-83b62703-8455-423e-842c-b8725fb04a25.png)

The table presented features UFO sightings from across the globe presented in an easy to read format. Information such as date, place, shape, time of sighting, and comments from the individual are readily available. If the user is looking for specific information or specific dates, they have the option to use the filters located on the left hand side of the page. All the user needs to do is enter the text as sampled within the text box and hit enter. One or all filters may be used to narrow down the table to provide the user exactly what they need.

#### *Filtered Table Results*
![filtered table](https://user-images.githubusercontent.com/108373151/190875408-ae629090-ff2f-45ff-98cd-c4cf023ab11d.png)

For example, the filters used in the above image is both date of 1/12/2010 and the state of Oregon. To reset the filters, simply click the "UFO Sightings" link in the navigation bar at the top of the page.

## Summary

The drawback of this page is without scanning the entire table, it is difficult to know the possible ways to filter the data. For example, the "US" country is easy to see within the first few lines of data. However, what data exists for other countries and how does the user know which countries (and their country code) to filter on? Additionally, the shape of the sighting is interesting information, but again, without scanning the table, it is difficult to know the available ways to filter on shape. The shape of "cigar" may not be considered when brainstorming ways to filter the data.

# Recommendations

- To resolve this drawback, I would recommend multi-select combo box filters instead of blank text boxes. This would enable the user to search through a list of available options to filter the data. The user could select both "cigar" and "teardrop" to display filtered data for both shapes.

- Additionally, the date field is rather limited. Currently, the table only includes UFO sightings from 1/1/2010-1/13/2010. However, if more information continues to be added to the table, it would make sense to break out the date into month, day and year to allow users to view filtered data in that manner.

- Further, it is not intuitive for the user to know that in order to clear the filters, to click the "UFO Sightings" link in the navigation bar at the top of the page. I would recommend to include a button below the search form that would clear the filters.