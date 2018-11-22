## Final Project Plan: Diversity Initiatives amongst Public Four-Year Colleges in the US

Student Name: Rohit Gupta   
Email: rgupta91 [at] uw.edu   

### Introduction
[College Scorecard Data](https://collegescorecard.ed.gov/data/) is a rich dataset that enables effective decision-making by students interested in pursuing college in the US. It has a range of important information such as the costs, scores, socio-economic breakdowns, graduation percentages, future earnings, debt measures etc. It was announced as a policy initiative by President Obama in 2013 during a [State of the Union Address](https://obamawhitehouse.archives.gov/the-press-office/2013/02/12/remarks-president-state-union-address).[1] The release of the dataset was an important milestone in ensuring transparency and enabling smarter decision-making on the part of students and their parents/guardians. It can also potentially inform policy decisions as value-addition at the college level is a strong component of social mobility.[2]

### Why is it important?
While for-profit organizations such as the U.S. News & World Report and Forbes have been serving the needs of the intended audience of this dataset, the unbiased nature of the College Scorecard dataset makes it distinguished from the above. For-profit institutions usually have no obligation to full transparency, and the intelligence layer on top of the raw data can be used to push an agenda that might not be in line with the interests of the end consumers (i.e. students in this case). Having a one-size-fits-all approach like these also have a tendency to be easily gamed: colleges artificially inflate their rankings by engaging in a downward spiral of doom.[3]   
For instance, assuming that graduation rate is one of the most important criteria for a particular ranking system, inclusion/diversity efforts by an institution can be met with a decrease in the ranking as students coming from a lower socio-economic background have a higher chance of dropping out. The dataset also stretches out far into the future (earnings after ~10 years), and the sample size is respectable enough to draw meaningful conclusions (compared to for-profit services such as [Payscale](www.payscale.com), which includes a lesser number of institutions with not enough information about included sample sizes, which limits the reliability of most types of analysis). 
   
An important research question that I want to answer by using this rich dataset: Which public 4-year colleges do a great job of value-addition taking into account student capabilities at the start of the program? Results from this study might be helpful for students embarking on their collegiate journey, especially for those coming from lower socio-economic strata looking to maximize their bang for the buck. It might also potentially help in identifying the institutions that enrich lives the most, and any patterns that can be gleaned from the best performers can influence discussions around college affordability. 

### Analysis Planned
Based on input variables that allude to diversity efforts such as tuition cost, ethnic diversity, family income, and deviation in test scores, I intend to cluster the institutions. Once meaningful clustering exercise is complete, I will be looking at the figures for return on investment, earnings, and completion rates across clusters to establish comparisons with the national average. I also plan to uncover any salient patterns, such as differences in terms of the types of study programs offered (such as STEM v/s Liberal Arts) across clusters.

### Human Centered Design Considerations
Human-centered design considerations have informed my understanding of the project from the scope to execution. While a generic ranking of the colleges might be a good starting point, it usually lacks a lot of important details. This study aims to account for different starting points in terms of student opportunities/abilities and identify institutions that are ideal for serving a very specific subset of the student population. The aim is to uncover institutions that add a lot of value by ensuring higher-than-expected earnings and/or graduation rates. It can be observed that some institutions admit students who were already "destined" for success, and the schools ranked high in traditional ranking paradigms usually provide a badge of exclusivity, reinforcing the cycle across time. Patterns emerging out of these clusters might help the less-advantaged students in identifying institutions that help them meet their goals.

### Data Sources
The most recent [College Scorecard Dataset](https://ed-public-download.app.cloud.gov/downloads/Most-Recent-Cohorts-All-Data-Elements.csv) was last updated in October 2018. The dataset is rich with a lot of information (going back to mid-90s), and has 7175 observations and 1899 features. A very descriptive [data dictionary](https://collegescorecard.ed.gov/assets/CollegeScorecardDataDictionary.xlsx) is also available under the [documentation tab](https://collegescorecard.ed.gov/data/documentation/).

The data is released under the [CC0 1.0 License](https://creativecommons.org/publicdomain/zero/1.0/). 

### Caveats
However, all the information used to populate the College Scorecard Dataset is collected from students who have received a federal financial aid, which is a potential source of bias (skews towards low-income student population). The dataset has a single entry for an entire campus, with no identifiers for "branches" which can skew the results a bit as a lot of the decision parameters can vary between the main campus and the satellites (affects ~8% of students in the database).[4] Moreover, as the earnings are reported for 10 years after graduation, some discrepancies can arise amongst the students who opt for subjects with an extremely long duration of the study (for instance, students studying medicine). The differences in cost of living across states should also ideally be accounted for a more accurate comparison across schools (assuming that graduates have a certain level of preference for the state in which the school is located). There is a lot of data that seems to be missing and/or anonymized, which can prove to be a roadblock for performing the analysis satisfactorily.   

### References:   
[1] https://www.brookings.edu/opinions/understanding-the-college-scorecard/#cancel   
[2] https://www.treasury.gov/connect/blog/Pages/A-Comparison-between-the-College-Scorecard-and-Mobility-Report-Cards.aspx   
[3] https://www.economist.com/graphic-detail/2015/10/29/our-first-ever-college-rankings   
[4] https://www.brookings.edu/research/using-earnings-data-to-rank-colleges-a-value-added-approach-updated-with-college-scorecard-data/   
