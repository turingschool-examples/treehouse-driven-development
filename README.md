# Treehouse Driven Developent

![treehouse](https://media.giphy.com/media/L1cKe0Rek3W5Cr0o8S/giphy.gif)

What could be better than renting out a beautiful treehouse cabin for the holidays? Your goal is to use Test/Treehouse Driven Development to build out the start of a Treehouse Booking App! 

## Treehouse Class
Your Treehouse class should meet the following requirements:

* Have the following properties:
  * `price <number>` 
  * `pricePoint <string>`
  * `bedrooms <number>` 
  * `bathrooms <number>`
  * `location <string>`
  * `isBooked` (default to false) 
  
* Have the following functionality:  
  * Be able to have a reduction in price. Passing in a number to this method should decrease the price property by that percent
  * Determine its price point
    * If the price is 100 or less, update the `pricePoint` to '$'
    * If the price is between 101 and 200, update the `pricePoint` to '$$'
    * If the price is over 200, update the `pricePoint` to '$$$'
  
 _Write the tests first, and then move on to your implementation code!_

## Customer Class
Your Customer class should meet the following requirements:

* Have the following properties:
  * `budget <number>`  
  * `bookings` (default to an empty array)
* Have the following functionality:
  * Be able to check their budget. Passing in an instantiation of a treehouse to this method should return a boolean value indicating if they have enough money to book that treehouse or not
  * Be able to book a passed in treehouse if it is in their budget
     * Add to bookings array
     * See their budget decrease by that amount   
     * Update the treehouse isBooked property from false to true
  * Not be able to book a passed in treehouse if it is NOT in their budget
     * See an apologetic message 
     * Their budget should not decrease
 
 _Write the tests first, and then move on to your implementation code!_
