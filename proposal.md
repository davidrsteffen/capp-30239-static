# Name: David Steffen

# A description of your subject area of choice. (1-2 paragraphs)
  I am interested in creating visualizations of trends in Medicaid enrollment specifically and health insurance coverage more broadly. 
  Key variables would include the number of people and percentage of the population enrolled in Medicaid, enrolled in any 
  health insurance, and not enrolled in any health insurance. I would be very interested in creating visualizations that show 
  levels of and trends in enrollment by race/ethnicity, by age, and by income. I think that looking at this topic will enable 
  to me to look at geospatial features (enrollment/percentage by state), time-series characteristics (enrollment and percentage 
  changes by year, especially before/after the Medicaid expansion in the Affordable Care Act), and potentially different hierarchies 
  (e.g., I could look at specific counties within certain states like Cook County within Illinois). I would also be combining these 
  breakdowns, i.e., seeing trends over time by race/ethnicity in each state. I am less sure how I would be able to incorporate
  networks/connections and categorical variables (except for expansion vs. non-expansion states) into the visualizations.
  
# Your likely data sources. For each, include a URL, short description, and estiamtes of number of rows by columns.
Kaiser Family Foundation Data Files: These tables provide data on which states expanded Medicaid under the Affordable Care Act, 
and which did not. They also provide monthly enrollment data in Medicaid in each state.
  Medicaid Expansion Enrollment by state: 5 columns x 51 states + DC
    https://www.kff.org/affordable-care-act/state-indicator/medicaid-expansion-enrollment
  Status of State Action on the Medicaid Expansion Decision: 1 column x 51 states + DC
    https://www.kff.org/affordable-care-act/state-indicator/state-activity-around-expanding-medicaid-under-the-affordable-care-act
  Medicaid and CHIP Monthly Enrollment: 3 columns x 51 states + DC x 10 years
    https://www.kff.org/other/state-indicator/medicaid-and-chip-monthly-enrollment

Census Bureau American Community Survey datasets (all available for each year and for each state): These tables provide the number of people 
enrolled in any health insurance and in Medicaid specifically (B27007, B27010, and S2704), both overall and broken down by a number of subgroups
(race/ethnicity, age, sex, etc.) They are also available at the state and county level, and for each year from 2010 to 2023 (with some exceptions).
  B27001 Health Insurance Coverage Status by Sex by Age: 1 column x 18 sex/age subgroups x 14 years x 51 states + DC
    https://data.census.gov/table/ACSDT1Y2023.B27001
  B27001A Health Insurance Coverage Status by Age (White Alone): 1 column x 9 sex/age subgroups x 14 years x 51 states + DC
    https://data.census.gov/table/ACSDT1Y2023.B27001A
  B27001B Health Insurance Coverage Status by Age (Black or African American Alone): 1 column x 9 sex/age subgroups x 14 years x 51 states + DC
    https://data.census.gov/table/ACSDT1Y2023.B27001B
  B27007 Medicaid/Means-Tested Public Coverage by Sex by Age: 1 column x 18 sex/age subgroups x 14 years x 51 states + DC
    https://data.census.gov/table/ACSDT1Y2023.B27007
  B27010 Types of Health Insurance Coverage by Age: 6 insurance types x 4 age subgroups x 14 years x 51 states + DC
    https://data.census.gov/table/ACSDT1Y2023.B27010
  S2702 Selected Characteristics of the Uninsured in the United States: 40 characteristics x 2 columns x 14 years x 51 states + DC
    https://data.census.gov/table/ACSST1Y2023.S2702
  S2704 Public Health Insurance Coverage by Type and Selected Characteristics
    https://data.census.gov/table/ACSST1Y2023.S2704

# A list of any questions you have for us.
  No questions for now!

  http://people.cs.uchicago.edu/~mcnutt/capp-30239-static-showcase-w21/2021-static-showcases/pelczar-web.pdf
  http://people.cs.uchicago.edu/~mcnutt/capp-30239-static-showcase-w21/2021-static-showcases/cloftus-web.pdf
  http://people.cs.uchicago.edu/~mcnutt/capp-30239-static-showcase-w21/2021-static-showcases/greer.pdf
