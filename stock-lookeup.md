#Stock lookup

##Scope
The scope of this project is using a much more fully featured API to get and display data for stocks.

##API
There is a lot of API's available for this project. The one I use is https://www.alphavantage.co/documentation/. Like most finance API's you are required to signup. The one linked above requires signup but it is free.

##Getting started
This project definately requires reading the API documentation, having a basica understanding of query strings, and being prepared to format data provided by the endpoints. The data given is not in the most usable format. Dont get freaked out over the complexity of the data though it is a good thing. Push your brain to come up with solutions on how to format the responses so they are usable and easier for you.

##General Ideas for Features
Some cool features you can have in this is graph's such as recharts. The endpoints also allow for data lookups and time intervals think about adding that into whatever search mechanism you add.

##Important things to keep in mind
A really important thing to keep in mind is this API requires registration and use of authorization keys. DO NOT HAVE THESE IN YOUR CODE THAT YOU PUSH TO GITHUB. Look into .env or just have a file that you add to your gitignore to hold your key. There are bots that scour github repositories looking for exposed API keys. A solution for a deployed site if you deploy is maybe have the key in local storage which is another cool thing to look up and use.
