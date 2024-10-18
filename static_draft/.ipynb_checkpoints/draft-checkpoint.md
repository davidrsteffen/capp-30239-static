## What is your current goal? Has it changed since the proposal?
	My goal is to visualize trends in Medicaid enrollment, and in the impact of the Medicaid expansion on both the percentage of population enrolled in Medicaid and the percentage of population below 138% of the federal poverty level (FPL) enrolled in any public health insurance. This has changed a little bit in the process, as well I was making visualizations I realized that there was less of a relationship between expansion and Medicaid enrollment than I anticipated, but more of one between it and the percentage of the population under 138% of FPL in public health insurance.

## Are there data challenges you are facing? Are you currently depending on mock data?
	I am not depending on mock data. The main data issue I faced is that some of the datasets and variables I was hoping to use were not available in all years of interest, or were provided differently (e.g., different variable names) in different years. This made combining the individual year-level datasets a bit trickier (I did it more naively in my first attempt), which I didn’t realize until making some of the visualizations and seeing that the data I had assigned to a certain variable for each year was not correct.

## Describe each of the provided images with 2-3 sentences to give the context and how it relates to your goal.
1.	Scatterplot of % of population in Medicaid vs. % of population in public health insurance
a.	This image shows that, as would be expected, states with more people in public health insurance tend to have more people in Medicaid. Notably, there does not seem to a clear relationship between Medicaid expansion status and Medicaid percentage, perhaps because the percentage of the population in Medicaid may be determined by other factors than just expansion (e.g., state poverty rate).
2.	Scatterplot of % of population below vs. above 138% of FPL in any public health insurance
a.	This image shows that there is a general trend where states with more of their population below 138% of FPL in public insurance also have more of their population above 138% of FPL in public insurance. Another very clear trend is that non-expansion states have less of their population below 138% of FPL in public health insurance (to the left on the graph).
3.	Chloropleth of proportion of population in Medicaid in each state/Proportion of Medicaid by state: bar chart
a.	I’m not sure if it would be more helpful to display this information on a map or as a bar chart – I’m leaning towards the map. I’m also thinking about other variables that may make more sense on the graph (e.g., small multiples of the percent in Medicaid by income, age, or race).
4.	Bar charts comparing expansion vs. non-expansion in each age/gender combination, small multiples
a.	This shows that a much higher percentage of children are enrolled in Medicaid than adults. It also shows, interestingly, that there are not major differences in child enrollment rates between expansion and non-expansion states, which makes sense because the expansion was to adults based on income and many children were already eligible. Finally, among adults Medicaid enrollment rates are higher for women.
5.	Percentage in Medicaid and in public coverage under 138% by expansion status and year
a.	This shows that the trend of the rates of Medicaid enrollment and public health insurance for low-income individuals being higher in expansion states is consistent across years. I’m worried I may have a data issue for 2017 in the Medicaid enrollment data and am going to double check that.
6.	Stacked bar charts of the age distribution of Medicaid by state and gender
a.	These charts show the distribution of total Medicaid enrollment by age group in each state. I am considering updating this chart to group into children vs. adults for easier readability with less levels. I am also thinking about a way to highlight the non-expansion states, either with a different color or border or by re-ordering the states.
7.	Line charts of changes over time in % enrolled in Medicaid, labeled by expansion status
a.	This shows changes over time in the percentage of people enrolled in Medicaid, with a separate trajectory for each state. One main takeaway is that this enrollment level seems to be consistent over time, except for in 2017 (when as mentioned above, I think I may have a data issue). Expansion states do not seem to have very different trends (I may try to find data going further back to before the expansion to see if their trends may differ there).
8.	Line charts of changes over time in % enrolled in any public insurance under 138%, labeled by expansion status
a.	This shows changes over time in the percentage of people under 138% of FPL enrolled in any public insurance, with a separate trajectory for each state as in the prior graph. This enrollment level seems to also be mostly consistent over time, except for in 2017 for a few states (when as mentioned above, I think I may have a data issue). Non-expansion states do seem to consistently have lower levels of this variable in all years than all but a few of the expansion states.

## What form do you envision your final deliverable taking? (An article incorporating the images? A poster? An infographic?)
	I am currently thinking of a poster

