#Project Title

## TALENT SOURCING ANALYSIS







## Table of Content 

- [Description](#description)
- [Data Source](#data-source)
- [Tools Used](#tools-used)
- [ETL Processing](#etl-processing)
- [Recommended Analysis](#recommended-analysis)
- [Data Analysis Procedures](#data-analysis-procedures)
- [Results and Findings](#results-and-findings)

### Project Description

 This Record contains 5,000,000+ commercial airline flights in 2015, compiled for the U.S. DOT Air Travel Consumer Report. Each record represents a single flight, including the airline name, flight number, origin/destination airport and flight distance, as well as scheduled/actual departure and arrival times

 ![Airline Flight Home](https://github.com/AlaskaDav/Portfolio/assets/155531290/3e792361-13e8-419a-9469-2a465f8303f6)

![Airline flight Report](https://github.com/AlaskaDav/Portfolio/assets/155531290/680eb955-b5d8-4ea4-b2c3-feccda09de45)


#### Data Source

Airline FLight Data : The data sets used for the analysis includes; 
- flights.csv: containing the number of flights in the country
- airline.csv: contains the number of different airline
- airports.csv: this file contains different e=airports and locatio within the country
- cancellation_code.csv: contains the number of cancellation that occured within the perios of analysis.

#### Tools Used 

- Microsoft Excel: for easy access the contents of the file and understanding of the components of the data.
    - [Download here](http://microsoft.com)
- Powerquerry : To carry ETL process on the data
- PowerBI: For visualization and creating reports

#### ETL Processing

In the initial data preparation process, the following process was performed
1. Data Extraction: extracting data files (.csv files) from Microsoft Excel into Powerquerry for cleaning and transformation
2. Transformation process taken place involves:
   - Removing duplicate values
   - Removing null Values from the data
   - Changing data types
   - Removing empty rows and columns
   - Creating  new columns
3. Loading process involves loading the completely transformed and cleaned data into PowerBI to build dashboard for reporting and visualizations.
 
#### Recommended Analysis

1. How does the overall flight volume vary by month? By day of week? 
2. What percentage of flights in experienced a departure delay in 2015? Among 
those flights, what was the average delay time, in minutes? 
3. How does the % of delayed flights vary throughout the year? What about for 
flights leaving from Boston (BOS) specifically? 
4. How many flights were cancelled in 2015? What % of cancellations were due to 
weather? What % were due to the Airline/Carrier? 
5. Which airlines seem to be most and least reliable, in terms of on-time departure?

#### Data Analysis Procedures:

- Collected data through .csv files from MsExcel.
- Uploading the data into PowerQuery for Cleaning and analysing the contents of the data
- Requested for data clarification and data validity.
- Loaded the data into PowerBi for visualization and Presentation.
- Providing insights, presenting informations and advice.
- Creating outstanding reports for end user understanding, board of directors and shareholders.

#### Results and Findings

The analysis results are summarized as follows;
1. The total number of On-Time flights recorded during the period was 3.69millio(63.47%) while the delayed flight records 2.13million and Flight cancelled record was 89.88k
2. The highest number of distance covered was July 2015 with a total of 520,718km, this distance was covered by southwest airline and the least distance covered was in February with 429,191km.
3. There are four major reason for cancellation of flight out of which Weather condition has the highest cause with over 54% of the total percentage whereas security has no effect on the cancellation. This implies that security issues never created a threat to flight departure.
4. The analysis also clearly shows that Southwest Airline Co. has the highest volume of flight engagement for the period.
5. Among the days of tthe week, wednessday has the highest volume of flight departure, this could be as a result of the following:
 -  Mid-week vacation or relaxation
 -  Mid-week Flight Discount
 -  Schedule of meetng for organization staffs.

#### Recommendations
Based on the analysis, I recommend the following actions:
 - Improvement of airport infrastructure and managements
 - Ensure the reliability of on-Time departure with good experience
 - Implementing new technologies to optimize airport operations
 - Improving the level of communication between airlines and airport operations 

#### Limitations

There was a difficulty in representing the insight from the data in periods, so, I had to create a Date table independently from the data and then built a relationship in the model table so as to present the report in a well organized periodic manner i.e Month reporting and Dayl)


😄
💻

|Heading1|Heading2|Heading3|
|--------|--------|--------|
|Content1|Content2|Content3|
|Excel |PowerQuerry |PowerBI |

