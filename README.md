# Data_Bootcamp_Final_Project

This project was completed by Amanda Colombo, Lewis Percy, and Daniel Gulda in partial fulfilment of ECON-UB.0232,
Data Bootcamp, Spring 2019. I certify that the NYU Stern Honor Code applies to this project.
In particular, I have:
Clearly acknowledged the work and efforts of others when submitting written work as our own.
The incorporation of the work of others–including but not limited to their ideas, data, creative
expression, and direct quotations (which should be designated with quotation marks), or paraphrasing thereof– 
has been fully and appropriately referenced using notations both in the text
and the bibliography.
And I understand that:
Submitting the same or substantially similar work in multiple courses, either in the same semester
or in a different semester, without the express approval of all instructors is strictly forbidden.
I acknowledge that a failure to abide by NYU Stern Honor Code will result in a failing grade for
the project and course.

Project Description:

"What are the key indicators for the absence of solar panels in an area?", and "What are the key indicators for the 
frequency of solar panels in an area?" we will be utilizing the extensive deep solar dataset, compiled by 
Stanford Engineering in 2018, to answer these two questions. This dataset uses deep learning and satelite imagery to 
gather data on residential and non-residential solar installations in the United States, at the census-tract level. 
This data is then combined with a series of other demographic and meteorologic variables e.g. median age, 
average solar radiation, household income and voting patterns. The dataset is extensive, with over 72,000 rows and 169 columns.
The initial question we look to answer while analyzing this dataset is, "What are the key indicators for the absence of 
solar panels in an area?". We aim to predict absence of solar panels because this is a more difficult prediction, 
most regions in the US have some solar panel penetration today, but what governs those that do not? 
Various classification methods were trialed for accuracy, before deciding that random forest produced the most 
accurate results - with an accuracy figure of greater than 80%. From this analysis feature importance was used to 
analyse which features contributed most heavily to this performance. Our second analysis is to compare those results 
of the feature importance from classification with regression, in order to determine whether those most important features 
that predict absence are consistent for predicting volume of solar panels. The results of this analysis could be of great 
importance for policy-makers and solar developers and outline the key barriers to promote greater solar adoption or 
break into a new market. Whereas the regression results outline which features are most predictive of market growth. 
The workflow below demonstrates that land area was by far the most important feature for the accuracy of classification, whereas,
for regression daily solar radiation was the most statistically important feature.
