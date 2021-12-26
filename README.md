# UFOs and JavaScript
## Overview
Dana is a data journalist who is given the opportunity to write about her hometown, MicMinnville, which is famous for its UFO sightings and also hosts an annual gathering of UFO enthusiasts. Dana has been interested in this topic since she was a child. She made a JavaScript file that contains sighting information with countries, cities, states, and the type of sighting. Because there is too much data, it is difficult to display the tables. Thankfully, JavaScript provides filters to use to manipulate the data. We assissted Dana in creating a tidy HTML page with her article, the table of data to support her findings, and user-friendly filters to fine tune the results.

The UFO webpage and dynamic table are working as intended, but Dana would like to provide a deeper analysis of UFO sightings by enabling users to filter multiple criteria at teh same time. We added table filters for teh city, state, country, and shape.
## Results
### The Completed UFO Page:
![Capture](https://user-images.githubusercontent.com/92230478/147396308-155fcf11-9a55-4db0-b8d6-b10c01b6fec0.PNG)
![Capture1](https://user-images.githubusercontent.com/92230478/147396325-c3781b0e-7493-4ff1-af05-200ee036fd55.PNG)

To filter the UFO sighting data, users will type the desired search criteria into the specified search fields. Example placeholder entires are visible in each of the fields to guide user responses and enter information in the correct format. For example, the "Enter Date" field take searches in a numbered format, such as 1/10/2010. The table will dynamically update and return results after entering search fields. If no matches are found, the table will be empty.

## Summary
While the table is great, one drawback is that Javascript language is case sensitive. The table will not update if the users do not enter exactly how the data is stored and does not allow for partial entries. This is an issue because it does not intuitively tell the user how the information should be entered other than the "default" example shown. For example, if a user were to enter "CA" to identify the UFO sightings in California, the filter search results are zero. Whereas, if they were to enter "ca" in lower case, there are plenty of results. 

To improve the user's experience, we can add the following enhancements: Add additional customizations, such as click-buttons, dropdown list, and/or auto-fill that can help "guide" the user and make the page more interactive by providing options for the users to select from for filters and create multiple pages for the entry results. As the total number of entries in this list increases, this webpage will become clunky and difficult to scroll thorugh so many entries. Additionally, create a button that allows the user to choose how many results are shown per page (25, 50, 100, etc.).

