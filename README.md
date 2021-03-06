# UFO

## Overview of Project

The purpose of this analysis was to build a webpage and dynamic table for UFO sightings that offers users an in-depth analysis by allowing users to filter for multiple criteria at the same time: date, city, state, country, and shape.

## Results

Someone can use this webpage by entering data in the search engines at the bottom of the page and hitting enter, the date for "Enter Date," the city for "Enter City," the state abbreviation for "Enter State," the country abbreviation for "Enter Country," and the shape for "Enter Shape." It should be noted that entries are case-sensitive as displayed in the example entries in each box, [as seen here](https://github.com/LaurenSonis/UFO/blob/main/2021-02-21%20(1)_LI.jpg).

For example, if a user wanted to see the UFO findings for California, the user would type "ca" in the engine titled "Enter State," then hit the enter key, and then the page would reload with all of the sightings in California, [as seen here](https://github.com/LaurenSonis/UFO/blob/main/2021-02-21%20(2).png).

## Summary 

In sum, one of the drawbacks of using this new design is case-sensitivity. I'm sure, for example, some users will want to type in "California" or even "CA" in the "Enter State" search engine instead of "ca," and it might take the user a few minutes to figure out why that's not working. 

I would recommend further development in two ways:

* 1 Give a disclaimer near the Filter Search header, ["Searches are case-sensitive"](https://github.com/LaurenSonis/UFO/blob/main/2021-02-21%20(3)_LI.jpg), by adding code to your [index.html file](https://github.com/LaurenSonis/UFO/blob/main/2021-02-21%20(4)_LI.jpg). 

* 2 Create a forEach loop to convert user input to lowercase so that every time a user inputs "CA" or "ca" or even "Ca," the input is read as "ca."
