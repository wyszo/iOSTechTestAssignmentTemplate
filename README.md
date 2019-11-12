
iOS Technical Take Home Assignment
==================================


Overview: 
---------

There's no deadline for the assignment, do it when you can. 

If completing the assignment takes more than 8h, please stop working on it and send us an incomplete solution. 

The assignment should be send back as a zip archive. 


Guidelines: 
-----------

Please don't use external libraries for networking and TableViews. Other libraries can be used as needed. 

The code needs to be written in Swift. Remember about unit tests and consider application architecture carefully. 


Requirements: 
-------------

1. The app opens to homepage - a tableView. Each cell consists of a thumbnail image to the left and a title text on the right. 

2. The app should download items to display from: 
`https://jsonplaceholder.typicode.com/photos?_limit=20`

3. Pressing any of the cells should push a new ViewController containing full size image at the top and a title underneath. 

4. The app should support paging, on scrolling to the bottom of a tableView, more elements should be loaded: 
`https://jsonplaceholder.typicode.com/photos?_limit=20&_start=20`

Good luck! 
