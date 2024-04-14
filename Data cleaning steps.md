
[[../../../../3 Resources/Programación/SQL/Data Cleaning Definition, Benefits, And How-To  Tableau|Data Cleaning Definition, Benefits, And How-To  Tableau]]

When using data, most people agree that your insights and analysis are only as good as the data you are using. ==Essentially, garbage data in is garbage analysis out.== Data cleaning, also referred to as data cleansing and data scrubbing, is one of the most important steps for your organization if you want to create a culture around quality data decision-making.

	Data cleansing, data cleaning and data scrubbing are often used interchangeably. In some cases, though, data scrubbing is viewed as an element of data cleansing that specifically involves removing duplicate, bad, unneeded or old data from data sets.

Data cleaning is the process that removes data that does not belong in your dataset. Data transformation is the process of converting data from one format or structure into another. 

	Transformation processes can also be referred to as data wrangling, or data munging.

# Steps

## Step 1: Remove duplicate or irrelevant observations

Remove unwanted observations from your dataset, including duplicate observations or irrelevant observations. Duplicate observations will happen most often during data collection. 

## Step 2: Fix structural errors

Structural errors are when you measure or transfer data and notice strange naming conventions, typos, or incorrect capitalization. These inconsistencies can cause mislabeled categories or classes. For example, you may find “N/A” and “Not Applicable” both appear, but they should be analyzed as the same category.

## Step 3: Filter unwanted outliers

 there will be one-off observations where, at a glance, they do not appear to fit within the data you are analyzing.
 However, sometimes it is the appearance of an outlier that will prove a theory you are working on. Remember: just because an outlier exists, doesn’t mean it is incorrect. This step is needed to determine the validity of that number.
 
## Step 4: Handle missing data

You can’t ignore missing data because many algorithms will not accept missing values. There are a couple of ways to deal with missing data. Neither is optimal, but both can be considered.

1.  As a first option, you can drop observations that have missing values, but doing this will drop or lose information, so be mindful of this before you remove it.
2.  As a second option, you can input missing values based on other observations; again, there is an opportunity to lose integrity of the data because you may be operating from assumptions and not actual observations.
3.  As a third option, you might alter the way the data is used to effectively navigate null values.

## Step 5: Validate and QA

At the end of the data cleaning process, you should be able to answer these questions as a part of basic validation:

-   Does the data make sense?
-   Does the data follow the appropriate rules for its field?
-   Does it prove or disprove your working theory, or bring any insight to light?
-   Can you find trends in the data to help you form your next theory?
-   If not, is that because of a data quality issue?

## 5 characteristics of quality data

1.  Validity. The degree to which your data conforms to defined business rules or constraints.
2.  Accuracy. Ensure your data is close to the true values.
3.  Completeness. The degree to which all required data is known.
4.  Consistency. Ensure your data is consistent within the same dataset and/or across multiple data sets.
5.  Uniformity. The degree to which the data is specified using the same unit of measure.


