
## TARAK

## Introduction
Time is a free yet rare resource. Every second matters, even more so if there is a life threatening emergency. Being prepared is the only key! In 2017 alone 335 natural disasters affected over 95.6 million people, killing an additional 9,697 and costing a total of US $335 billion. This loss could have been averted had the populace been more aware of the dangers around them and how to mitigate them. Keeping this in mind, we present ## TARAK a web app which will not only alert the user about any possible mishappenings around them, but also provide them with the required support and strategies to survive, being the true 'taarak'(sanskrit for 'Protector').

## How It Works

This app will use  trained model .The model will be trained on inputs of data of many past years from various API's concerned with weather ,earthquakes ,cyclones ,etc,. and return an array of weights .The model will be trained on different subclasses of natural disasters as mentioned before ,so the array of weights returned will correspond to each of these subclasses .After the weights are returned it will take in the present day data from the various API's and apply the weights returned before on this data to return a array of probablities( these probablities will indicate which natural disasters are more prone to occur). the probablities will be sorted and listed on the app main page. 

## What Is New In Our App

We will try to implement two new things:
1) A notification system ,what are planning is to set a threshold value to the set of probablities returned .If the a probablitiy of a disaster occurence exceeds a threshold then this will activate the notification system and the user will be messaged with the info of a high chance disaster occurence today. The threshold value will be decided by manuelly going through the data .We will see the data of the days in the past when a disaster has occured and what are the probablity value returned by our model for that data and through some algorithm decide the threshold value for each disater.

2) Area setting system, the user can set an area on the app which he frequently visits ,by setting some parameters like area location ,its size(radius).,etc. This setting will give the user daily updates on the area of his concern and ensure the safety of his loved ones.

