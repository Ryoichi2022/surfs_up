# surfs_up

Challenge 11
# UFO Sightings Search

## 1. Overview of project
Dana, a data journalist, is trying to develop an HTML page that would contain an article and a table of data related to UFO sightings. So far, the sighting information has been summarized in a JavaScript file. Through the project, the table will be incorporated into the HTML page with filters so that users can easily manipulate the sighting data and see the results on the page.


## 2. Results
### How to use filter
The sighting data will be tuned as follows using the search criteria such as date, city, state, country, and shape. Either single criterion or multiple criteria can be applied by entry of values in blank boxes, which are filled with grey placeholders. An example of value entry is presented below as Picture 1.

### General instructions
When you enter a value in the Enter Date box, it needs to be in mm/dd/yyyy format. As shown in the picture, ‘0’ is not necessary in the ten’s place in the case that month or day is a single digit. Also, text entry is case sensitive, and only lower cases will be used. If you would like to see sightings in the United States, the entry needs to be ‘us’ in the Enter a Country box.

#### (Picture 1) Value entry example
![](https://github.com/Ryoichi2022/UFOs/blob/main/Picture_1.png)

### Individual entry box
#### * Date
The entire table includes sightings during the period from January 1, 2010 (1/1/2010) through January 13, 2010 (1/13/2010). If a date outside the period is entered, nothing will be displayed on the page.

#### * City
Various cities are available as entry option. Please be sure to type it only with lower cases.

#### * State
You are supposed to enter the state value using the regular abbreviation of the states in the United States as well as Canada. Currently, 35 U.S. states are available to fill in the box including ca, fl, and ma.

#### * Country
The only values are ‘us’ for the United States and ‘ca’ for Canada.

#### * Shape
16 specific shapes plus ‘other’ and ‘unknown’ can be used for the Enter a Shape box. The top three shapes in the table are light, triangle, and sphere.


## 3. Summary
### Drawback of the page
* The page only allows users to manipulate the sighting information by entering criteria one after another. Users will not be able to save the search result directly from the page. It would be convenient if the result can be downloaded into the user’s device in any format.

### Recommendations for further development
* Each sighting contains a comment to describe the object, or UFO, more specifically, such as colors or how it looked like. Setting a key word filter over the comments will be useful and add value to users.
* There are only 111 UFO sighting reports in the page currently, and they are limited to the United States and Canada. It would be recommended that more data be gathered not only from these two countries but from all over the world. Then, the page will be more attractive.
