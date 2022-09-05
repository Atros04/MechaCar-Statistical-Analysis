# MechaCar Statistical Analysis

## Linear Regression to Predict MPG
From the screenshot, we can see that while length of the vehicle and the gound clearance have a significant affect on the predicted MPG of the vehicle, we still have too much variance in our data to accurately predict MPG of these prototypes. The linear analysis shows the slope of our regression line being 0.72 MPG which is a good thing to show that our metrics that we measured do have an impact on the MPG performance. However, we still have 3 variables that are not significant enough to say for certain that we can predict MPG of these prototypes effectively.

## Summary Statistics on Suspension Coils
Should we choose this particular manufacturer, we do meet our requirements of the suspension variance not going over 100 PSI from the lots in total. Unfortunately, lot 3 of the suspension did fail our requirements with a variance almsot 2 times that of our requirements. We would need additional random sampling of these suspension coils to ensure that lot 3 is either an outlier or the norm for this manufacturer.

## T-Tests on Suspension Coils
Across all the lots, we cannot reject the null hypothesis and say that the observed mean of the samples is statistically similar to the population mean. However for lot 3, we do reject the null hypothesis and say the observed mean is statistically different to the population mean. Because of us having to say lot 3 is too variable for our needs, we need to check more random lots to ensure that this observed rejection is not standard for the manufacturer.

## Study Design: MechaCar vs Competition
To best test our car against the competition, we should look to study:
- Fuel efficiency in both city and highway
- Weight ratios by comparing weight of vehicles vs length & height
- Cost of our vehicle vs others of the same size and fuel efficiency
- Safety of our vehicle
- Maintenance schedule such as how often it needs to get oil changed, engine serviced, and other factors.

Ultimately these study factors will need to be tested across our final design and the available competition. We will want to test as many cars in the same class as ours to get enough data to run both t-tests and linear regression analysis. Each test will allow us to make sure that our car is going to perform as expected while allowing us to predict future performance if we improve upon the vehicle.

We will want to collect as much data as possible. Anywhere from vehicle dimensions to engine performance to chemical efficiency. On top of those measures, we will want to get data on our competitors to compare which means accessing public records or getting some vehicles to test ourselves. Ultimately, the more data we collect, the better we can make our regression analysis and t-tests.
