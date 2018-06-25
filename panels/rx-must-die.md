---
description: Do we overuse Rx Java? Do Coroutines and LiveData replace it?
---

# Rx Must Die

## Description:

Is the learning curve of Rx too steep? Do we overuse Rx Java? Is LiveData an alternative? Do Coroutines and Kotlin build-in features make it obsolete?

## Panel host:

Kevin McDonagh, Novoda

## Panelists:

* Joannes Orgis, Microsoft Todo
* Ivan Morgillo, Asana Rebel
* Hasan Hosgel, Lab1886 - Mercedes-Benz
* Ash Davis, ImmobilienScout24

## Why did you choose to use Rx? 
Change of mindset from doing things in the background to defining behaviors. 

Solution to threading problems, and handling streams of data. 

It was good in good old Java times. 

Because it fits nicely with all streams and can be used for all different aspects in the app. 

### Why not
Coroutines are there to solve threading problems 


Rx is overused . No need to apply to everything . 

Do not adapt the latest things, stick to the architecture your team likes 

Difficult to get rid of 

When not used daily then dangerous to introduce errors and misunderstanding . 

If you use only Singleton you probably don't need Rx

It might be less readable .  Operators concatenation might be too much. 

Stacktrace is not readable . 

5000 extra methods 

## not to use for
Calls to the backend
Business logic that should be in a function

 

#### use for
React on change of favorites
Push from the business logic 
Rotation change 

###alternative tools
Live Data with room
Arrow library?  Different league 
Coroutines 
Rx bindings
Rx kotlin





Think about reactive scenarios. 

Do not force an architecture by your library 

Rxjava 2 was made to include backpressure

###what is missing ? 
More education on real use 
Split rxjava 
Preserve stacktraces 



