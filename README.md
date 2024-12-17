## Welcome to the New Brunswick Map Demo!
### Find who represents you in the part of the province that you live in!

#### File structure
* /images
* index.html
* ridings.css
* ridings.js

In the /images directory put in the images you require labelled by the riding number such as `<insert_riding_num>.jpg`


#### index.html 
* Find a `modal-content` which presents as a tutorial as to how to use the map
* Find a `popover-class` which determines the labels showing up on the map
* A `page-container` and a `map-container` holding the two primary columns of the website

#### ridings.js

Important methods: 
`resetScale()` which resets the scale
`parseCSV()` which turn the postal codes into an array
`handleSearchResult()` which manages the dictionary search of mapping riding number to postal codes and centering the image

Rest of the code is self-explanatory with comments sprinkled throughout
