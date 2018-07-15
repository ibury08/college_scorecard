# college_scorecard
College Scorecard
https://collegescorecard.ed.gov/data/
Problem & Target Audience
High school students seeking to enroll in a university have thousands of choices, each with relative advantages and disadvantages. Considering the ever-increasing cost of higher education as well as the huge variance in completion rate and career success after graduation, this single decision of where to attend has far-reaching consequences. The goal of this project is to classify universities as net positive investment, net negative investment, or neutral investment, based on historical data of its graduates. Factors affecting investment performance include post-graduation employment rate and average salary, availability of financial aid, student loan debt accrued, completion rate, etc. 
Data Acquisition
The full data set is available at the link above, compiled by the College Scorecard Project. The data is aggregated from a variety of sources, including the Integrated Postsecondary Education Data System, National Student Loan Data System and the U.S. Treasury Dept. (2.35GB).
The dataset contains data from 1996-2016, for roughly 8,000 colleges and universities, with qualitative and quantitative values for over 1800 columns, across the categories of academics, admissions, student body, cost, aid, repayment, completion, and earnings. 
Methodology
One approach to this classification problem is to determine an expected value for a given student, comprised of the cost of attendance, risk of non-completion, chances of employment post-graduation, and average salary. Based on these expected values, institutions can be classified as positive, negative or neutral. Alternatively, clustering may be used to group institutions across the multiple variables, (e.g. low risk-low reward). 

