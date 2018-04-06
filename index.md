---
layout: base
title: SousTech Home
---

# SousTech
#### Zach Wade
		
## Description

SousTech is a system for actively monitoring and classifying culinary dishes as they are being prepared. Designed as part of a larger connected kitchen concept, SousTech will be able to determine when food is being made, as well as the specific dish being cooked. Furthermore, it should be able to determine the current status of the food such as overcooked, undercooked, or missing an important ingredient. Finally, the ultimate desire is for it to be able to communicate with the rest of the kitchen, and even other kitchens, to approximate the nutrition contents of food being made, and to provide alternatives. 

The framework around which SousTech is being developed is that of a connected kitchen. This kitchen would ideally be able to assist not only in the preparation of the food itself, but also aid the resident in making healthier consumption decisions. Already this idea is being explored in industry — Samsung notably produces a line of smart fridges, and LG has developed several internet connected stovetops — but in order to expand on this, more targeted research needs to be done. In this way, the goal of SousTech is to produce a standalone device that can be attached to the hood of a stove and serve as an anchor for connecting the stove to the rest of the kitchen. It will be outfitted with a suite of sensors, likely including gas sensors (such as for CO2 and methane), as well as cameras, spectroscopic sensors, and perhaps microphones. Using these, it will attempt the objectives mentioned above; classification of dish being the primary object, with the others serving as later goals. 
Researchers

The project is currently being run by Samadrita Das, a masters student of Human Computer Interaction, with advising from Mayank Goel, a professor with the Human Computer Interaction Institute (HCII). I will likewise be working with Professor Goel, and will join Samadrita on this project for the duration of this semester. Beginning next semester, I will take on the project myself as Samadrita will no longer be working on it. 

## Objectives 

 - 75% A reasonable objective that ought to be achievable by the end of the next semester is to have a standalone device capable of classifying the current food among several dishes with high accuracy, and determining whether it is actively burning
 - 100% For the full extent of the project, I would hope to be able to determine the current dish not only with high accuracy, but with high flexibility as well. In practice, this would mean examining several different signals to determine which ones will be most robust to changes in the environment.
 - 125% If I am able to accomplish all of this, then I will want to work on classifying more details about the food. For instance, one suggestion we had considered was determining the ingredients used in preparing the dish, and looking for some that are absent. Another avenue for development lies in cross-kitchen communication, specifically in automatically sharing recipes that are similar, but improved by some metric. 

## Milestones

 - 1st Technical Milestone
   - As part of her own work, Samadrita would like to have a functioning prototype that is able to feed live gas content analysis to a classification system. The hope is that this classifier would be able to distinguish between a few dishes within a controlled environment. 
   - This would be completed by the end of the current semester, with me helping on both hardware and software.
 - January 31st
   - Finish the remainder of the work from Samadrita’s project (assuming it is not complete)
   - Determine (and purchase) what other sensors will be useful for SousTech  
 - February 14th
   - Integrate the new hardware into the prototype
   - Update the model to use data from all of the available hardware
 - February 28th
   - Improve the model, possibly experimenting with alternate means of classification (prior experience has taught me that this stage often takes twice as long as I ever expect)
 - March 21st
   - Determine what other signals can be extracted from the available data
   - Classify whether the current dish is in an extreme state (such as burning)
 - April 4th
   - Finish adding detection for any other signals I have decided will be worth pursuing
 - April 18th
   - Make the resulting system more robust and less prone to failure
   - Plan out the design for the final prototype
 - May 2nd.
   - Have a final prototype done and in a state where it can be presented

## Literature

Speaking to Samadrita, she suggested that there has not been much prior research into the type of food analysis we wish to perform. There is some prior work on electronic noses, devices that can determine approximate odor, however those are generally focused on detecting organic compounds. However, I have been able to find some research on the topic, especially when generalizing the classification beyond gasses. Below are some of the papers I discovered

 - Emmanuelle Schaller, Jacques O. Bosset, Felix Escher, ‘Electronic Noses’ and Their Application to Food, In LWT - Food Science and Technology, Volume 31, Issue 4, 1998, Pages 305-316, ISSN 0023-6438, https://doi.org/10.1006/fstl.1998.0376.
 - B. Dębska, B. Guzowska-Świder, Application of artificial neural network in food classification, In Analytica Chimica Acta, Volume 705, Issues 1–2, 2011, Pages 283-291, ISSN 0003-2670, https://doi.org/10.1016/j.aca.2011.06.033.
 - Wen Wu and Jie Yang, "Fast food recognition from videos of eating for calorie estimation," 2009 IEEE International Conference on Multimedia and Expo, New York, NY, 2009, pp. 1210-1213. doi: 10.1109/ICME.2009.5202718

## Resources Required
	
As this is a hardware projects as well as a software one, there will be several things required in order to carry out the project. The biggest of these will be the sensors. With regards to the gas sensors, those have already been purchased and are currently being integrated into the project. For further sensors, they will need to be ordered on a case by case basis. In addition, a computer will be necessary that can talk to these devices. In practice, I imagine this will be something in the way of a small embeddable computer, although I do not know what is currently being used. All other software and hardware needed will be handled individually.

## Milestone

Details from the first milestone can be found on the [milestone](milestone) page.

Weekly milestones can be found below

 - [Update #1](update1)
 - [Update #2](update2)
 - [Update #3](update3)
 - [Update #4](update4)
 - [Update #5](update5)
