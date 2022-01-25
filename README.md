# Bikesharing

## Overview of the statistical analysis:

Now that we've gotten a good idea of how to create our story using tableau, there is still some more work to be done to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.

For this analysis, we use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, we create a set of visualizations to:
* Show the length of time that bikes are checked out for all riders and genders
* Show the number of bike trips for all riders and genders for each hour of each day of the week
* Show the number of bike trips for each type of user and gender for each day of the week.

## Results:

**_Deliverable 1_**: Change trip duration to a datetime format [NYC_CitiBike_Challenge.ipynb](NYC_CitiBike_Challenge.ipynb).

**_Deliverable 2_**: Visualizations for the NYC Citibike trip analysis (posted to tableau public)
1. [Checkout Times for Users](https://public.tableau.com/app/profile/kobert.lam/viz/NYCCitiBikeChallenge-CheckoutTimesforUsers/CheckoutTimesforUsers?publish=yes)
    * The top checkout duration is 5 minutes which accounted for 146,752 trips.
    * 98.83% of checkout time are within one hour.
2. [Checkout Times by Gender](https://public.tableau.com/app/profile/kobert.lam/viz/NYCCitiBikeChallenge-CheckoutTimesbyGender/CheckoutTimesbyGender?publish=yes)
    * Top checkout duration for male is 5 minutes, 6 minutes for female, and 11 minutes for unknown gender.
3. [Trips by Weekday per Hour](https://public.tableau.com/app/profile/kobert.lam/viz/NYCCitiBikeChallenge-TripsbyWeekdayperHour/TripsbyWeekdayperHour?publish=yes)
    * The top numbers of bike trips occurred on Thurday at 6 pm (44,905 trips).
    * Most trips occurred in 5-6pm and 7-9am from Monday to Friday.
4. [Trips by Gender (Weekday per Hour)](https://public.tableau.com/app/profile/kobert.lam/viz/NYCCitiBikeChallenge-TripsbyGenderWeekdayperHour/TripsbyGenderWeekdayperHour?publish=yes)
    * More male and female customers have the trip in 7-9am and 5-6pm from Monday to Friday.
5. [User Trips by Gender by Weekday](https://public.tableau.com/app/profile/kobert.lam/viz/NYCCitiBikeChallenge-UserTripsbyGenderbyWeekday/UserTripsbyGenderbyWeekday?publish=yes)
    * Most male subscribers had the trips on Mon-Fri.
    * Most female subscribers had the trips on Mon-Sat.
    * More non-subscribers (for all genders) had the trips on Sat and Sun.
6. [Summary:](https://public.tableau.com/app/profile/kobert.lam/viz/NYCCitiBikeChallenge-Summary/Summary?publish=yes)
    
    ![This is an image](images/Summary.jpg)
    * This dashboard includes 3 viz created in this module:
        1. Number of Rides
        2. Gender Breakdown
        3. Customers
    * The total number of rides in Aug 2019 was **2,344,224**. Gender breakdown: Male 65.28%, Female 25.1%, and Unknown 9.62%. Customer type breakdown: Subscriber 81.07%, Customer 18.93%.

## Summary:
* **_Deliverable 3_**: Story for the NYC Citibike (posted to tableau public)
[NYC CitiBike Challenge - Story](https://public.tableau.com/app/profile/kobert.lam/viz/NYCCitiBikeChallenge-Story/NYCCitiBikeAnalysis?publish=yes).
* Since most of the customers are male (65.28%), we can focus the business to serve the male customers based on their bike trip perferences.
* We need to make sure enough number of bikes available for rental during the peak rental period in 5-6 pm and 7-9 am from Monday to Friday, and 10am-6pm on Saturday and Sunday.

Additional visualizations are suggested for future analysis:
* Show the top starting locations with length of time that bikes are checked out.
* Show the top ending locations with length of time that bikes are checked out.
* Show the duration of bikes being parked at all locations.

