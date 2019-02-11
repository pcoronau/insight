# insight
Contains insight project

This notebook contains the code for my insight project where I built the tool UValue.

The data is not publicly available and was obtained from Thinknum. It contains 4 million reviews from Glassdoor for 
approximatly 5,000 companies. Each review is separated into positive aspects and negative aspects, along with scores
in 5 different areas: management, salary, work/life balance, company culture and career opportunities. 

I use the reviews to generate a simplified score in any area and company selected by the user. To do so, I use glove,
a word embedding algorithm, able to capture analogies, synonyms and antonyms, in general the semantic meaning of the word. My tool outputs a bar chart and a pie chart 
for each area, along with a boxplot indicating where in the distribution the selected company lies, as well as scores 
for popular categories. 

The notebook is thoroughly annotated and explained.

The web app can be found at: https://u-value.herokuapp.com, also documented in my webapp github folder.



