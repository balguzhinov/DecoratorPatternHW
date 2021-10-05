# DecoratorPatternHW

I have created my own example for Decorator Pattern. This example provides information about houses.
I have implemented "House" interface which contains methods getCost and getStatus of the house. 
After that, i have created several classes for the house such as "House With The Bath", "House with the garage" and etc.
Then i have an abstract class named as "HouseDecorator" which contains 2 methods that outputs description and cost.
On the main class, it outputs everything we want to output.
For instance: 

Description: Default house;
 Cost 10,000$
Description: Default house, with Bath;
 Cost 10,000$ + 5000$
Description: Default house, with Bath, Garage;
 Cost 10,000$ + 5000$ + 10,000$
Description: Default house, with Bath, Garage, with Fountain;
 Cost 10,000$ + 5000$ + 10,000$ + 12,000$
 
 That is how it looks on my own example.
