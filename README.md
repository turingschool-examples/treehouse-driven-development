# Treehouse Driven Developent

![treehouse](https://media.giphy.com/media/L1cKe0Rek3W5Cr0o8S/giphy.gif)

What could be better than renting out a beautiful treehouse cabin for the holidays? Your goal is to use Test/Treehouse Driven Development to build out the start of a Treehouse Booking App! 

## Treehouse Data Model and Functionality

Your Treehouse implementation should meet the following requirements:

* Have the following state in the Data Model
  * `price <number>` 
  * `pricePoint <string>` (default to empty string)
  * `bedrooms <number>` 
  * `bathrooms <number>`
  * `location <string>`
  * `isBooked` (default to false) 
  
* Have the following functionality:  
  * Be able to have a reduction in price. Passing in a number to this method should decrease the price property by that percent. Think of this like a discount. 
  * Determine its price point (Similar to common review sites and booking sites, visuals are provided to give a user a quick idea of the cost. Dollar signs are used here to indicate if a treehouse is affordable or expensive)
    * If the price is 100 or less, update the `pricePoint` to '$'
    * If the price is between 101 and 200, update the `pricePoint` to '$$'
    * If the price is over 200, update the `pricePoint` to '$$$'
  
 _Write the tests first, and then move on to your implementation code!_

## Customer Data Model and Functionality 
Your Customer implementatino should meet the following requirements:

* Have the following state in the Data Model:
  * `budget <number>`  
  * `bookings` (default to an empty array)

* Have the following functionality:
  * Be able to check their budget. You may need to pass in treehouse data so that a customer can determine if they can afford the treehouse. Consider returning a boolean to explain if a user has enough money in their budget to rent the treehouse. 
  * Be able to book a passed in treehouse if it is in their budget
     * Add to bookings array
     * See their budget decrease by that amount   
     * Update the treehouse isBooked property from false to true
  * Not be able to book a passed in treehouse if it is NOT in their budget
     * See an apologetic message 
     * Their budget should not decrease
 
 _Write the tests first, and then move on to your implementation code!_

## Considerations: 
- Consider how you might make your functions pure. As best as you can, make sure your functions always return the same results if the same arguments are passed in. Attempt to make your functions independent of state or state changes. 
- ✨BONUS✨: There's a lot of data in this little application! It would be easy to just mutate the data directly, but mutating data isn't a functional practice as it may result in bugs or misunderstandings. How might you make this data immutable instead? Instead of mutating data, consider creating an entirely new value and overwriting the original. Read up more on 'immutability' in JavaScript by searching the web! 