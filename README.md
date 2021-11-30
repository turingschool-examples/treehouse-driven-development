# Treehouse Driven Developent

![treehouse](https://media.giphy.com/media/L1cKe0Rek3W5Cr0o8S/giphy.gif)

What could be better than renting out a beautiful treehouse cabin for the holidays? Your goal is to use Test/Treehouse Driven Development to build out the start of a Treehouse Booking App! 

## Treehouse Class
Your Treehouse class should meet the following requirements:

* Have the following properties:
  * price
  * bedrooms
  * bathrooms
  * location
  * isBooked (default to false) 
* Have the following functionality:  
  * Be able to go on sale. Passing in a number to this method should decrease the price property by that percent
  
 _Write the tests first, and then move on to your implementation code!_

## Customer Class
Your Customer class should meet the following requirements:

* Have the following properties:
  * budget
  * bookings (default to an empty array)
* Have the following functionality:
  * Be able to check their budget. Passing in a treehouse to this method should return a boolean value indicating if they have enough money to book that treehouse or not
  * Be able to book a treehouse (add to bookings array) if that treehouse is in their budget
  * Be able to see a message if they do not have enough money to book that treehouse
  * See their budget decrease after successfully booking a treehouse
  * Update the treehouse isBooked property from false to true upon successful booking
 
 _Write the tests first, and then move on to your implementation code!_
