# Bikesharing

## Project Overview
This project used NYC CitiBike data to prepare a business proposal for a similar service in Des Moines, Iowa. We analyzed the data in NYC to get a better idea of usage, demographics, and demand. The data available included gender, usertype, start and stop times, trip duration, bike IDs, and others. The goal was to produce useful data and visualizations to include in a sales pitch for potential investors.

## Resources
- Data source: 201908-citibike-tripdata.csv
- Software: Python 3.7.11, Jupyter notebook 6.4.6, Tableau Public 2021.4.4

## Dashboard
The data was analyzed in a Tableau dashboard with a published story linked [HERE.](https://public.tableau.com/app/profile/tyler1799/viz/CitiBikeTrends_16488775653070/CitiBikeStory "Go to Tableau Public")

## Analysis Results
The analysis yielded some interesting results. The following seven views could prove useful in a pitch to investors

- ### Checkout Times for All Users: 

    ![Checkout Times for All Users](/Resources/CheckoutTimesUsers.png)
    
    This chart shows the trip duration for all users. It is filtered down to trips less than three hours. You can see that users typically ride for 5-6 minutes with a rather steep dropoff over the next 25 minutes. A very small percentage of users ride longer than 40 minutes.
    
- ### Checkout Times by Gender 

    ![Checkout Times by Gender](/Resources/CheckoutTimesGender.png)
    
    This chart is similar to the first but breaks the data down further to show differences based on gender. It became apparent that the ridership was a majority male.  Ride length tendencies remained similar between the genders.

- ### Gender Breakdown

    ![Gender Breakdown](/Resources/gender_breakdown.png)
    
    This pie chart shows the relative percentage of each gender in CitiBike's data. Roughly 2/3rds of riders are male.
    
- ### Trips per Hour by Weekday 

    ![Trips per Hour by Weekday](/Resources/trips_per_hour_by_weekday.png)
    
    Next we looked at what days and times might be the busiest. Riders were consistent over the daytime weekend hours and into the early evening. During the week rides mostly occured during the morning commute and moreso for the evening commute home. Friday afternoons also saw a pickup in usage for people who were maybe ending the workweek early or taking a much needed break.
        
- ### Trips per Hour by Gender and Weekday 

    ![Trips per Hour by Gender and Weekday](/Resources/trips_per_hour_by_gender_and_weekday.png)
    
    The same usage data was sliced further to see if genders showed different usage habits. The busy times for male and female were similar with males again showing heavier usage overall.

- ### August Peak Hours

    ![August Peak Hours](/Resources/august_peak_hours.png)
    
    This chart gives a better relative sizing to the morning and afternoon peak hours.  You can see that the morning commute creates a peak followed by a bigger peak during the evening commute.  This includes all weekdays so the consistent weekend usage flattens the peaks slightly.

- ### Trips by Gender and Weekday 

    ![Checkout Times by Gender](/Resources/trips_by_gender_by_weekday.png)
    
    This chart also looked at which days were busiest by gender but also split the data by usertype to see if subscribers or casual users had different habits.  The chart made it clear that male subscribers were the overwhelming majority of riders. There were casual customers but their numbers were low enough that the chart didn't show much difference between their gender categories.

## Summary
The data shows regular usage during commute times and consistent usage during the weekend midday hours.  There is also significantly heavier usage among males than females. It would be interesting to see if there is a driver to the split.  

One visual to investigate this might be to calculate the percentage of male riders by station.  This would allow further investigation into stations that show the highest male usage and see if surrounding businesses or other landmarks are driving the differences.  More bikes could be positioned in these locations.

Another helpful visual might be to investigate usage by birth year. Knowing the age distribution of users would help for marketing or targeted promotions.
