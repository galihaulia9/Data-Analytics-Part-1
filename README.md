# Data-Analytics-Part-1
Week eight learns about Data Analytics such as data basics, data manipulation, and data cleansing.

## What is Data Analytics?
Data analytics is the process of inspecting a set of data that is useful for drawing conclusions from existing information and improving software systems. Data analytics technology and techniques are used in the commercial industry which makes it easier for companies to get better and more accurate results.
This week learns about data analytics which is divided into sub-materials namely data basics, data manipulation, and data cleansing.

## Data Basics
Basic data is a collection of information that is stored in a computer and can be systematically examined, processed, or manipulated using a computer program.
- What is data?

Data is something that refers to the facts of an observed object, either in the form of numbers or words. Data can also be thought of as information used in the process of drawing conclusions, especially in statistics.

## Describe Basic Data Variable Types
Variable data can be divided into 2 types, namely : Category and Numeric.

The Category are further divided into 2, namely Nominal and Ordinal.
- Nominal : A type of data that consists of categories that cannot be sorted or ranked. This is also called a nominal scale. However, nominal data can sometimes be both qualitative and quantitative. Some examples of nominal data are symbols, words, letters, and the gender of a person.
- Ordinal : A category of data that has a natural order. It is often used in surveys, questionnaires, and the fields of finance and economics. Ordinal data stands out because it is impossible to distinguish between data values. An example is clothing size (small, medium, and large are not measurable differences, but are clearly ordered to show size comparison).

The Numeric are further divided into 2, namely Discrete and Continues.
- Discrete : Variables in the form of categorizing data or distinguishing or grouping certain types. An example is a father with a total number of family members of 10, so the number of dependents as a father is 9.
- Continues : Data obtained from the results of counting or measurement, so data is not only in the form of whole numbers, but can also be in decimal form. Examples are the number of correct or incorrect in a test, score, ranking, height, weight, length, distance etc.

## Variable Data Types
<img width="672" alt="image" src="https://github.com/galihaulia9/Data-Analytics-Part-1/assets/125258524/331adf59-99ad-489e-ad53-cfcd135a3af4">

## Structured Data
<img width="371" alt="image" src="https://github.com/galihaulia9/Data-Analytics-Part-1/assets/125258524/ca6c99fc-13b9-4e98-a7a4-5a40967eb020">

## Describe Data Categories
1. Qualitative Data : Is information that is descriptive and cannot be measured by numbers. Example : Observing or observing someone's post comments where there are negative, positive, or neutral comments on various social media such as Instagram, Twitter, etc.
2. Quantitative Data : Is a set of information that can be measured, counted, and compared on a numerical scale. Example : Number of followers and posts on social media, a person's height, temperature, etc.
3. Structured Data : Structured data refers to information that is highly organized and can be easily stored and accessed from a database with a simple search engine algorithm. Examples : excel files, SQL databases, sales data, etc.
4. Unstructured Data : Is a type of big data where the data does not have any specific form or structure. Unstructured data is more qualitative than quantitative, which means it is more characteristic and categorical. Examples : video files, social media content, etc.
5. Metadata : Metadata is a collection of data that contains information from data so that the data is easy to manage again. Metadata can provide information about the origin of the data, who created it, the purpose of creating the data, and others. Example : a music file can provide information about the artist, song title, album, year of release, music genre, etc.
6. Big Data : Is data that is so large, fast and complex that it is impossible to process traditionally or manually. This data can be collected from various sources in raw form, filtered and processed so that it can be delivered according to its needs and use. Example : analyzing dropout rates, enrollment numbers, and student achievement rates to optimize curriculum.

## Examples of Big Data Characteristics
- Velocity : Instagram users grow by more than 100 million accounts every year.
- Volume : Instagram has stored 69.23% of the personal data of over one billion users worldwide.
- Variety : The Instagram platform can vary in form such as there is data in the form of personal data forms, photos, videos, or even instastory filter data.
- Veracity : The existence of a user with the user's account name (ID) from platforms such as Instagram, Facebook and others.
- Value : The Instagram Stories feature is used by 500 million users every day. This shows that the feature that allows users to create instant posts is quite popular.

