# -School_District_Analysis.-
##  Overview
The objective of this School District Analysis is to analize the data available, evaluate the relation between the students performance, focused in math & reading scores, measuring the  overall passing percentages per students again the budgets and/or amount expended by the School District, aditionally the school board, alerted about a presumption of dishonesty, therefore it was required to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact; with the consequence that was requested to repeat the analysis perfomed in this module and writte a report to describe how these changes afected the overall analysis.

The class objective was to continue using Python and learn to use Pandas, Jupyter Notebook, with an overview of Anaconda and development enviroments, aditionally we continue working with CSV files and learned a better way to managing largest data to find missing values,  learning and refreshing about data types and variables, clean data, merge data frames, averages, percentages, format & re-order columns, manage calculations, index, count, bins, categorize, group and commit the final code in Git Hub, using Git Bash in my case because I have windows, all learned allow to present the following results. 
##  Results
The results were obtained based in the csv data provided by the School District in two confidential files named Students_complete.csv and Schhols_complete.csv, that was conformed by  a very large data, and no posibile or convenient to be handled with Excel or VBA, therefore the best option was to apply all to learned in the last two modules of CSV, Python, Jupyter Notebook and others tools required to execute the job. we saved the files with a new extension ipynb, that that constitute a file in a notebook document created by Jupyter Notebook, an interactive computational environment that helps scientists manipulate and analyze data using Python . It contains all the content from a Jupyter Notebook web application session, including computation inputs and outputs, mathematical functions, images, and explanatory text (reference. https://fileinfo.com/extension/ipynb#:~:text=An%20IPYNB%20file%20is%20a%20notebook%20document%20created,and%20outputs%2C%20mathematical%20functions%2C%20images%2C%20and%20explanatory%20text.)
### The District Summary
   * The first analysis, covert to analize and provide a District summary  that consisted into replace the reading and math scores, replacing the 9th grade for reading and math scores at Thomas High School with Nan using the loc method, as shwon in figure below.
  
![this is an image](https://github.com/JJF1962/School_District_Analysis.-/blob/main/Resources/Capture%209th%20grade%20with%20NaN.PNG)  
  
   *  It was repeated the School District Analysis as required, the sample of data shown a total of 15 schools, with a total of 39,170 students, the average math score was 79 and reading 81.9, meaning that 75.5% passed  math, 86.82% passed reading and the overall passing percentage was 65.64% as shown in the figure below.

![this is an image](https://github.com/JJF1962/School_District_Analysis.-/blob/main/Resources/Capture%20performance%20.PNG)

### The School Summary
Replacing the 9th grader students data in the school summary data frame, the analysis showed that the average math and reading scores not varied and stayed the same, however the overall passing percentage increase from 65.64% to 90.6%  as shown in the step 11 of the charter, as a consequence of the reduction in size of the data sample, causing a positive impact in the schools results, because all the percentages in the total of categories increased as shown in the figures below

![this is and images](https://github.com/JJF1962/School_District_Analysis.-/blob/main/Resources/Capture%209th%20graders.PNG)

However, it was noticed, that the schools with less students, showed a better performance in every category, the sutdents not only passed math & reading, also they perfomed well in other assignatures as shown in the two pictures below.

![this is an image](https://github.com/JJF1962/School_District_Analysis.-/blob/main/Resources/Capture%20Score%20by%20School%20Size.PNG)

![this is an image](https://github.com/JJF1962/School_District_Analysis.-/blob/main/Resources/Capture%20Score%20by%20School%20size%202.PNG)

### The High and Low performance School
 Aditionally, ith was analized the higest performance and the lowes performance schools, the highest performance schools were Cabrera,Thomas, Griffing, Wilson and Pena         and the lower performace Hhigh schools were Johnson, Hernandez, Huang, Figueroa and Rodriguex as shown in pictures below

![this is an images](https://github.com/JJF1962/School_District_Analysis.-/blob/main/Resources/Capture%20High%20performance%20schools.PNG)

![this is an images](https://github.com/JJF1962/School_District_Analysis.-/blob/main/Resources/Captureless%20performance%20schools.PNG)

### Replacing the nitth-grade scores affect the following:
 * Math and Reading scores by grade

![this is an images](https://github.com/JJF1962/School_District_Analysis.-/blob/main/Resources/Capture%20math%20and%20reading%20score%20by%20geade.PNG)

 
 * Scores by School Spending
 
![this is an images](
 
![this is an images](

 * Scores by School size

![this is an images](

![this is an images](


 * Scores by School type
 
![this is an images](
 
![this is an images](

 ## Summary

