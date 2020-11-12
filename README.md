# Power_BI
This repository is meant to host some of the Power BI dashboards and reports I created for the Enterprise DNA challenges. 

## Files
The folders contain the dataset(in xlsx or csv format) used, the dashboard itself (in pbix), and the dashboard converted into pdf format.

## Challenges (Enterprise DNA)

### 1- Executive Sales Report
You are an analyst working at a major retailer. The sales director has approached you and asked for you to prepare a report that he can take to the executives regarding sales performance and to make sure it looks good. Unfortunately, he is unavailable for any further conversations about what he wants in the report!!

### 2- Customer Insight
You are an analyst working closely with the customer team.

The customer engagement manager (Janet) has just returned from a meeting and has been given two data sets. One contains customer sales information and the other customer engagement information.

Janet is now looking for you to produce a report that looks at both data sets and gives us some insight into customer behaviour.

She is not sure if there is a correlation between sales and engagement but would like to know either way.

There is 1 years worth of data taken from both systems.

The ball is now in your court and you need to find a way presenting this data back to Janet and the team.

### 3- HR Data Insights
News is fast spreading about who the go to analyst is in the company. (PS it’s YOU)

The HR manager (James) has approached you for some help.

He is reviewing all internal consultations that have taken place around policy changes.

They currently have a HR system in place where they create and manage the respective consultations.

The current process is that once management decide that there is going to be a change to any policy, they then create a consultation within this HR system assigning a window to hold interviews with employees.

The company policy is that every employee will be interviewed twice regarding the change. The outcome of each interview is recorded.

Unfortunately the current system doesn’t have a reporting suite.

James has managed to get the data out of the system with some help from IT but isn’t sure where to go next.

He has said he is looking to report back to his seniors around the outcomes of these interviews and what the reception has been towards a consultation. James is also keen to establish the change of outcomes between the two interviews and any other metrics that you feel are key to this report.

The ball is now in your court and you need to find a way presenting this data back to James.

### 4- Delivery App Review
You are working at a consultancy that implemented an app for a client to help them improve their delivery process and fulfillment from warehouses to store.

The app was the created so that drivers could scan the label as opposed to entering it manually while also recording the time of arrival, the time they left the store and some other variables that the management were interested in improving.

The management is now looking to evaluate how the business has reacted and how effective the app is.

The senior consultant has extracted all data from the app and placed it into the file as below.

He now wants you to use this data and create a report or dashboard to help management visualise what is happening so that we can decide what the next stage of the transformation is.

The management are particularly interested in any warehouse store combination that it’s not working well for.

The time being spent at a store.

The number of times manual entry was still used.

The number of damaged labels

If returns are being collected

A 1 in the data represents true

A 0 represents false

The ball is now in your court and you need to find a way presenting this data back to Janet and the team.

### 5- Optical Data
You are working at large opticians and they are having some issues with their current appointment system and can’t access their reporting.

The supplier is working on fixing the issue however its going to take them some time to fix the issue.

Penny (Optical Manager) has been working with IT to try and formulate an interim solution.

IT have suggested that going forward reporting should be done outside of the appointment system in a specific business intelligence tool.

Penny is yet to be convinced that this is the right solution and has little experience in BI and doesn’t want to become reliant on IT for reporting.

IT have manged to persuade her that Power BI can provide a solution which is fit for purpose and allows her to self-serve.

IT have manged to take an extract of data from the appointment system for the proof of concept.

They have now asked you as the Power BI expert to create a model that Penny and her team could easily navigate and demonstrates the capabilities of Power BI.

Penny has written several requirements that she is expecting from the solution:

As a user I need a report that allows me to see patient details- Age, last appointment, smoker, driver, when the next appointment is due, private or subsidised patient, eye test results.

Age needs to be calculated

The next appointment due is based on the following logic.

Age under 25- require an eye exam once a year

Age 25 upto and including 55- once every 6 months

