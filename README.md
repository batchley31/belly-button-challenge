# belly-button-challenge

To start I made a variable for the url as a constant so that it cannot be changed at all even with other variables being added updated or removed from it.  I then created a constant variable for the data and then used the D3 libarary to upload the data from the json file and log it.

To set up the variables for the bar charts created a function from the url and json data to select the ID and then add the option and value from that ID.  I set up the function to display the first set of data in the list by default within the same begining function.  For the second function I created a function to read of the ID selected in the dropdown menu so that way when the new ID takes places the function also pulls the correct data that relates to the ID now selected.

The next function I created is one that takes all the information from the metadata like the gender, age, and id of the subject just to name a few.  I had the function then pull all the different data assocaited with each patient starting with their id and ending with their wfreq. That way when I selesct the certian ID for for the patient I want it will pull through all the data from this metadata function.

The last functions I made were the ones to create the bar chart and bubble graph.  When I created the bar chart I used hbarChart so that the bars would go left to right on the screen instead of up and down.  This made it easier to read since it was also accompanied with a second graph where I used bubbleChart to show teh same graph but with a different type of visual.  For each graph I sliced the data to only show the first 10 id data points and reversed it so the graph would be highest to lowest.

To enter all the information into a new plot I created variables that reflected the type of chart and then entered each variable into the Plotly.  Also inside the Plotly was a layout that I created under the layout variable.  In the layout I set my margins and height and width for the graphs.
