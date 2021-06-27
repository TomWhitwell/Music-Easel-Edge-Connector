# Music Easel Edge Connector
 
 *** NB: THIS IS CURRENTLY UNTESTED, I will update once my prototypes are ready *** 
 
 This is an Eagle Library for the card edge for Buchla Music Easel expansion cards. This should work with BEMI Music Easels and clones, apart from the 208r rev1  which has different pinout. NB: I take no responsibility at all for anything designed using this part.
 
 This is just the edge connector library, and two boards showing the part in situ - neither of these board layouts will do anything. This is not a prototype board! 
 
 There are two versions:
 
 The Full version is the whole bottom side of a standard program card. 
 
 ![image](https://user-images.githubusercontent.com/1890544/123557200-7b0df080-d787-11eb-9cca-d3eeeda1df48.png)

The Small / Minimal version is just the edge connector itself 

![image](https://user-images.githubusercontent.com/1890544/123557351-63833780-d788-11eb-99a1-04f31a2836e2.png)

For both cards, take care to match the outline layer to the outline in the part - if you turn on tDocu layer, you'll see the measurements to make it easier to connect with the part 

The symbol has text explaining which pin is which: 

![image](https://user-images.githubusercontent.com/1890544/123557415-b361fe80-d788-11eb-875d-8ca29997e5a8.png)

Things to watch out for: 
* The edge connector runs right up to the edge of the board, so you may get design rule errors, which you can probably ignore. 
* Eagle doesn't seem to understand that the outline layer in the part connects with the outline layer on the rest of the board, so it looks as if the outline layer is incomplete. However, this doesn't seem to be a real issue - the gerbers produced have a complete outline layer. 

Thank you to Mark Borri for his help with this, and for [Portabellabs](http://www.portabellabz.be/toolbox.html) for the pinout details, in the documentation for their excellent 208 Toolbox. 

This part was designed by Tom Whitwell in Herne Hill, London, in June 2021. You are free to use it however you want. 
