# UFOs

## Overview 

The purpose of this project was to learn to create a visually appealing webpage, which features some dynamically filtered tabular data in a user-friendly interface for ufo sightings. To accomplish the purpose of this project we needed to learn how to take data that is stored as a JavaScript array and create a table to organize the information that will visually adjust as "events" change (i.e. filtering). In order to react when an element is changed, we used Javascript functions to loop through the data to build the table and create a customized dashboard. The customizations include filters with event listeners that will record the information when an element has changed based off the user’s input, through an interactive webpage. 

### Tools

HTML, Bootstrap, Javascript, DOM manipulation, and CSS

## Results

To understand the results that we got when filtering the webpage we first must look at how the webpage first looked which included only a date filter and required the user to click a button for the filter to be applied. With the new modified webpage the button was removed and more filters were added like the city, state, country, and shape which upon user input, the table will automatically filter the results accordingly. Below you can see all the results from initial creation to the various filters added to the modified webpage.

### original webpage

![Original Website](https://github.com/backwater-graphics/UFOs/blob/main/static/images/original-website.jpg)
---

### Filtering by event date

The user enters the desired date, the change is detected and the table is updated accordingly.

![Event Date](https://github.com/backwater-graphics/UFOs/blob/main/static/images/event-date.jpg)
---

### Filtering by city

The user enters the desired city, the change is detected and the table is updated accordingly.
![City](https://github.com/backwater-graphics/UFOs/blob/main/static/images/city.jpg)
---

### Filtering by state

The user enters the desired state, the change is detected and the table is updated accordingly.

![State](https://github.com/backwater-graphics/UFOs/blob/main/static/images/state.jpg)
---

### Filtering by country

The user enters the desired country, the change is detected and the table is updated accordingly.

![country]( https://github.com/backwater-graphics/UFOs/blob/main/static/images/country.jpg)
---

### Filtering by shape

The user enters the desired shape, the change is detected and the table is updated accordingly.

![shape]( https://github.com/backwater-graphics/UFOs/blob/main/static/images/shape.jpg)
---

### All Filters

All filter parameters can be entered simultaneously.

![All Filters]( https://github.com/backwater-graphics/UFOs/blob/main/static/images/all.jpg)
---

## Summary

In conclusion the new web page design includes additional search fields, which is a definite improvement over the previous iteration. The previous version only provided a date field to search by and depended upon a button click to refresh or update the displayed table. However, there is some drawbacks and recommendations that could be done to make this site even better.

### Drawbacks

The main drawback that I see with the webpage filters is that the user must know specific information to use when using the filters. So for example to pick a shape, the user would have to go through the table to find a shape to search for.
Another drawback is that the filters are case sensitive, which means you have to know if the information was entered in with upper-case letters or lower-case letters or both. If you don’t know and you try to filter on the wrong letter case it will not return a result.

### Recommendations

-	The first recommendation would be due to the fact that we do not know exactly what the existing options are for the shape field, so it makes it hard to effectively search using that filter and there seem to be a limited number of pre-defined descriptions, but if I search for something using terms such as oblong or oval, I receive no results. So, the recommendation would be for the Shape Field to be a drop-down selection menu instead of an input field.
-	The second recommendation would be to add the functionality so that the input fields except either case and would return results even if the wrong case was used.
-	The third recommendation would be after you enter information into the input fields there is no easy way to clear the data except to manually clear it yourself. The recommendation would be to add a button to clear the data from the input fields.
