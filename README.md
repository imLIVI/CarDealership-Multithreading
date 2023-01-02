# Synchronization
## CarDealership-Multithreading
### Description
We have a manufacturer of goods (for example, cars) and a consumer (buyer). The buyer wants to buy the product, but can only do it when it is in stock (the manufacturer
made/created it)

You yourself must define the synchronization object for your actions and you yourself must describe the necessary classes. Restrictions: The manufacturer and the buyer 
are streams. The program should not be too complicated (it is not necessary to describe all the characteristics of the car in the class, we do not use them here, so 
apply the principle of abstraction)

#### Program operation:
1. Creating a producer flow and a buyer flow
2. The buyer buys the product, if possible
3. With some frequency, the manufacturer puts the product on the market
#### Program requirements
1. Each key stage should be accompanied by the output of the current status to the console, for example: Toyota manufacturer has released 1 car
2. All delays (car assembly time, the timeout of the desire to buy a car) must be made in constants (no "Magic numbers")
3. There should be several streams of buyers who will want to buy a car several times. The manufacturer produces 1 car each. The program can be completed after the sale
 of 10 cars
 
 <a href="https://github.com/netology-code/jd-homeworks/blob/master/synchronization/task1/README.md">(RUS version of description)</a>
 
 ### Result
 ![image](https://user-images.githubusercontent.com/63547457/210224346-4b016a91-70ae-4508-ab10-7d674fb9f0df.png)
