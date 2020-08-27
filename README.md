## Project 1 ReadMe
## Investigating Racial and Socioeconomic Biases in Standardized Tests


### Problem Statement
As a former teacher, I am aware of racial and socioeconomic biases among standardized tests. White and Asian students have statistically performed higher on the SAT and ACT (and other standardized tests as well). An analysis from Inside HigherEd in 2015 found the average total SAT score for white and Asian students was above 1100 while the average total SAT score for Hispanic and African American students was below 1000.

There is also a correlation between low socioeconomic areas and a high rate of minorities. Low socioeconomic areas often have a large proportion of Title 1 schools. Title 1 schools are schools which have low income students as  40% more of their population. These schools often have

I picked the three states with the highest percentage of low income students to analyze their SAT and ACT participation rates and average scores: Mississippi, Louisiana, and New Mexico.

### Data Used
I imported the SAT and ACT data sets for   2017 - 2019 and used that data for my research and presentation.    
The data set contains the following information:

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|ACT and SAT|Each state in the US|
|participation17sat|float|SAT|SAT participation rate (in %) for each state for 2017|
|readingwriting17sat|int|SAT|Average SAT 'Evidence based reading and writing' score for 2017 by state|
|math17sat|int|SAT|Average SAT 'Math' score for 2017 by state|
|total17sat|int|SAT|Average total SAT score for 2017 by state|
|participation17act|float|ACT|ACT participation rate (in %) for each state for 2017|
|english17act|float|ACT|Average ACT English score for 2017 by state|
|math17act|float|ACT|Average ACT Math score for 2017 by state|
|reading17act|float|ACT|Average ACT Reading score for 2017 by state|
|science17act|float|ACT|Average ACT Science score for 2017 by state|
|composite17act|float|ACT|Average ACT Composite score for 2017 by state|
|participation18sat|float|SAT|SAT participation rate (in %) for each state for 2018|
|readingwriting18sat|int|SAT|Average SAT 'Evidence based reading and writing' score for 2018 by state|
|math18sat|int|SAT|Average SAT 'Math' score for 2018 by state|
|total18sat|int|SAT|Average total SAT score for 2018 by state|
|participation18act|float|ACT|ACT participation rate (in %) for each state for 2018|
|composite18act|float|ACT|Average ACT Composite score for 2018 by state|
|participation19sat|float|SAT|SAT participation rate (in %) for each state for 2019|
|readingwriting19sat|int|SAT|Average SAT 'Evidence based reading and writing' score for 2019 by state|
|math19sat|int|SAT|Average SAT 'Math' score for 2019 by state|
|total19sat|int|SAT|Average total SAT score for 2019 by state|
|participation19act|float|ACT|ACT participation rate (in %) for each state for 2019|
|composite19act|float|ACT|Average ACT Composite score for 2019 by state|


### Data Cleaning Process
As I imported each .csv file, I looked at each line and column to see if I could find any obvious errors. There were a few duplicate lines and a few scores typed in wrong, as evident in my code, so I fixed the errors. The ACT information also included the national average and starting in 2018, the SAT started to include data on Puerto Rico and the Virgin Islands. I removed those data points in order to make my comparison between the tests the most accurate.

In order to make my code simpler and to be able to combine all of the data sets into one, I renamed the columns to make them all unique by adding the test type and year to the section name. For example, I renamed the 'Math' column for the 2017 SAT Math score to 'math17sat'.

### Primary Findings
I looked at the average total/ composite scores for Mississippi, Louisiana, and New Mexico and compared them to the national averages for each test. I also looked at their participation rates. I was surprised to find that the average total SAT scores for my three states were right around, or even above, the national average. However, then I looked at the participation rate for each state and they were all extremely low - between 4 and 11%. The low participation rates are very small sample populations and therefore cannot be representative of the whole state.

On the other hand, the average ACT score for each of my three states was much lower than the national average. When I looked at the participation rates for the ACT, Mississippi and Louisiana both had 100% participation for all three years and New Mexico had between 63 and 67% for each year. The larger (if not complete) sample sizes are much more representative of each's state's student population and can demonstrate the average student performance of each of my three states. The average ACT score of these states demonstrates that there is a discrepancy in these low income, high minority areas.

### Research  
Both the SAT and ACT are around $50, which can be a large amount of money for a low income family. The cost of these tests can quickly add up if a student needs to take it multiple times or send their scores to more schools than they are allowed to for free. For states where the standardized are not free, both the SAT and ACT offer fee waivers for their tests and to send score reports. This allows low income students to take the test without having to worry about paying for it. The SAT fee waiver allows the student to take the test twice and send their scores to an unlimited number of schools. The SAT also partners with some schools to waive the application fee for these students. The ACT fee waiver allows the student to take the test four times and send their scores to an unlimited number of schools. The ACT fee waiver also provides the student with a free self-paced test prep course.

After doing some outside research, I learned that both Mississippi and Louisiana both make the ACT a mandatory test. Because it is mandatory, the ACT is offered for free in these states. However, low income students still don't have the funds to be able to pay for test prep courses, so they are still at a disadvantage compared to students whose families can afford a test prep course. In order to get a fee waiver, students need to talk to their school counselor and ask for help. This may be an embarrassing topic and also prevent them from taking the test.

I recommend that Title 1 schools offer test prep for low income students in either one or both tests. If a state mandates participation in a test, they should also provide a free prep course for that test so that all students are able to be set up for success.

I would also like to investigate the distribution of Title 1 schools across the US to compare that to the SAT and ACT data we have. I tried to find the distribution online but could not, which is why I used the percentage of low income students to determine which states I looked at. 
