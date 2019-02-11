# insight
Contains insight project

This notebook contains the code for my Insight project where I built the tool UValue, developed during the first 3 weeks of the fellowship.

__Problem statement:__

The alignment between personal values and company culture is extremely important to ensure employee satisfaction. When these two are not aligned, people are at a higher risk of leaving their job. Employee churn costs between 6 to 9 months of the employee's salary, so this misalignment is costly for both the employee, who might find herself unemployed, and the company itself. 

My product aims to solve this problem by helping job seekers assess how current employees of a given company evaluate its performance in the users' values of interest. It can be also used as a tool for companies to determine if their established core values are being met.

Currently this is done by looking at Glassdoor reviews and reading thousands of reviews for each company, which is a very inefficient and time consuming process.

__My solution:__

I use Glassdoor reviews to generate a simplified score in any area and company selected by the user. To do so, I use glove, a word embedding algorithm, able to capture analogies, synonyms and antonyms, in general the semantic meaning of the word. My tool outputs a score in the form of a pie chart for each area, along with a boxplot indicating where in the distribution the selected company lies, and a bar plot containing the scores of the company for popular categories.

__The data:__

The data is not publicly available and was obtained from Thinknum. It contains 4 million reviews from Glassdoor for 
approximatly 5,000 companies. Each review is separated into positive aspects and negative aspects, along with scores
in 5 different areas: management, salary, work/life balance, company culture and career opportunities. 

__The code:__

The notebook is thoroughly annotated and explained.

The web app can be found at: https://u-value.herokuapp.com, also documented in my webapp github folder.



