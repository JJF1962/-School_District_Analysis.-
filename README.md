# School_District_Analysis.
##  Overview
The objective of this School District Analysis is to analize the data available, evaluate the relation between the students performance, focused in math & reading scores, measuring the  overall passing percentages per students again the budgets and/or amount expended by the School District, aditionally the school board, alerted about a presumption of dishonesty, therefore it was required to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact; with the consequence that was requested to repeat the analysis perfomed in this module and writte a report to describe how these changes afected the overall analysis.

The class objective was to continue using Python and learn to use Pandas, Jupyter Notebook, with an overview of Anaconda and development enviroments, aditionally we continue working with CSV files and learned a better way to managing largest data to find missing values,  learning and refreshing about data types and variables, clean data, merge data frames, averages, percentages, format & re-order columns, manage calculations, index, count, bins, categorize, group and commit the final code in Git Hub, using Git Bash in my case because I have windows, all learned allow to present the following results. 
It was used the Loc method to evaluate and select all math and reading scores from the ninth grade, the  comparison operator to retrieve the  rows with "Thomas High School" in the school_name column and to retrive all rows with the "9th grade", the comparison and logical operators to retrieve the rows for reading and math score for Thomas High School 9th graders and identified the NaNs.
##  Results
The results were obtained based in the csv data provided by the School District in two confidential files named Students_complete.csv and Schhols_complete.csv, that was conformed by  a very large data, and no posibile or convenient to be handled with Excel or VBA, therefore the best option was to apply all to learned in the last two modules of CSV, Python, Jupyter Notebook and others tools required to execute the job. we saved the files with a new extension ipynb, that that constitute a file in a notebook document created by Jupyter Notebook, an interactive computational environment that helps scientists manipulate and analyze data using Python . It contains all the content from a Jupyter Notebook web application session, including computation inputs and outputs, mathematical functions, images, and explanatory text (reference. https://fileinfo.com/extension/ipynb#:~:text=An%20IPYNB%20file%20is%20a%20notebook%20document%20created,and%20outputs%2C%20mathematical%20functions%2C%20images%2C%20and%20explanatory%20text.)
### The District Summary
The first analysis, cover  and provide a District summary  that consisted into replace the reading and math scores, replacing the 9th grade for reading and math scores at Thomas High School with Nan using the loc method, as shwon in figure below.
  
![this is an image](https://github.com/JJF1962/School_District_Analysis.-/blob/main/Resources/Capture%209th%20grader%20with%20NaN1.PNG)  
  
It was repeated the School District Analysis as required, the sample of data shown a total of 15 schools, with a total of 39,170 students, the average math score was 79 and reading 81.9, meaning that 75.87% passed  math, 85.65% passed reading and the overall passing percentage was 64.85% as shown in the figure below.

![this is an image](https://github.com/JJF1962/School_District_Analysis.-/blob/main/Resources/Capture%20District%20Summary1.PNG)

Before the clean-up the average reading score 81.87% and math 78.98% (as Shown in Figure below - source:schools_complete.ipynb), we can said that excersize allow to determine that the reading score has a small variance, increase about 3.78% and 3.05% and  the math score showns a decrease of 7.84%

![tis is an image](https://github.com/JJF1962/School_District_Analysis.-/blob/main/Resources/Capture%20before%20clean%20up%20%20%25%20pass.PNG)
Source:schools_complete.csv.ipynb


### The School Summary
Replacing the 9th grader students data in the school summary data frame, the analysis showed that the average math and reading scores not varied and stayed the same, however the overall passing percentage increase from 65.64% to 90.6%  as shown in the step 11 of the charter, as a consequence of the reduction in size of the data sample, causing a positive impact in the schools results, because all the percentages in the total of categories increased as shown in the figures below

![this is and images](https://github.com/JJF1962/School_District_Analysis.-/blob/main/Resources/Capture%209th%20graders.PNG)

However, it was noticed, that the schools with less students, showed a better performance in every category, the students not only passed math & reading, also they perfomed well in other assignatures as shown in the two pictures below.

![this is an image](https://github.com/JJF1962/School_District_Analysis.-/blob/main/Resources/Capture%20Score%20by%20School%20Size.PNG)

![this is an image](https://github.com/JJF1962/School_District_Analysis.-/blob/main/Resources/Capture%20Score%20by%20School%20size%202.PNG)

### The High and Low performance School
 Aditionally, ith was analized the higest performance and the lowest performance schools, the highest performance schools were Cabrera,Thomas, Griffing, Wilson and Pena         and the lower performace Hhigh schools were Johnson, Hernandez, Huang, Figueroa and Rodriguex as shown in pictures below

![this is an images](https://github.com/JJF1962/School_District_Analysis.-/blob/main/Resources/Capture%20High%20performance%20schools.PNG)

![this is an images](https://github.com/JJF1962/School_District_Analysis.-/blob/main/Resources/Captureless%20performance%20schools.PNG)

### Replacing the nitth-grade scores affect the following:
 * Math and Reading scores by grade

![this is an images](https://github.com/JJF1962/School_District_Analysis.-/blob/main/Resources/Capture%20math%20and%20reading%20score%20by%20geade.PNG)

 
 * Scores by School Spending
if we review the data in the figure below, we can conclude that is not related the amount spended compared with the score grades, the data of the schools that spent less on their students present highest overall passing percentage (90%) than the other ones. therefore, we can conclude that is not correlation between the amount expend and the students performance.
 
![this is an images](https://github.com/JJF1962/School_District_Analysis.-/blob/main/Resources/Capture%20score%20by%20spending%201.PNG)
 

 * Scores by School size
The avergae school size, For the first two rows of the figure below, shown the good overall passing performance for  the students of the small(90%) and mediam schools (91%), however for the largest school the overall passing drop to 58%  

![this is an images](https://github.com/JJF1962/School_District_Analysis.-/blob/main/Resources/Capture%20Score%20by%20School%20size%202.PNG)

 * Scores by School type
 The students of the charter have a better performance than the District, overal passing percentage for the Charter is 90% and for the Distrct Schools only 54%, as shown in figure below.
 
![this is an images](https://github.com/JJF1962/School_District_Analysis.-/blob/main/Resources/Capture%20Score%20by%20School%20type.PNG)
 

 ## Summary

