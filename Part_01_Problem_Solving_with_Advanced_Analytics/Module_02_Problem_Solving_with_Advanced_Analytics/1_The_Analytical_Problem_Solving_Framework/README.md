### crisp explanation
# CRISP-DM

This framework was originally developed by data miners in order to generalize the common approaches to defining and analyzing a problem. In this course, we will call CRISP-DM the "Problem Solving Framework".

The framework is made up of 6 steps (CRISP-DM Steps):

1. Business Issue Understanding
2. Data Understanding
3. Data Preparation
4. Analysis/Modeling
5. Validation
6. Presentation/Visualization

![CRISP-DM Framework](crisp-dm-framework.jpeg)


1. Business Issue Understanding

"This initial phase focuses on understanding the project objectives and requirements from a business perspective, and then converting this knowledge into a data mining problem definition, and a preliminary plan designed to achieve the objectives. A decision model, especially one built using the Decision Model and Notation standard can be used." - Wikipedia

* What DECISIONS needs to be made?
* What INFORMATION is needed to inform those DECISIONS?
* What type of ANALYSIS can provide the INFORMATION needed to inform those DECISIONS?


2. Data Understanding

"The data understanding phase starts with an initial data collection and proceeds with activities in order to get familiar with the data, to identify data quality problems, to discover first insights into the data, or to detect interesting subsets to form hypotheses for hidden information." - Wikipedia

* What data is needed?
* What data is available?
* What are the important characteristics(features) of the data?


3. Data Preparation

"The data preparation phase covers all activities to construct the final dataset (data that will be fed into the modeling tool(s)) from the initial raw data. Data preparation tasks are likely to be performed multiple times, and not in any prescribed order. Tasks include table, record, and attribute selection as well as transformation and cleaning of data for modeling tools." - Wikipedia

Common Steps Used in Data Preparation

* Gathering Data: When gathering data - you may need to collect data from multiple sources within your organization.

* Cleaning Data: The data set you are working with may have issues that you want to resolve prior to your analysis. This can be in the form of incorrect or missing data.

* Formatting Data: You may need to format the data by changing the way a date field appears, renaming a field, or even rotating the data, similar to using a pivot table.

* Blending Data: You may want to blend, or combine, your data with other datasets to enrich it with additional variables, similar to using the vlookup function in Excel.

* Sampling Data: Lastly, you may want to sample the dataset and work with a more manageable number of records.


4. Analysis/Modeling

"In this phase, various modeling techniques are selected and applied, and their parameters are calibrated to optimal values. Typically, there are several techniques for the same data mining problem type. Some techniques have specific requirements on the form of data. Therefore, stepping back to the data preparation phase is often needed." - Wikipedia

Important Steps
* Determine what methodology to use to solve the problem

* Determine the important factors or variables that will help solve the problem

* Build a model to solve the problem (Build Predictive Model, Validate Model, Repeat Process, Perform Analysis multiple times until we have confidence in the Analysis)

* Run the model and move to the validation phase


5. Validation

"At this stage in the project you have built a model (or models) that appears to have high quality, from a data analysis perspective. Before proceeding to final deployment of the model, it is important to more thoroughly evaluate the model, and review the steps executed to construct the model, to be certain it properly achieves the business objectives. A key objective is to determine if there is some important business issue that has not been sufficiently considered. At the end of this phase, a decision on the use of the data mining results should be reached." - Wikipedia

Important Steps
* Observe the key results on the model

* Ensure the results make sense within the content of the business problem

* Determine whether to proceed to the next step or return to a previous phase

* Repeat as many times as necessary


6. Presentation/Visualization

"Creation of the model is generally not the end of the project. Even if the purpose of the model is to increase knowledge of the data, the knowledge gained will need to be organized and presented in a way that is useful to the customer. Depending on the requirements, the deployment phase can be as simple as generating a report or as complex as implementing a repeatable data scoring (e.g. segment allocation) or data mining process. In many cases it will be the customer, not the data analyst, who will carry out the deployment steps. Even if the analyst deploys the model it is important for the customer to understand up front the actions which will need to be carried out in order to actually make use of the created models." - Wikipedia

Key Considerations
* Determine the best method of presenting insights based on the analysis

* Determine the best method of presenting insights based on the audience

* Make sure the amount of information shared is not overwhelming

* Use the results to tell a story to the audience

* For more complex analyses, you may want to walk the audience through the analytical problem solving process

* Always reference the data sources used

* Make sure your analysis supports the decisions that need to be made


