# UFO Finder using JavaScript

## Overview 
The purpose of this project was improve the functionality of a website that we previously set up in the modeule. First, changes were made to the *index.html* file to account for the new functions that would be created. Next, the event listener in the *app.js* file was edited to account for input changes. Finally, the updateFilters() and filterTable() fucntions were created in *app.js*. The updateFilters() function saved the element,value, and id that were changed in the user input. The filterTable() function loops through the filters provided by updateFilters() and keeps the corresponding data. 

## Results
When the UFO Finder website is first accessed, all of the data is displayed (as seen below) because there has not been any input changes detected yet. 
![no Input](https://github.com/naomishields/UFOs/blob/main/static/images/no_input.png)

Once the user inputs something into the filter search then the website will begin to respond. If the user inputs a value into the filter search that does not match any of the data then an empty table will be returned (as seen below).
![No Matches](https://github.com/naomishields/UFOs/blob/main/static/images/no_match.png)

When the user inputs values into the filter search that do have matches then a filtered table will appear. This can be seen below in the example case where the state of California was inputed along with the shape of light.
![Filtered Table](https://github.com/naomishields/UFOs/blob/main/static/images/filtered.png)

## Summary 
One drawback of the way that the table filters data is that nothing is returned if the user does not input the right criteria. Something I think that could be added is a try-catch block in the to address inputs that do not match any of the data that outputs a message to the user instead of an empty table. Another thing that I think could be useful is a dropdown search tool so that the user could see all the possible options and have the opportunity to select multiple values in the different fields. 
