# Methodology Map

The Analytical Problem Solving framework helps systematically work through a business problem; however, it doesn’t help us understand which methodology to use.

The Methodology Map will help us as we decide which methodology to use to solve a business problem, and is meant to be used as we work our way through the Problem Solving Framework.

![Methodology Map](methodology-map.jpg)

There are Non-predictive and Predictive Analysis (or Business Problems):

## Non-Predictive Analysis (or Business Problems)

Non-predictive analysis can be broken down into four categories:
- Geospatial
- Segmentation
- Aggregation
- Descriptive


**- Geospatial Analysis**

This type of analysis uses location based data to help drive your conclusions. Some examples are:

* Identifying customers by a geographic dimension such as zip code, state, or county, or
* Calculating the distance between addresses and your stores, or
* Creating a trade area based upon your customer locations for further analysis

Some types of Geospatial analysis require the use of special software - such as software that can convert an address to Latitude & Longitude, or can calculate the drive time between two geographic points on a map.

**- Segmentation**

Segmentation is the process of grouping data together. Groups can be simple, such as customers who have purchased different items, to more complex segmentation techniques where you identify stores that are similar based upon the demographics of their customers.

**- Aggregation**

This methodology simply means calculating a value across a group or dimension and is commonly used in data analysis. For example, you may want to aggregate sales data for a salesperson by month - adding all of the sales closed for each month. Then, you may want to aggregate across dimensions, such as sales by month per sales territory. In this scenario, you could calculate the sales per month for each salesperson, and then add the sales per month for all salespeople in each region.

Aggregation is often done in reporting to be able to “ slice and dice” information to help managers make decisions and view performance.

**- Descriptive**

Descriptive statistics provides simple summaries of a data sample. Examples could be calculating average GPA for applicants to a school, or calculating the batting average of a professional baseball player. In our electricity supply scenario, we could use descriptive statistics to calculate the average temperature per hour, per day, or per date.

Some of the commonly used descriptive statistics are Mean, Median, Mode, Standard Deviation, and Interquartile range.


## Predictive Analysis (or Business Problems)

Predictive analysis can be 
- Data rich
- Data poor

Data Rich vs. Data Poor
Do you have data on what you are trying to predict? If so, you can proceed down the data rich path, otherwise, the data poor path is your only option.


**Data Poor Business Problems**

**- A/B Tests**

If there is not sufficient usable data to solve the problem, then we need to set up an experiment to help us get the data we need. An experiment in a business context is usually referred to as an A/B Test.


**Data Rich Business Problems**

**Numeric vs. Non-Numeric Predictive Analysis**

Assuming we have enough data to proceed with the analysis, our next decision is to look at the outcome we’re trying to predict and determine if it’s a numeric outcome or a non-numeric outcome.

**- Regression Models**

Numeric outcomes are those where the outcome is simply a number. Predicting the demand for electricity or the hourly temperature are both numeric outcomes. Models predicting numeric data are called regression models.

**- Classification Models**

Non-numeric outcomes are those where we’re trying to predict the category into which a case (e.g. customer) falls, such as whether a customer will pay on-time, pay late, or default on a payment. Another example is the whether an electronic device will fail before 1000 hours or not. Models predicting non-numeric data are called classification models.


**Numeric Variables (Regression Models)**

**Target Variables**

Target variables represent the outcome we are trying to predict. In order to select the right predictive model, we first determine whether the target variable is numeric or non-numeric. The type of numeric or non-numeric target variables will then help us select which model is appropriate. Let’s start with numeric variables.

**Types of Numeric Variables**

The three most common types of numeric variables are continuous, time-based, and count.

**- Continuous**
A continuous variable is one that can take on all values in a range. For instance your height can be measured down to many decimal places. We do not grow in even inch intervals.

**- Time-Based**
A time-based numeric variable is one where you are trying to predict what will happen over time. This is often related to forecasting.

**- Count (Discret)**
Count variables are numbers that are discrete, positive integers. They’re called count numbers because they’re used to analyze variables that you can count. As modeling these type of variables is not common in business, we won’t be covering this topic in this course.


**Non-Numeric Variables (Classification Models)**

A non-numeric variable is often called categorical, because the values of the variable take on a discrete number of possible values or categories. Examples include whether an electronic device will fail before 1000 hours or not; whether a customer will pay on-time, pay late, or default on a payment, or whether a store is classified as large, medium or small.

**Classification Models:**

**- Binary and Non-Binary**

When modeling categorical variables, the number of possible outcomes is an important factor. If there are only two possible categorical outcomes, such as Yes or No, or True or False, then the variable can be described as Binary.

If there are more than two possible categorical outcomes, such as small, medium, or large, or pay on-time, pay late, or default on a payment, then the variable can be described as non-binary. The important take-away from this lesson is the ability to determine if you should use a classification model, and whether it should be a binary model or a non-binary model.

