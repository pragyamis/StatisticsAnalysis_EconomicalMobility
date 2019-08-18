<b>Abstract</b>

In this project, I will look at economic mobility across generations in the contemporary USA. The data come from a large study1, based on tax records, which allowed researchers to link the income of adults to the income of the irparents several decades previously. For privacy reasons, I don’t have that individual-level data, but I do have aggregate statistics about economic mobility for several hundred communities, containing most of the American population, and covariate information about those communities. I am interested in predicting economic mobility from the characteristics of communities.

<b>Inspiration</b>

Inspired by homework assignment from CMU class 36-401 (Modern Regression) and 36-402 (Undergraduate Advanced Data Analysis).

<b>Motivation</b>

1.Hands on experince with real life datasets. 2.Practise with all techniques learnt in STAT420. 3.Discover how applied statistics can help us answer socio-economic questions.

<b>Dataset</b>

The data file mobility.csv has information on 741 communities. The variable I want to predict is economic mobility; the rest are predictor variables or covariates.
<b>Mobility:</b> The probability that a child born in 1980–1982 into the lowest quin- tile (20%) of household income will be in the top quintile at age 30. Individuals are assigned to the community they grew up in, not the one they were in as adults.
Population in 2000.
<b>Urban </b> Is the community primarily urban or rural?
<b>Black:</b> percentage of individuals who marked black (and nothing else) on cen- sus forms.
<b>Racial segregation:</b> a measure of residential segregation by race.
<b>Income segregation:</b> Similarly but for income.
<b>Segregation of poverty:</b> Specifically a measure of residential segregation for those in the bottom quarter of the national income distribution.
<b>Segregation of affluence:</b> Residential segregation for those in the top qarter.
<b>Commute:</b> Fraction of workers with a commute of less than 15 minutes.
<b>Mean income:</b> Average income per capita in 2000.
<b>Gini:</b> A measure of income inequality, which would be 0 if all incomes were perfectly equal, and tends towards 100 as all the income is concentrated among the richest individuals (see Wikipedia, s.v. “Gini coefficient”).
<b>Share 1%:</b> Share of the total income of a community going to its richest 1%.
<b>Gini bottom 99%:</b> Gini coefficient among the lower 99% of that community.
<b>Fraction middle class:</b> Fraction of parents whose income is between the na- tional 25th and 75th percentiles.
<b>Local tax rate:</b> Fraction of all income going to local taxes.
<b>Local government spending:</b> per capita.
<b>Progressivity:</b> Measure of how much state income tax rates increase with in- come.
<b>EITC:</b> Measure of how much the state contributed to the Earned Income Tax Credit (a sort of negative income tax for very low-paid wage earners).
<b>School expenditures:</b> Average spending per pupil in public schools.
<b>Student/teacher ratio:</b> Number of students in public schools divided by num- ber of teachers.
<b>Test scores:</b> Residuals from a linear regression of mean math and English test scores on household income per capita.
<b>Highschooldropoutrate:</b> Also,residualsfromalinearregressionofthedropout rate on per-capita income.
Colleges per capita
<b>College tuition:</b> in-state, for full-time students
<b>College graduation rate:</b> Again, residuals from a linear regression of the actual graduation rate on household income per capita.
<b>Labor force participation:</b> Fraction of adults in the workforce.
<b>Manufacturing:</b> Fraction of workers in manufacturing.
<b>Chinese imports:</b> Growth rate in imports from China per worker between 1990 and 2000.
<b>Teenage labor:</b> fraction of those age 14–16 who were in the labor force.
<b>Migration in:</b> Migration into the community from elsewhere, as a fraction of 2000 population.
<b>Migration out:</b> Ditto for migration into other communities.
<b>Foreign:</b> fraction of residents born outside the US.
<b>Social capital:</b> Index combining voter turnout, participation in the census, and participation in community organizations.
<b>Religious:</b> Share of the population claiming to belong to an organized religious body.
<b>Violent crime:</b> Arrests per person per year for violent crimes.
<b>Singlemotherhood:</b> Number of single female household swith children divided by the total number of households with children.
<b>Divorced:</b> Fraction of adults who are divorced.
<b>Married:</b> Ditto.
<b>Longitude:</b> Geographic coordinate for the center of the community
<b>Latitude:</b> Ditto
<b>ID:</b> A numerical code, identifying the community.
<b>Name:</b> the name of principal city or town.
<b>State:</b> the state of the principal city or town of the community.
