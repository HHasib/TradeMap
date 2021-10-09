# TradeMap : an interactive learning platform for new traders
Trade Map is a software that helps people with limited investing knowledge to start investing.

## Project Background
What is the one thing that is most sought after in this world? We are studying hard to get a job or start a business but what is the final goal of this. Well as everyone might have guessed it by now, it is money. What if I told you I can show you a way to make money when you are sleeping? What if I could show you a way to make your money work for you?That is what TradeMap is here for. It is an interactive learning platform for anyone to start trading securities in a safe manner.



## Project Abstract
TradeMap helps users to check price of stocks in real time. It will also help fetch news in real time for users to make informed decisions. It also has the capability to show various chart types for all types of stocks. Traders (Registered traders) can perform some technical analysis, which is to analyze if the price of a certain stocks will rise or fall, at the push of a button. There is also a plan to have a small trading platform with virtual money where traders can try out their strategies without losing any real money. Sometimes stocks prices move very rapidly and to notify the traders of such movements there will be a bot added to the program which will alert the user when the price moves below or above a certain level.

### Project Diagram
![alt text](https://github.com/HHasib/TradeMap/blob/main/HasnatHasib_TradeMap.png?raw=true)

## Project relevance
For this project it will have an object oriented design. This will enable us to create each object in a very elegant way. For example, we can create an object for trading where there will be methods for buying the stock or selling the stock. There will also be an object for the alert system that will be implemented within the trading object for automated trading. For each method we will be writing unit tests and follow the TDD method to minimize bugs within the entire code. The TDD is a very good approach for a big program like this. The UML also helps others understand how the code works. It makes is easier for a non-coder to understand the program. For version control git will be used to keep track of each update made to the code. Different teammates can work on different branches for different components of the code and then can finally merge to the main (or master) branch.


## Conceptual design
For this project we will be creating the full program from scratch. Although the program is being created from scratch, we will be using a lot of python libraries which will make it very easy for us to complete this program. 

## Background 

Link to working repository on GitHub: https://github.com/HHasib/TradeMap

**Running**
To run the program, go to the TradeMap folder in your terminal and type: 
  python3 tradeMapMain.py

## Dependencies

### Language
- python 3

### Libraries
- Matplotlib
- Pandas
- Numpy
- ScipY
- TKinter/PyQt5

### APIs
- Alphaadvantage
- pyTelegramBotAPI


## Required Resources
To create this project, there is not a need of additional resources apart from the dependencies mentioned above. You might need a python package manager such as pip to download the necessary python packages as mentioned in the dependencies section.
