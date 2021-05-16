# UFOs - 


## Overview
Dana's webpage and dynamic table are working as intended, but she would like to have users filter on multiple criterias to do a more in-depth analysis. So, in addition to the date filter, she wants to filter on city, state, country and shape.

The task at hand is to:

1. Filter UFO sightings on multiple criterias
2. Replace the handleClick() with a new function in app.js
3. This new function will loop thru the dataset and keep only the results that match the search criteria.


### Prior work done.

.. Use JavaScript to load the sightings data into a table
.. Use JavaScript coding to filter data based on date
.. Use html, css, d3 and bootstrap to create web page to display the data for analysis.


## Results

On running the Index.html file in a browser, the screen shot(1) depicits the search fields with their placeholder values and all data is retrieved. By default, all data is listed.
(Note: the placeholder values are there just to indicate the format of the criterias to enter)
A search/filter can be done on one or more fields as shown in the screen print(2). Here the date (1/1/2010) and city (el cajon) were entered, then pressed Enter to produce the results.
To remove any of the filtered fields, simply delete the contents and press Enter. The placeholder will re-appear in that field.

1. UFOs_filter_options.png
![UFOs_filter_options](https://user-images.githubusercontent.com/78666055/118411907-0febdd00-b665-11eb-837f-14132ef153ee.png)

2. UFOs_filter_example.png
![UFOs_filter_example](https://user-images.githubusercontent.com/78666055/118411912-167a5480-b665-11eb-8808-231d5adc7eea.png)


## Summary

The filter works as intended and now users can narrow their search, but one drawback is the placeholder can be confusing as it might suggest they are included in the filter.
One way the filtering can be improved is: if the filter values could be selected from drop down boxes, it would definitely make the filtering more reliable.
Further, highlighing the filtered selection so they are not confused with the placeholders would certainly add clarity to what is being searched for.