Age greater than 55- should be having an appointment once every 3 months

The next appointment due is only suggested it is possible that a number of patients will often visit before their appointment is due however we want to ensure we are complying and are aware of patients who are due for an appointment.

She would love for there to be an indicator or formatting to show her which patients were due for appointments.

She doesn’t currently have this capability in her reporting but would love to be able to generate a list of patients needing appointments which she can then share with the customer contact team and help plan for resourcing.

When she selects a patient, she wants to see all their historic appointments not just the most recent. As part of the compliance framework they need to ensure that the opticians are carrying out the required tests and due diligence. She currently monitors this bye checking the left eye and right eye values from the appointments and see the difference if any between appointments and ensure that random numbers haven’t been entered.

The ball is now in your court and you need to help convince Penny that Power BI is the reporting tool for her and her team.

### 6- Insurance Complaints Data
You are working at a large insurance company who are due to undergo an internal audit with regards to their complaint’s procedure.

The company are forward thinking and currently have a data warehouse in place alongside several models.

Management have asked you to look at the model and produce insights for management level that can highlight any issues and prepare them for the audit.

Given your recent work they have complete trust in your ability and have given you freedom to present this back as you see fit.

Some factors to consider:

The most recent 2 years of data is what most stakeholders are interested in
The ability to see status changes and when they happened
Complaints broken down by the dimensions
Client Satisfaction
Worst offending brokers

### 7- Purchases, Inventory And Sales!
So this weeks challenge comes at the request of a user who has emailed in an idea.

After reviewing with the team we feel there is a great opportunity here for us to learn from what is a typical scenario faced by many businesses in various industries

Things are going to be a little different this week. The ask is very specific you must stick to it as best you can.

There are 3 datasets coming from their own respective sources.

Purchases – This data shows us the date that our business raised a purchase order for a particular product and the amount of the product.

Receiving – This when we as a company took stock of the materials, we have ordered e.g. the products arrived in our warehouse.

Billing – This is the transactional data of what we sold to which customer.

The ask is to produce a single page summary that gives us the below insight into our business.

There are 3 key things we want to see:

1. From us placing a purchase order what is the time elapsed before we receive the goods into our warehouse

2. From us receiving goods what is the time elapsed before we are billing for the goods

3.Analyse the Billing

Note: Remember that the data is coming from three different sources so there is no existing keys or relationships between the tables

### 8- Jira IT service Desk Analysis

Jira is a major player and a core tool used by many organisations whether it’s to support agile development or manage service desk tickets.

This challenge is covering of two major components that you are likely to need in your armoury as an all-round analyst;

Working with data from Jira
Building a report around IT tickets
It’s a common ask to design and implement a report that can help manage tickets being received, managing workloads and planning interventions.

Data has been extracted into a flat file and is ready for you to build out in Power BI.

The ask is to produce a report that gives us the below insight into our business.

Patterns related to; ticket status, ticket composition, ticket technician

Types of issues

Timings around different issues (time to resolve etc)

Identify areas/issues we could further train users

Identify patterns for reoccurring issues so we can identify areas which may need management intervention

After some great data profiling from our contestants a few questions were posed to the business to help us produce a report that is beneficial.

1)How to handle records where the create date is after the due date?

The business were surprised at this, and the only business reason behind this is staff creating tickets after the event (Wink, wink, nudge, nudge this is great information. There are likely issues with the business process or data capture. We should highlight these records to the business in the report.)
It could also highlight implementation issues so present these records as such.

2)How to handle records without due date?

In general there should be no tickets without due dates and any that are should be marked as incomplete as there should be no tickets without a time frame.

I hope these questions help you structure your thought process and also in terms of handling the data.

### 9- Currency Conversion and More

The ask is to produce a report from the data above that gives the user the ability to select a currency and see the associated sales and cost.

The user wants the ability to know the conversion rate that has been used. This can be an average value.

Highlight any issues with the data.

### 10-
