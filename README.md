# Project Summary

This project was to create a design document for a fictional game company "The Gaming Room."
The company wanted a web based platform for their existing mobile game "Draw It or Lose It."

The company specified the following requirements:
-	The application will render images from an extensive stock library. 
-	The game will consist of four 1-minute rounds of play. 
-	If time expires, the remaining teams will have an opportunity to guess within 15-seconds. 
-	A game will have one or more teams involved. 
-	Each team will have multiple players. 
-	The game and team names must be unique. 
-	Each game, team, and player objects need to have unique identifiers.

One of the challenges of creating a design document is knowing what should be focused on and communicated to the audience. 
One of the things I did well in creating this project was incorporating feedback from an experienced and trusted professor. 
Their feedback went into updated versions of this document as it took shape over several weeks. 
This feedback helped me focus the document into something worth reading.

If I could choose one part of this document to revise it would be to explore a cloud-based platform. 
The current requirement was to explore traditional server platforms. 
However, if this game was truly to be web-based then the scale-out and regional capabilties of cloud-based platforms becomes more important to explore.

It is important to consider the user's requirements by putting them into the software design. 
For example, one of the requirements is to use an image library. 
Later it was determined that the library consisted of 200 8 megabyte images or a library of 1.6 gigabytes of data. To serve these images as quickly as possible to the game clients, one of the recommendations is to serve these is to store these images on fast read disks such as solid-state drives. 
Another recommendation is to size the servers with enough RAM to load the whole library into RAM and serve the images from RAM. 
If we do not meet the customer's requirments they are unlikely to to use us on future projects nor recommend us to other clients when their needs are not satisfactorily met. 

In a way this design was developed in an Agile way. It was drafted with certain sections in a time period, put out for review (early release), incorporated feedback into the next release and added new sections to the document in the next period. I continued to iterate over the document until all interested parties were satisified with the design. This approach was successful, and I intend to keep using it in future work.
