# USA_Airline_Flight_Analysis
This is an analysis of USA commercial flights in 2015. In this analysis, I explored flight trend, flight cancellation reasons and airlines in USA. This analysis was carried out using Power BI.
## Data Sourcing
There were four datasets used for this analysis. They are:
   * Airline data
   * Airport data
   * Cancellation Code data
   * Flight data.

The datasets were provided by Quantum Analytics.
## Data Cleaning and Transformation
The data was cleaned using Power Query Editor. 
The following steps were taken
* Merged Airline and Airport tables with Flight table
* Replaced cancellation code letters with their respective cancellation reasons
* Created columns for name of month and day of the week
* Ensured all columns are in their appropriate data type
## Data Analysis and Insights
Using DAX, I created some calculated measures. The following are the insights generated
* There were over 89,000 cancelled flights out of 5.82 million flights recorded in 2015.
* 54% of the cancelled flights was as a result of the weather while the remaining percentage of cancelled flights were caused by either the airline, national air system or security.
* California had the busiest air traffic in the year 2015 in USA.
* The highest number of flight in 2015 was recorded in the month of July. This could have been as a result of  the summer vacation.
* There were more flights during the weekdays than the weekends.
* Southwest Airline was the most reliable airline by on-time departure.
* Virgin America Airline was the least reliable airline by on-time departure.