## Data Manipulation
The ETL (extract, transform, and load) process is a step in data manipulation that is usually used to manage, clean, transform and move data from various sources.
The basics of ETL in data manipulation :
- Extract is a stage to retrieve data from existing data sources such as text files, spreadsheets etc.
- Transformation at this stage involves processing and modifying the data that has been entered into Jupyter so that the data we will use is in accordance with the analysis needs. This data transformation is used to clean, merge and change the data structure if needed.
- This stage of load is the stage of storing the processed data in the repository which will be used for further analysis.

## Data Cleansing
Clean data is a stage used to clean data from common problems such as NULL values, special characters, unnecessary spaces, inconsistent formats, and duplicate data. This stage is needed so that the data can be processed further without flaws and errors.
#### 1. Handling NULL
Handling NULL is a data cleaning process to replace NULL (empty values) with default values. Example :

<img width="219" alt="image" src="https://github.com/galihaulia9/Data-Analytics-Part-1/assets/125258524/8678655f-a223-4812-8933-1aa41a1b6b5d">

To find out which columns have Null (empty values), we must first look at the information from the data to be processed. From the table information above, it can be seen that there are columns that have null values, namely the power, fuel, gear, and version columns.

#### 2. Special Characters
Is done to remove unwanted special characters.

#### 3. Trimming Spaces
Is performed to remove unnecessary spaces in a column.

#### 4. Inconsistent Formatting
Is done to change the data to be consistent with its data type.

#### 5. Removing Duplicates
Is done to remove duplicate data.

#### 6. Imputing Data
Saves the cleaned data such as saved in (.csv) form.

## Validating Data
Validating data in data manipulation is a process of checking whether data has met certain criteria or rules before further analysis or processing. This is very important to ensure the accuracy and integrity of the data. Example :
- Checking Text Data Meets Minimum Length

![2](https://github.com/galihaulia9/Data-Analytics-Part-1/assets/125258524/78098b6d-e911-43e1-ad82-f5c20a8070ad)

The code above is used to check the number of characters of the column. If the length is less than 'min_length' then the row is considered not meeting the criteria.

<img width="424" alt="image" src="https://github.com/galihaulia9/Data-Analytics-Part-1/assets/125258524/8fb602b6-9915-4816-b9bb-061ba5a4d5a9">

The code above will generate a data frame 'valid_text_data' containing lines with text that meets the minimum expected length.

## Organize Data
Data organization (organizing data) is the process of putting data into groups and categories to make it easier to use so that it can be accessed, processed, and analyzed more quickly.

- Sorting : A process of reorganizing a collection of objects using certain rules. Sorting is also known as an algorithm to put a collection of data elements into a certain order based on one or more keys in each element.
- Filtering : The process of examining a data set to exclude, reorganize, or divide data according to certain criteria.
- Slicing : An operation used to access a portion of a sequence such as a string, list, or tuple. It allows you to select a subset of data from a larger sequence by specifying a start and end index.
- Transposing : An operation that changes the position of a row to a column and vice versa in a data or matrix. Transposing is often used in data manipulation especially in dataframes as provided by the Pandas library in Python.
- Appending : One of the most frequently used features in python arrays is the append function. This append function is useful for adding array values in the last order. This function is slightly different from the insert function, where the insert function can add array values at certain positions.
- Truncating : An operation in data manipulation used to remove some data from the beginning or end of a dataset. This is useful when you want to limit or cut the data in your dataset according to certain conditions.

## Aggregate Data
Aggregate Data is the process of combining and summarizing data from multiple sources to produce in-depth conclusions is known as data aggregation. The purpose of data aggregation is to facilitate the analysis and interpretation of large amounts of data.

- Grouping : Is a technique to separate data based on certain criteria by mapping data with groups. To do grouping, we use a method called groupby(). When doing grouping, there are several sequential processes such as splitting, applying and combining.
- Joining/merging : The process of combining two or more datasets based on certain keys or columns. This allows us to combine data from several different sources into one larger and more complete dataset.
- Summarizing : A way to summarize a document into a simpler form by taking the important points in the document.
- Pivoting : One of the widely used data visualization types and is the basic plot type in data visualization. This type of plot displays information in the form of a series of data points connected by straight line segments. It can be used on Datasets that have continuous values to see the movement of data over time.
