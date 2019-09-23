# Uber Interview Challenge

Uber’s Driver team is interested in predicting which driver signups are most likely to start driving. To help
explore this question, we have provided a sample dataset of a cohort of driver signups 1 in January 2015.
The data was pulled a few months after they signed up to include the result of whether they actually
completed their first trip. It also includes several pieces of background information gather about the driver
and their car.

We would like you to use this data set to help understand what factors are best at predicting whether a
signup will start to drive, and offer suggestions to operationalize those insights to help Uber.

See below for a detailed description of the dataset. Please include any code you wrote for the analysis
and delete the dataset when you have finished with the challenge. Please also call out any data related
assumptions or issues that you encounter.

+ 1. Perform any cleaning, exploratory analysis, and/or visualizations to use the provided data for this
analysis (a few sentences/plots describing your approach will suffice). What fraction of the driver
signups took a first trip?

+ 2. Build a predictive model to help Uber determine whether or not a driver signup will start driving.
Discuss why you chose your approach, what alternatives you considered, and any concerns you
have. How valid is your model? Include any key indicators of model performance.

+ 3. Briefly discuss how Uber might leverage the insights gained from the model to generate more first
trips (again, a few ideas/sentences will suffice).

## Data Description:
`id`: driver_id

`city_id`: city_id this user signed up in

`signup_os`: signup device of the user (“android”, “ios”, “website”, “other”)

`signup_channel`: what channel did the driver sign up from (“offline”, “paid”, “organic”, “referral”)

`signup_timestamp`: timestamp of account creation; local time in the form ‘YYYYMMDD’

`bgc_date`: date of background check consent; in the form ‘YYYYMMDD’

`vehicle_added_date`: date when driver’s vehicle information was uploaded; in the form ‘YYYYMMDD’

`first_trip_date`: date of the first trip as a driver; in the form ‘YYYYMMDD’

`vehicle_make`: make of vehicle uploaded (i.e. Honda, Ford, Kia)

`vehicle_model`: model of vehicle uploaded (i.e. Accord, Prius, 350z)

`vehicle_year`: year that the car was made; in the form ‘YYYY’

