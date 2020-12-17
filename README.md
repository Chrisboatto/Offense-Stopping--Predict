# Offense-Stopping--Predict

**Which Pitch Stops Offense Best?**

Following my last project of clustering or grouping pitches, this project uses those groupings to determine which pitch is best at stifling offense. Within the data set, the attributes that determined the offensive output of the observation were; ExitSpeed, LaunchAngle, and Direction. 



​	**ExitSpeed** - The speed in which the ball left the bat after being hit

​	**LaunchAngle** - The relative angle parallel to the ground (raised three feet) the ball left the bat at

​	**Direction** - The direction on the field the ball went to.



The model I used was a Random Forest model as it is the model that allowed for the most accuracy in tree development. Random Forest models do well in tabular based data because it is mostly numeric and easily compiled. The one thing that I especially like about the Random Forest model is that it grows each tree simultaneously thus reducing and potentially removing all chance of error when running. I had to tune my model up a bit due to memory restrictions but the model itself still worked very well.

The end result didn't a massive statistical difference between the pitch groupings at stopping defense as you can see in the graph below, but the pitch that did the best by decimal points were the Fastballs.



**Lets take a look!!!!!!!!**


![Image of Predicting Offense](https://raw.githubusercontent.com/Chrisboatto/Offense-Stopping--Predict/main/Predicting Offense.png?token=AKUDE7FG6IHSY36UO6RKLQK73KVM6)

