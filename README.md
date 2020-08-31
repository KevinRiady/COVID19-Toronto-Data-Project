## Data Science Project: Analyzing COVID-19 Cases in Toronto

### Results:
[!% Distribution of Age Groups Affected](/Results/%_distribution_of_age_groups_affected)

### Dataset Description: 

The primary dataset contains demographic, geographic, and severity information for all confirmed and probable cases reported to and managed by Toronto Public Health since the first case reported in January 2020.
 - Includes cases that are sporadic (occurring in the community) and outbreak-associated.
 - Data are extracted from provincial communicable disease reporting system (iPHIS) and Toronto's custom COVID-19 case management system (CORES). 
 - Link: https://open.toronto.ca/dataset/covid-19-cases-in-toronto/

The Census 2016 dataset is a secondary dataset that is used to support in answering questions that pertain to the primary dataset. 
 
### Insights that can be drawn from this dataset by asking questions:
(Format: question to be asked, and an explanation of its business case impact.
 - ✅ What is the age group that has been most affected? 
   - To obtain a better understanding of which age group is most vulnerable, and which age group has been affected the least. A public warning can be given to better inform others and help them in becoming more sensitive to those who are most vulnerable.
 - 🟧 Visual map showcasing number of cases in each neighbourhood - Not possible to get postal code map since Canada Post bought rights to it. There is actually an alternative: Area Codes are made available as showcased in 'Analyzing Toronto Housing Market'.
 - ✅Which neighborhood has been most affected? Showcase the progression over time on a multiple-line plot 
   - We want to know which neighbourhood is driving the case numbers in Toronto.
   - People can be better informed and even warned to avoid visiting the top 10 most infected neighbourhoods
   - The COVID19 response team can form a more effective response plan, focused on curbing the rise of cases within those neighbourhoods
 - ✅ Case progression in Toronto over time. 
   - Noting if there were spikes at any point in time that took place between the start of COVID and the current time.
 - ✅ Source of infection: Which source is contributing the most to Canada's COVID-19 cases?  
   - Better understand where most of COVID19 reported cases are coming from: is it from travel? Hospital visits? Community transmission?
   - To inform the public to avoid activities that have the highest percentage of driving case rates.
   - To guide the COVID19 response team in enacting effective policies that discourage others from engaging in said activities (travel, gatherings, etc.)
 - ✅ How many confirmed cases? How many probable cases? 
 - ✅ What are the average duration between Episode Date and Reported Date? (time between when disease was acquired to the symptom onset/lab specimen collection date/ reported date. 
   - To gain an understanding of the duration between the individual's COVID19 contraction date and the date at which they are deemed to be positive.
 - ✅ How many cases are currently still active? 