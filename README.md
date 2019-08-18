#Abstract

In this project, I will look at economic mobility across generations in the contemporary USA. The data come from a large study1, based on tax records, which allowed researchers to link the income of adults to the income of the irparents several decades previously. For privacy reasons, I don’t have that individual-level data, but I do have aggregate statistics about economic mobility for several hundred communities, containing most of the American population, and covariate information about those communities. I am interested in predicting economic mobility from the characteristics of communities.

#Inspiration

Inspired by homework assignment from CMU class 36-401 (Modern Regression) and 36-402 (Undergraduate Advanced Data Analysis).

#Motivation

1.Hands on experince with real life datasets. 2.Practise with all techniques learnt in STAT420. 3.Discover how applied statistics can help us answer socio-economic questions.

#Dataset

The data file mobility.csv has information on 741 communities. The variable I want to predict is economic mobility; the rest are predictor variables or covariates.
Mobility: The probability that a child born in 1980–1982 into the lowest quin- tile (20%) of household income will be in the top quintile at age 30. Individuals are assigned to the community they grew up in, not the one they were in as adults.
Population in 2000.
Urban Is the community primarily urban or rural?
Black: percentage of individuals who marked black (and nothing else) on cen- sus forms.
Racial segregation: a measure of residential segregation by race.
Income segregation: Similarly but for income.
Segregation of poverty: Specifically a measure of residential segregation for those in the bottom quarter of the national income distribution.
Segregation of affluence: Residential segregation for those in the top qarter.
Commute: Fraction of workers with a commute of less than 15 minutes.
Mean income: Average income per capita in 2000.
Gini: A measure of income inequality, which would be 0 if all incomes were perfectly equal, and tends towards 100 as all the income is concentrated among the richest individuals (see Wikipedia, s.v. “Gini coefficient”).
Share 1%: Share of the total income of a community going to its richest 1%.
Gini bottom 99%: Gini coefficient among the lower 99% of that community.
Fraction middle class: Fraction of parents whose income is between the na- tional 25th and 75th percentiles.
Local tax rate: Fraction of all income going to local taxes.
Local government spending: per capita.
Progressivity: Measure of how much state income tax rates increase with in- come.
EITC: Measure of how much the state contributed to the Earned Income Tax Credit (a sort of negative income tax for very low-paid wage earners).
School expenditures: Average spending per pupil in public schools.
Student/teacher ratio: Number of students in public schools divided by num- ber of teachers.
Test scores: Residuals from a linear regression of mean math and English test scores on household income per capita.
Highschooldropoutrate:Also,residualsfromalinearregressionofthedropout rate on per-capita income.
Colleges per capita
College tuition: in-state, for full-time students
College graduation rate: Again, residuals from a linear regression of the actual graduation rate on household income per capita.
Labor force participation: Fraction of adults in the workforce.
Manufacturing: Fraction of workers in manufacturing.
Chinese imports: Growth rate in imports from China per worker between 1990 and 2000.
Teenage labor: fraction of those age 14–16 who were in the labor force.
Migration in: Migration into the community from elsewhere, as a fraction of 2000 population.
Migration out: Ditto for migration into other communities.
Foreign: fraction of residents born outside the US.
Social capital: Index combining voter turnout, participation in the census, and participation in community organizations.
Religious: Share of the population claiming to belong to an organized religious body.
Violent crime: Arrests per person per year for violent crimes.
Singlemotherhood:Numberofsinglefemalehouseholdswithchildrendivided by the total number of households with children.
Divorced: Fraction of adults who are divorced.
Married: Ditto.
Longitude: Geographic coordinate for the center of the community
Latitude: Ditto
ID: A numerical code, identifying the community.
Name: the name of principal city or town.
State: the state of the principal city or town of the community.
