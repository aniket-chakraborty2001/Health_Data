#  Project Name: Project_on_Health_Data
### Introdunction:
This project comes in mind when I found that some of my friends as well as their parents are suffering from diseases like Diabetics, Thyroid and Pressure and many more. Here I took the case of the three disease I mention. In the notion to make a beautiful case stydy I collected the information from my friend circle and notice that the above disease affects the youth generation more cruelly than the other generations. So I decided to make a case study on this topic.

### Data Collection:
I collected and created the data set in Excel, that contains 100 observations and 10 variuables. I collected the data from my friends and their parents. As it is my one of first few projects I am working on clean data that has no missing values and redundant data or human error.

### Data Transformation:
To do my analysis I converted the xlsx file to the csv format using online servies. The term csv stands for comma separated value files. In R we can read a file even if it is in xlsx format. But i prefer to use the csv format for better understanding and better results in analysing the data.

### Required Packages:
To complete this whole project we need some libraries and packages. They are-
* Tidyverse
* dplyr
* ggplot2

If there are any package that are not loaded in the R session, then we can use the install.packages() functions followed by the function name in quotes to install the package.

### Required Knowledge:
The knowledge which are required to build this project includes:
* Basic knpowledge of R programming
* R codes, functions and sysntax
* Data reading
* Data cleaning
* Data manipulation
* Data Visualization

### Selection of R document:
In this project we have two options. They are:
* R Script- which comes with .R extension
* R Notebook- which comes with .Rmd extension

**Here we use the R Notebook as it helps to write the code in the chunks and comments outside the chunks. It makes the R code reproducible. In other words if needed, in future we can easily change them and get our desired result.

## Into the explanation of  the project:
The project in explained in this reading in detailed through some steps. The steps are as follow:

### 1. Installing and loading required packages:
It is the first step of any data analysis, whether it is done in R or in Python. This step helps to start supporting the codes, functions and syntaxes that we will write in the console. The popular librraries that are used in this project are:
* Tidyverse
* dplyr
* ggplot2

**Note: To load a library, we use the library() function followed by the name of the library. If it gives error then it means we first have to install the package that carries the library. In such case we use install.packages() function followd by the name of the package withion quotes.**

### 2. Data reading:
In this step we first read the data using the readr library that lies in the tidyverse package. We use the read.csv() function followed the the file name in quotes. Note that for our case study the file is already uploaded in the R environment, so no file path is required to read the file.

### 3. Data Understanding:
This step deals with understanding the data virtuall and physically. We can use different functions to understand the data closely. Some functions are gives as:
* View()- gives a preview of the whole data set.
* str()- gives the types of variables in the data set.
* summary()- gives a statistical summary of the data.
* glimpse()- works same as summary() function
* head()- gives a specified number of first observations.
* tail()- gives a specified number of last observations.
* colnames()- gives the column names of the data frame.
* nrow()- returns the number of rows in the data frame.
* ncol()- returns the number of columns in the data frame.

### 4. Data Manipulation:
This include cleaning data, dealing or addressing any missing value, correcting error, renaming a variable into another name and so on. To manipulate data we use **dplyr** library with the pipe operator , denoted as **'%>%'**. We use some functions to do the following works:
* mutate()- to create a new variable depending on condition
* Select()- to select a specific variables
* filter()- to filter a observation based on condition
* group_by()- to group by result according to variable
* summarize()- to get Mathematical and Statistical outputs
* rename()- to rename a column name i.e. variable name

**Note: In a data frame rows and columns have a specific name. The rows of a data set is called Observation and the columns of the data set is called variable. Where one observation and one variable meet,there the data lies, called a cell.**

### 5. Data Analysis stage:
In this stage we use different plots such as line chart, scatter plot, bar plot, pie chart, histogram and so on to visually represent what we got from the analysis. We use **ggplot2** library and ggplot() function. We use differnt functions such as **mapping**, **aesthetic**, **facet_wrap()**, **labs** and connect them by using a "+" sign. 

**Note: Since in GitHub, Rmd file does not show the results, so I decided to add the conclusion section. Also I uploaded the html file in the files section.**

## Project Conclusions:
* There are 67 patients that are happy with their treatment bill.
* There are 33 patients that are not happy with their treatment bill.
* In the popilation Diabetics has highest contribution.
* Average bill amount for females is greater than that of males.
* Amount received by hospital is more than for females.
* Amount received by doctors is more than for females.
* There are more females whose Feedback is Bad.
* The patients of age range 20-25 are more affected by Diabetics.

