## Project Description
* My previous project proposal, upon more research, became a bit too challenging for this project.
* Since next quarter I am leaning towards choosing more data science heavy classes, I wanted to try out data analysis with this project.
* The project involves analyzing NHANES 2017-18 examination data on oral health dentition and demographic information.
* This can be used to study the prevalence of dental caries among U.S. adults.
* The analysis focuses on the DMFT index, involving data cleaning, transformation, and visualization.

## Project Selection Rationale
* I selected this project to apply data analysis skills on real-world health data, focusing on pandas and visualization libraries.
* It improved my ability to handle complex datasets, perform statistical analysis, and potentially generate meaningful insights into public health issues.

## Major Class Themes
* Employed pandas DataFrames to filter, clean, and prepare the NHANES datasets for analysis, showcasing the flexibility and power of DataFrames in handling real-world data.
* Utilized if statements within custom functions to dichotomize outcomes and apply logical conditions, demonstrating the application of basic programming constructs in data analysis.

## Project Improvements
* If redoing the project, I would incorporate more advanced statistical analyses and predictive modeling to deepen the insights gained.
* This would leverage the data more fully and provide a richer understanding of the factors influencing dental health.

## Running the Project
* Ensure pandas, NumPy, seaborn, matplotlib, scipy, and tableone are installed.
* Data are already uploaded in GitHub, however, alternatively these can be downloaded from the NHANES website (OHXDEN_J.XPT and DEMO_J.XPT for 2017-18).
* The notebook guides through data preprocessing and analysis through embedded comments.

## Challenges
* Encountered challenges with data cleaning and merging datasets due to complex data structures and missing values.
* Resolved these through custom cleaning functions and careful dataset merging based on patient identifiers.

## Cited Sources
* Learned how to use list comprehesion and format specifier to generate columns and ensure that the integer is formatted as a two-digit number. (https://docs.python.org/3/library/stdtypes.html#str.format)
* Learned how to convert byte objects into strings to extract specific letters from cells. (https://www.geeksforgeeks.org/python-strings-decode-method/)
* Learned how to apply a function to every element of a DataFrame. (https://www.w3resource.com/pandas/dataframe/dataframe-applymap.php)
* Learned how to use the lamda function for a specific column to perform operations without defining a separate, named function. (https://www.geeksforgeeks.org/applying-lambda-functions-to-pandas-dataframe/)
* Learned how to implement Table 1 in the context of healthcare data analysis, which is a useful tool to get the summary statistics for a study population. (https://pypi.org/project/tableone/)
