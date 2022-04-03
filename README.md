# MechaCar_Statistical_Analysis



## Linear Regression to Predict MPG

Vehicle length and ground clearance provide a non-random amount of variance to the mpg values in the dataset. This is evident from the individual p-values that show that these variables have a significant impact on mpg. They are unlikely to provide random amounts of variance to a linear model.

The summary shows that the p-values is 5.35e-11 which is statistically significant. This provides us with sufficient evidence to reject our null hypothesis, thus the slope of our linear model is not zero. 

This linear model predicts mpg of MechaCar prototypes effectively as shows by an r-squared value of approximately 71% (0.71).

<p align="left">
   <img src="https://user-images.githubusercontent.com/91852495/161401756-7b8f160b-da31-40d5-8632-3928f50084ae.png" width="520" height="200">
</p>

<p align="left">
   <img src="https://user-images.githubusercontent.com/91852495/161401758-9e91701b-1301-4259-9411-4176cfb2fecb.png" width="520" height="400">
</p>

## Summary Statistics on Suspension Coils

Current manufacturing data does meet the design specification for the manufacturing lots in total. The variance is 62.29 which is less than the 100 pounds per square inch limit that was given for design specifications for MechaCar suspension coils.

<p align="left">
   <img src="https://user-images.githubusercontent.com/91852495/161401799-a9d0a09d-aab4-49c5-a5b8-13e86997c358.png" width="520" height="75">
</p>

However, if we look at the individual lot variance, we can see that Lot 1 and 2 meet design specifications, but Lot 3 does not (variance is equal to roughly 170).

<p align="left">
   <img src="https://user-images.githubusercontent.com/91852495/161401793-bccd99c1-29fc-4d7a-95cb-60646c8a5e9d.png" width="520" height="150">
</p>

## T-Tests on Suspension Coils

All Manufacturing Lots: 
- The p-value = 0.06 and is above our significance level.
- We do not have sufficient evidence to reject the null hypothesis. 

<p align="left">
   <img src="https://user-images.githubusercontent.com/91852495/161405559-94df434b-57e9-4033-b3a4-d141fa3c17bc.png" width="520" height="250">
</p>

Lot 1:
- The p-value = 1 and is above our significance level.
- We do not have sufficient evidence to reject the null hypothesis
- The two means are statistically similar.

<p align="left">
   <img src="https://user-images.githubusercontent.com/91852495/161405556-0602a583-5806-4797-9b13-f7d537a77c49.png" width="520" height="250">
</p>

Lot 2:
- The p-value = 0.61 and is above our significance level.
- We do not have sufficient evidence to reject the null hypothesis
- The two means are statistically similar.

<p align="left">
   <img src="https://user-images.githubusercontent.com/91852495/161405557-c533938d-f651-4abe-93c4-442d49c47f1c.png" width="520" height="250">
</p>

Lot 3:
- The p-value = 0.04 and is below our significance level.
- We have sufficient evidence to reject null hypothesis.
- The two means are statistically different.

<p align="left">
   <img src="https://user-images.githubusercontent.com/91852495/161405558-a0359155-2bcd-4411-8d3a-14fb17fbc6be.png" width="520" height="250">
</p>

## Study Design: MechaCar vs Competition

</p>
<p align="left">
   <img src="https://user-images.githubusercontent.com/91852495/161401794-eaa91886-2e04-40d4-adf3-1097f2c52601.png" width="520" height="250">
</p>
<p align="left">
   <img src="https://user-images.githubusercontent.com/91852495/161401797-55a6c863-5bc5-4c1d-869a-d9ff1b8387b5.png" width="520" height="250">
</p>



