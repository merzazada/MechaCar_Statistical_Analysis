# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
- Intercept  vehicle_length  ground_clearance are a non-random amount of variance to the mpg values in the dataset.
- The slope of the linear model considered to be zero, because the null hypothesis states that the slope is equal to zero.
- This linear model predict mpg of MechaCar prototypes effectively, because the p-value is (3.637e-12) greather then 0.05.
> <img width="1440" alt="D1" src="https://user-images.githubusercontent.com/97934695/169706269-0011b5e3-4959-4b39-abad-dbf77d770a9f.png">

## Summary Statistics on Suspension Coils

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. the current manufacturing data can not meet this design specification for all manufacturing lots in total and each lot individually because the variance in the lot2 and lot3 is really huge.

> <img width="1440" alt="D2" src="https://user-images.githubusercontent.com/97934695/169706869-8b527f7d-1646-4378-904a-342f649f7b18.png">

## T-Tests on Suspension Coils
> <img width="1440" alt="lot1" src="https://user-images.githubusercontent.com/97934695/169707150-17f8c4fa-8905-4558-af4e-3f3dc3c21da2.png">
> <img width="1440" alt="lot2" src="https://user-images.githubusercontent.com/97934695/169707154-714af9a3-7079-4687-8f34-c3972cc156d5.png">
> <img width="1440" alt="lot3" src="https://user-images.githubusercontent.com/97934695/169707162-5f10b000-5f1f-43fb-b66d-9e559d031da9.png">

## Study Design: MechaCar vs Competition
### Metrics

Collecting data for comparable models across all major manufacturers for past 3 years for the following metrics:

- Safety Feature Rating: Independent Variable
- Current Price (Selling): Dependent Variable
- Drive Package : Independent Variable
- Engine (Electric, Hybrid, Gasoline / Conventional): Independent Variable
- Resale Value: Independent Variable
- Average Annual Cost of ownership (Maintenance): Independent Variable
- MPG (Gasoline Efficiency): Independent Variable

### Hypothesis: Null and Alternative

After determining which factors are key for the MechaCar's genre:

- Null Hypothesis (Ho): MechaCar is priced correctly based on its performance of key factors for its genre.
- Alternative Hypothesis (Ha): MechaCar is NOT priced correctly based on performance of key factors for its genre.

### Statistical Tests

A multiple linear regression would be used to determine the factors that have the highest correlation/predictability with the list selling price (dependent variable); which combination has the greatest impact on price.

