# Objectives
Students will be able to
- define `data analysis` and `data science` and articulate the difference between them
- explain what `big data` is
- list the skills needed for data analysis
- list the skills needed for data science
- explain the different components of the data analysis ecosystem and how they relate (e.g. data, database, analysis tools, visualization)

# Agenda
0. Intro
1. Defining some terms
2. Industry examples of data analytics
3. Thought experiment: Signup flow/ product usage/engagement
3. Data analysis discussion (Healthcare Case Study)
4. Industry examples of data science
5. Thought experiment: creating a Netflix
6. Big data discussion (Netflix Case Study)
7. Data Analysis Workflow (Restaurant Case Study)
7. Examples of data visualization
8. Next steps + skills needed

# Intro (10)
- Why are we here?
- What is data analytics?

# Terms (20)
- databases
- [SQL](http://support.sas.com/documentation/cdl/en/sqlproc/63043/HTML/default/images/proc-sql-ex3a.png) | [example](https://upload.wikimedia.org/wikipedia/en/8/87/Sql_query1.png)
- [noSQL](https://www.mongodb.com/nosql-explained)
- Excel
- [big data](http://www.sas.com/en_us/insights/big-data/what-is-big-data.html)`#BuzzWord`
- data science / machine learning
- [data analytics vs data science](http://qr.ae/RwB5Yd)

# Examples of analytics (10)

| Industry    | Description           |
|-------------|-----------------------|
| healthcare  | insurance claims data |
| media       | subscription/churn    |
| advertising | ad effective ness     |
| finance     | customer segmentation |
| general     | product usage         |

**Question** Any others?

# Product usage analytics (20)
**Question** If you're a data analyst at an e-commerce company, say Bonobos, what questions/problems are you thinking about?

Some categories of analysis to consider:
- User acquisition channels
- Sign up flow
- Email engagement
- Web activity
- Activation/retention

Third-Party Tools
- [Google Analytics](https://www.google.com/analytics/standard/)
- [Mixpanel](https://mixpanel.com/engagement/)

# Healthcare claims data (30)
- [Data](https://docs.google.com/spreadsheets/d/1xB5KMLhb0ETkowUzBV6EQho9DVpzP-o0By1q1kkBnN4/edit?usp=sharing)
- [Documentation](https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Medicare-Provider-Charge-Data/Downloads/Medicare-Physician-and-Other-Supplier-PUF-Methodology.pdf)
- [News](http://www.fiercehealthfinance.com/story/cms-releases-new-physician-hospital-payment-data/2015-06-01)
- [Fact Sheet](https://www.cms.gov/Newsroom/MediaReleaseDatabase/Fact-sheets/2015-Fact-sheets-items/2015-06-01.html)

## Questions
- What is this data about?
- What types of data are being collected?
- What insights could we extract from this data?
- If you were an insurance company, what are some questions you might have?
- If you were a hospital, what are some questions you might have?
- If you were a physician, what are some questions you might have?

# Industry examples of data science (15)
| Industry    | Description                     |
|-------------|---------------------------------|
|  e-commerce | product recommendation          |
|  finance    | fraud detection                 |
|  healthcare | computer vision to detect cancer|
|  logistics  | self-driving cars, [UPS](http://priceonomics.com/why-ups-trucks-dont-turn-left/)          |

**Question** Any others?

# Data Science (15)
Some terms:
- supervised
- unsupervised
- features and target data
- models (e.g. linear regression, logistic regression, random forest, neural networks)
- training the model
- cross validation

# Creating a Netflix-esque Recommendation Engine (Time Permitting) (20)
- what are some features?
- how would the algorithm get feedback?
- how would the algorithm update based on feedback?

# Big Data (25)
- [Netflix & House of Cards](https://upload.wikimedia.org/wikipedia/en/8/87/Sql_query1.png)

## Questions
- What are some takeaways you found interesting?
- What kind of data is Netflix collecting?
- What other insights/questions would you ask of the data?

# Analytics Workflow (Time Permitting) (30)
- [Health grade analysis case study](http://fivethirtyeight.com/features/how-data-made-me-a-believer-in-new-york-citys-restaurant-grades/)
- [Health inspection data](https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/xx67-kt59)
- [Restaurant health ratings visualization](http://www.nytimes.com/interactive/dining/new-york-health-department-restaurant-ratings-map.html?_r=1&)

## Workflow
Here are some general guidelines.

If you're crafting an experiment,

0. Define the problem.
1. Define the data you'd need to collect to make a determination
2. Instrument your app/product to collect that data
3. Run your analysis and validate/invalidate your hypothesis.

If you're already working with an existing data set
0. Understand what data you have available to you
1. Identify any issues or incompleteness of the data
2. Define the problems/questions you want to ask of the data
3. Process the data so that you can easily answer those questions/

## Questions
- What is the problem definition?
- What was the author's analysis workflow?
- What methods were used?

# Visualization (5)
- [d3](https://github.com/mbostock/d3/wiki/Gallery) | [examples](https://github.com/mbostock/d3/wiki/Gallery)
- [highcharts](http://www.highcharts.com/)
- [plot.ly](https://plot.ly/)
- [tableau](http://www.tableau.com/)

# Skills (5)
## Data Analytics
- Excel
- SQL
- python & pandas

## Data Science
- python & pandas or R
- statitics, probability and linear algebra
- SQL, noSQL

## Data Visualization
- Javascript
- d3.js
- python & matplotlib/seabreeze

# Next Steps
- Data Analytics course
- Data Science course
- Intro to SQL
- Intro to Excel
- Intro to Python
- Python for Data Science
- Intro to Pandas
- Advanced Python