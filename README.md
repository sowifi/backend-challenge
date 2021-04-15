# :coffee: Coffee machine backend challenge
The goal of this exercise is to try to understand your code skills, architectural decisions and also the overall problem-solving 

## Challenge 
This challenge is to build a simple API to interact with a coffee machine.
We provide a set of Interfaces to implement and use on the API.

The API should have 3 endpoints to allow the following actions (Same actions as seen in `EspressoMachineInterface`):
- Make one Espresso
- Make one Double Espresso
- Check the status of the machine

## Coffee machine requirements
- The standard WaterContainer contains 2 litres but other sizes can be attached.
- The standard BeanContainer holds 50 spoons of beans but other sizes can be attached.
- A single espresso uses 1 spoon of beans and 0.05 litres of water
- A double espresso uses 2 spoons of beans and 0.10 litres of water

## Tips
- You can use any PHP framework you feel comfortable with.
- You are free to use whatever you want to save the state of the coffee machine between requests.
- The naming of API endpoints and returned data is up to you.
- Please include clear instructions on how to run your solution and list any assumptions that you have made.

## Limitations
You MUST NOT change any of the existing methods defined in the interfaces except to use other namespace.
