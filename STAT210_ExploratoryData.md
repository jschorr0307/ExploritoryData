Visualize Data
================
Jerri Schorr
10-15-2019

##### **Chapter 7**

###### **7.1**

-   Process of EDA
    -   Generate questions about your data.
    -   Search for answers by visualising, transforming, and modelling your data.
    -   Use what you learn to refine your questions and/or generate new questions.
-   More of a state of mind. Not a list of strict rules
-   We will use visualization, transformation and modeling to clean data

###### **7.2**

-   2 important questions to ask when cleaning data
    -   What type of variation occurs within my variables?
    -   What type of covariation occurs between my variables?
-   Definitions:
    -   **Variable** is measurable data
    -   **Value** is a state of a variable
    -   **Tabular data** is a set of values, each associated with a variable and an observation. Tabular data is tidy if each value is placed in its own “cell”, each variable in its own column, and each observation in its own row

###### **7.3**

-   **Variation** is the tendency for measurements to vary in data
-   Variable is **categorical** if it is in groups
    -   age ranges, hair color
-   It is **continuos** if it is an infinite set of values
    -   height, time
-   Outliers can be input error or new important data

###### **7.4**

-   Unusual data
    -   drop the entire row **OR**
    -   replace the value with **NA**
        -   easy way to replace with NA
        -   mutate(y = ifelse(y &lt; 3 | y &gt; 20, NA, y))
-   Always research the unusual data before deleting or replacing

###### **7.5**

-   **Covariation** describes the behavior between variables.
    -   Boxplots are good for covariance comparison
    -   Scatter plots are good continuous data

###### **7.6**

-   Look for patterns since there are usually clues in patterns
    -   Patterns can show covariance
    -   Models and graphs help distinguish patterns

###### **7.7**

-   This section is about ggplot2
-   Reference STAT310 notes for more info

###### **7.8**

-   FOr more info look into ggplot book and data viz book
