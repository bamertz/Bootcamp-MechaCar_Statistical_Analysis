# MechaCar_Statistical_Analysis

### AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. The deliverables below are used to provide insights that may help the manufacturing team.

_____

# Deliverable 1: Linear Regression to Predict MPG

### The MechaCar prototypes were produced using multiple design specifications to identify ideal vehicle performance. Multiple metrics, such as vehicle length, vehicle weight, spoiler angle, drivetrain, and ground clearance, were collected for each vehicle.

### 1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
### 2. Is the slope of the linear model considered to be zero? Why or why not?
### 3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

![Variables](https://github.com/bamertz/MechaCar_Statistical_Analysis/blob/8ecb1f07100eb18ae00248784fb01bc7d0227bb3/Pictures/Variables.png)

Both the Vehicle length and Ground Clearance have a low chance of providing random amounts of variance. Vehicle length has a probability value of 2.60e-12 and ground clearance has a probability value of 5.21e-08. The p-value of the linear regression analysis is 5.35e-11 which is less than the significance level of .05%. Therefore, we can reject the null hypothesis, and the slope of our linear model is not zero. The R-squared value is 0.7149, which means roughly 71% of the variability of our dependent variable (mpg) is explained using this linear model.
_______

# Deliverable 2: Create Visualizations for the Trip Analysis



### The MechaCar Suspension_Coil.csv dataset contains the results from multiple production lots. In this dataset, the weight capacities of multiple suspension coils were tested to determine if the manufacturing process is consistent across production lots.

### The suspension coil’s PSI continuous variable across all manufacturing lots
### The following PSI metrics for each lot: mean, median, variance, and standard deviation.

### 1. The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

![Total Summary](https://github.com/bamertz/MechaCar_Statistical_Analysis/blob/8ecb1f07100eb18ae00248784fb01bc7d0227bb3/Pictures/Total%20Summary.png)

![Lot Summary](https://github.com/bamertz/MechaCar_Statistical_Analysis/blob/0c812312558b3d9f44bc354c45bc3d4f3ce76b16/Pictures/Lot%20Summary.png)
_______

# Deliverable 3: T-Tests on Suspension Coils

### Using your knowledge of R, perform t-tests to determine if all manufacturing lots and each lot individually are statistically different from the population mean of 1,500 pounds per square inch.

![Lot 1 T Test](https://github.com/bamertz/MechaCar_Statistical_Analysis/blob/32b4b7709c63254834fb42eac45c2576db036f5d/Pictures/Lot%201%20T%20Test.png)


![Lot 2 T Test](https://github.com/bamertz/MechaCar_Statistical_Analysis/blob/32b4b7709c63254834fb42eac45c2576db036f5d/Pictures/Lot%202%20T%20Test.png)


![Lot 3 T Test](https://github.com/bamertz/MechaCar_Statistical_Analysis/blob/32b4b7709c63254834fb42eac45c2576db036f5d/Pictures/Lot%203%20T%20Test.png)

![Overall T Test](https://github.com/bamertz/MechaCar_Statistical_Analysis/blob/8ecb1f07100eb18ae00248784fb01bc7d0227bb3/Pictures/Overall%20T%20Test.png)

_______


# Deliverable 4: Design a Study Comparing the MechaCar to the Competition
## Study Design: MechaCar vs Competition



### Using your knowledge of R, design a statistical study to compare performance of the MechaCar vehicles against performance of vehicles from other manufacturers.

### 1. What metric or metrics are you going to test?
### 2. What is the null hypothesis or alternative hypothesis?
### 3. What statistical test would you use to test the hypothesis? And why?
### 4. What data is needed to run the statistical test?

_____


