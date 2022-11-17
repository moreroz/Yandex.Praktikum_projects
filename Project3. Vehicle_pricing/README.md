If you have problems viewing the code, please use https://nbviewer.jupyter.org/
# Initial data
Data on vehicles from advertisements:
- price
- model year
- model
- condition
- cylindres
- fuel type
- the vehicle's mileage when the ad was published
- transmission
- paint colour
- whether the vehicle has 4-wheel drive (Boolean type)
- the date the ad was published
- days listed from publication to removal
# Libraries used
pandas, matplotlib, numpy
# Content
The following tasks were solved:
 - filling in missing values and data formatting
 - removing of duplicates
 - removing of errors from text part
 - checking for outlier
 - analysis of any possible correlation between different criterias and price of a car as well as frequeancy of advertising of each type of vehicle
# Main conclusions
- there is no connection between age and condition with price  
- there can be a correlation between average mileage and price
- price is also can be connected with transmission type for different group of vehicles (price for manual transmission is higher for SUV but lower for sedan).
