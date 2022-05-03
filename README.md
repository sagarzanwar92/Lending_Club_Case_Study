# Lending Club Case Study
> 


## Table of Contents
 1.  Data Sourcing & Business Understanding
 2.  Data Cleaning
     - Clean rows
     - Clean columns
     - Operate missing or partial values
     - Standerdize columns: 
         - numeric and text separately
         - keep only one of the columns that have extreamly high correlation
     - Outlier identification and treatment
 3. Derive Metrics
 4. Univariate Analysis
 5. Bivariate Analysis
 6. Conclusions:
     -  To avoid loss of business
     -  To avoid financial loss


## Conclusions and Recommendations

To avoid loss of business:
Lend out loans to candidates who can be categorized into Grade 'A' and its subgrades
Lend out loans to applicants who ->
	have High annual income (typically over 50K)
	need lesser loan (typically below 15K)
	have no previous history of loan defaults OR public bankruptcies
	are from eastern or central states 
Lend these loans at: 
	lower intrest rates
	for shorter period (36 months)


To avoid financial loss:
Avoid lending out loans to candidates who can be categorized into Grades 'B', 'F' or 'G’ and its subgrades
Avoid lend out loans to applicants who ->
	have low annual income (typically less than 50K)
	need more loan (typically over 15K)
	have previous history of loan defaults OR public bankruptcies
	are from western states
	need loans for longer period
Perform a better verification : most of the defaulters fall under 'verified' or 'Source Verified' category
Follow strict guidlines while lending the loans during the first financial quarter



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies and Versions Used
Pandas
Numpy
Matplotlib
Seaborn
Plotly Express
Itertools



## Contact
Created by [@sagarzanwar92] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->