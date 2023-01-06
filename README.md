# Netflix-recommendation-challenge
implemented model and refined with another model which stands 3rd in the contest of 1million$ prize worth, which aims to decrease original rmse by 10 percent with efficient time-complexity.

## The challenge(Birth of new innovation in netflix recommendation) :- 
![This is an image](https://assets3.thrillist.com/v1/image/2677075/1584x746/scale;webp=auto;jpeg_quality=60.jpg)
* In October 2006,CEO Reed Hastings was looking for a way to increase the efficiency of Cinematch, the software the company rolled out in 2000 to recommend movies you might enjoy. Over the years he'd recruited brilliant minds to tinker with the magic formula, but they'd hit a wall. He needed results. Fresh ideas. Innovation.
* Netflix, then a service peddling discs of every movie and TV show under the sun, announced "The Netflix Prize," to achieve this goal which is the reason of the birth of latent factor model ***(implemented here)*** which stood 3rd place in the contest.

## Latent factor model and implementation :- 
 ![This is an image](https://github.com/srinathsai/Netflix-recommendation-challenge/blob/main/1.jpg)
 ![This is an image](https://github.com/srinathsai/Netflix-recommendation-challenge/blob/main/2.jpg)
 
 # Dataset used :- 
 * A sample of orginal dataset provided for the contest.
 
 ## Factors of model :-
  * Number of iterations =40.
  * k =25 ***(for matrices columns)***
  * lambda=0.1 
  * learning rate = 0.001
  
 ## Output and significance :- 
 * Decreased orginal model rmse by 9 percent which is show by line plot in the code.
 
 # Improvements done to model :- 
 * A new model called Latent factor model with biases has been implemented which showed slight improvement in the rmse and this iscompared in code file.

 ## Lf factor model with biases :- 
  * It is the extension of LF model with biases added to users and ratings in the formula and below is the formula used in building model :- 
    ![This is an image](https://github.com/srinathsai/Netflix-recommendation-challenge/blob/main/3.jpg)
 
 
