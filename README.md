# Nursing-Home-Covid_19-Analysis

INTRODUCTION: The World Health Organization defines COVID-19 as an infectious disease which is caused by a virus called CoV-2.It causes mild to moderate respiratory symptoms such as flu, cold, and pneumonia. The outbreak started in 2019 and spread rapidly throughout the world.

OBJECTIVE: The main purpose of this project is to analyze National Healthcare Safety Network(NHSN) datasets and see how COVID-19 affected healthcare Facilities, Staff, and residents during the period of three years (2020-2022).

DATA COLLECTION: This analysis contains National Healthcare Safety Network (NHSN) COVID-19 datasets for different nursing and care homes, rehabilitation centres, and healthcare facilities across States/cities in the United States of America(USA).

DATA CLEANING: The tool used for this analysis is Microsoft Excel, it was used to clean the dataset by                                                                                          Dropped some columns that were not relevant to the project.                                                                                                                                   Edited the column headers.                                                                                                                                                              Changed date format from MM/DD/YY to DD/MM/YY                                                                                                                                        
  On the States column, I changed the abbreviation for states to full by using the substitute function  i.e =Substitute(A1,"AL","ATLANTA")                                      
 Formated the columns with numeric values
 Removed blank rows and cells for 2020 datasets reduced from 491,031 to 481381, for 2021 dataset reduced from 793,491 to 779,267 and lastly  2022 dataset reduced from 786391 to 773,334.    

ANALYTICAL METHODS: To further analyze this dataset, appropriate statistical analysis was used, they are as follows;                                                                           
Correlation analysis for 2020 dataset between residents and staff confirmed COVID-19 cases. 
2021 regression analysis (residents and staff total confirmed cases).    
Descriptive statistics.
Boxplots(2020) total residents confirmed covid-19.
Sumif, Sumifs, Countif, Countifs.
Conditional Formatting.

INSIGHTS:
In 2020, the total number of occupied beds in Tupelo Nursing and Rehabilitation Center was 3,291 beds.
The total number of residents COVID-19 deaths at Milford in 2020 was 6,084 deaths.
In 2021, the total number of beds available at Riverside Healthcare Center in Michigan was 1,833 beds.
On 08/08/2021, the total number of staff-confirmed cases at Brockly was 3,094 staff.
In Minnesota, the number of times Covid-19 incidence occurred in the year 2020 was 18,376.
On 03/07/2022,25 COVID-19 incidence occurred at Crowell Memorial Home.
Correlation analysis shows a positive relationship between residents and staff confirmed COVID-19 cases.
The P Value between residents and total confirmed COVID-19 cases in 2021 is '0' which makes it a Null hypothesis.
Box plots showed outliers(abnormal values) in the upper limit.


SUGGESTIONS: 
For areas with the highest cases of Covid-19 like Brighton Rehabilitation and Wellness Center, health campaigns and awareness should be organized to educate the residents on possible preventive measures.
Healthcare workers should be well equipped with protective materials, especially at Miller's Merry  Manor.
Millers Merry Manor health facility should be placed on surveillance because it recorded the highest number of staff and residents with Covid-19 in 2021.
Proper training should be given to health workers on how to treat patients to prevent re-infection.
Health Facilities with elderly patients should be provided with more ventilators, medications, and medical personnel.
Caderbrooke care home recorded the highest death rate, it is advisable to pay special attention to the facility to prevent future deaths.
California ranks the highest state with Covid-19 cases from 2020-2022.





REFERENCES:
https://data.cms.gov/covid-19/covid-19-nursing-home-data
https://download.cms.gov/covid_nhsn/faclevel_2020.zip
https://download.cms.gov/covid_nhsn/faclevel_2021.zip
https://download.cms.gov/covid_nhsn/faclevel_2022.zip

