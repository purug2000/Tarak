
## TARAK

## Introduction

In this era of modern technology that we are living in today, does not permit one to invest much of his time into knowing the world around them .Picking up the example of natural disasters ,a middle class man who wastes approximately much of his day to day life earning money for the welfare of his family ,might be completly unaware that there is a high probablity of a natural disaster in the very area that he daily visits. Everybody reads newspapers to gain info about the weather today or otherwise may come to know through the TV that there might be a proximity of an earthquake, volcanic eruption, cyclone, heavy rainfall.,etc. But what if we could get all this info daily ,even before someone steps out of his/her shelter. Well keeping this idea in mind ,here is the solution, TARAK, a web app (to be developed by priyanshu@cse.iitk.ac.in ,karanv@iitk.ac.in and triptesh@iitk.ac.in) which will provide the user with all the info he needs to safely escape any natural disaster .

## How It Works

This app will use a trained model .The model will be trained on inputs of data of many past years from various API's concerned with weather ,earthquakes ,cyclones ,etc,. and return an array of weights .The model will be trained on different subclasses of natural disasters as mentioned before ,so the array of weights returned will correspond to each of these subclasses .After the weights are returned it will take in the present day data from the various API's and apply the weights returned before on this data to return a array of probablities( these probablities will indicate which natural disasters are more prone to occur). the probablities will be sorted and listed on the app main page. 

## What Is New In Our App
