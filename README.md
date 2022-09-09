# MechaCar_Statistical_Analysis

### AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. The deliverables below are used to provide insights that may help the manufacturing team.
___

# Deliverable 1: Linear Regression to Predict MPG

The MechaCar prototypes were produced using multiple design specifications to identify ideal vehicle performance. Multiple metrics, such as vehicle length, vehicle weight, spoiler angle, drivetrain, and ground clearance, were collected for each vehicle.

![Variables](https://github.com/bamertz/MechaCar_Statistical_Analysis/blob/8ecb1f07100eb18ae00248784fb01bc7d0227bb3/Pictures/Variables.png)

Both the Vehicle length and Ground Clearance have a low chance of providing random amounts of variance. Vehicle length has a probability value of 2.60e-12 and ground clearance has a probability value of 5.21e-08. The p-value of the linear regression analysis is 5.35e-11 which is less than the significance level of .05%. Therefore, the null-hypothesis can be rejected,and the slope of the linear model is not zero. The R-squared value is 0.7149, which means a little over 71% of the variability of the dependent variable (mpg) is explained using this linear model.

___


# Deliverable 2: Create Visualizations for the Trip Analysis


The MechaCar Suspension_Coil.csv dataset contains the results from multiple production lots. In this dataset, the weight capacities of multiple suspension coils were tested to determine if the manufacturing process is consistent across production lots.

The suspension coil’s PSI continuous variable across all manufacturing lots
The following PSI metrics for all 3 lots combined: mean, median, variance, and standard deviation.

Total Summary:

![Total Summary](https://github.com/bamertz/MechaCar_Statistical_Analysis/blob/8ecb1f07100eb18ae00248784fb01bc7d0227bb3/Pictures/Total%20Summary.png)

The following PSI metrics for each lot: mean, median, variance, and standard deviation.

Lot Summary:

![Lot Summary](https://github.com/bamertz/MechaCar_Statistical_Analysis/blob/0c812312558b3d9f44bc354c45bc3d4f3ce76b16/Pictures/Lot%20Summary.png)

Lots 1 & 2 are similar with both medians reporting at 1500 PSIand the means just .02 over that for Lot 2. However, Lot 3 measures at 1496.14 for its mean with a variance of 170.28.

Since the design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. The current manufacturing data meets this design specification for all manufacturing lots in total but Lot 3 does not meet it individually.


_______

# Deliverable 3: T-Tests on Suspension Coils

The following T-Tests were created in R to determine if all manufacturing lots and each lot individually are statistically different from the population mean of 1,500 pounds per square inch.

![Lot 1 T Test](https://github.com/bamertz/MechaCar_Statistical_Analysis/blob/32b4b7709c63254834fb42eac45c2576db036f5d/Pictures/Lot%201%20T%20Test.png)


![Lot 2 T Test](https://github.com/bamertz/MechaCar_Statistical_Analysis/blob/32b4b7709c63254834fb42eac45c2576db036f5d/Pictures/Lot%202%20T%20Test.png)


![Lot 3 T Test](https://github.com/bamertz/MechaCar_Statistical_Analysis/blob/32b4b7709c63254834fb42eac45c2576db036f5d/Pictures/Lot%203%20T%20Test.png)

![Overall T Test](https://github.com/bamertz/MechaCar_Statistical_Analysis/blob/8ecb1f07100eb18ae00248784fb01bc7d0227bb3/Pictures/Overall%20T%20Test.png)

Lots 1 & 2 are statistically similar with both of them recording P-values above the significance level of .05, while lot 3 has a P-value of 0.04168. This means Lot 3's supsension coil PSI is statistically different from the population mean.
_______


# Deliverable 4: Design a Study Comparing the MechaCar to the Competition
## Study Design: MechaCar vs Competition

This is a statistical study to compare the performance of the MechaCar vehicles against performance of vehicles from other manufacturers using R. 

- The metrics related to performance that I would test between MechaCar and other vehicles would be horspower, acceleration, miles per gallon, and cost to manufacture. 
  
- Hypothesis: There is no statistical difference between MechaCar and other competitor vehicles cost to manufacture. 
 
- Null Hypothesis:There is statistical difference between MechaCar and other competitor vehicles cost to manufacture. 
   
- Conduct a T-Test to determine if there is a statistical difference between the MechaCar and its competitors to see if given the same criteria, the MechaCar is a lower cost to manufacture and therefore more profitable.

- The data needed to do these statiscial tests would be each vehicles miles per gallons or fuel efficiancy ratings, vehicle cost, vehicle cost to manufacture, acceleration times, and horsepower.

_____


