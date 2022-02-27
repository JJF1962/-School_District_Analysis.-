# -School_District_Analysis.-
##  Overview
The objective of this School District Analysis is to analize the data available, evaluate the relation between the students performance, focused in math & reading scores, measuring the  overall passing percentages per students again the budgets and/or amount expended by the School District, aditionally the school board, alerted about a presumption of dishonesty, therefore it was required to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact; with the consequence that was requested to repeat the analysis perfomed in this module and writte a report to describe how these changes afected the overall analysis.

The class objective was to continue using Python and learn to use Pandas, Jupyter Notebook, with an overview of Anaconda and development enviroments, aditionally we continue working with CSV files and learned a better way to managing largest data to find missing values,  learning and refreshing about data types and variables, clean data, merge data frames, averages, percentages, format & re-order columns, manage calculations, index, count, bins, categorize, group and commit the final code in Git Hub, using Git Bash in my case because I have windows, all learned allow to present the following results. 
##  Results
The results were obtained based in the csv data provided by the School District in two confidential files named Students_complete.csv and Schhols_complete.csv, that was conformed by  a very large data, and no posibile or convenient to be handled with Excel or VBA, therefore the best option was to apply all to learned in the last two modules of CSV, Python, Jupyter Notebook and others tools required to execute the job. we saved the files with a new extension ipynb, that that constitute a file in a notebook document created by Jupyter Notebook, an interactive computational environment that helps scientists manipulate and analyze data using Python . It contains all the content from a Jupyter Notebook web application session, including computation inputs and outputs, mathematical functions, images, and explanatory text (reference. https://fileinfo.com/extension/ipynb#:~:text=An%20IPYNB%20file%20is%20a%20notebook%20document%20created,and%20outputs%2C%20mathematical%20functions%2C%20images%2C%20and%20explanatory%20text.)

  * The Schoold Distric is afected in different ways, the first analysis was to replace the reading and math scores, replacing the 9th grade for reading and math scores at Thomas High School with Nan using the loc method, as shwon in figure below.
  
![this is an image]( 
  
  
  
  * and it was noticed, that the schools with less students, showed a better performance in every category, the sutdents not only passed math & reading, also they perfomed well in other assignatures as shown in the two pictures below.

![this is an image](https://github.com/JJF1962/School_District_Analysis.-/blob/main/Resources/Capture%20Score%20by%20School%20Size.PNG)

![this is an image](https://github.com/JJF1962/School_District_Analysis.-/blob/main/Resources/Capture%20Score%20by%20School%20size%202.PNG)

 * Secondly, it was performed a study of student score by school type, of course it was considered the honestity issued mentioned before related to Thomas High School, replacing the 9th grader students data in the school summary data frame, the analysis showed that the average math and reading scores not varied and stayed the same, however the overall passing percentage increase from 65% to 90% as a consequence of the reduction in size of the data sample, causing a positive impact in the schools results, because all the percentages in the total of categories increased as shown in the figures below

![this is and images](https://github.com/JJF1962/School_District_Analysis.-/blob/main/Resources/Capture%209th%20graders.PNG)

Aditionally, ith was analized the higest performance and the lowes performance schools, the highest performance schools were Cabrera,Thomas, Griffing, Wilson and Pena         and the lower performace Hhigh schools were Johnson, Hernandez, Huang, Figueroa and Rodriguex as shown in pictures below


[this is an images](https://github.com/JJF1962/School_District_Analysis.-/blob/main/Resources/Capture%20High%20performance%20schools.PNG)

[this is an images](https://github.com/JJF1962/School_District_Analysis.-/blob/main/Resources/Captureless%20performance%20schools.PNG)



