Springboard Data Science Career Track
Section 5.2: Working with Data in Files

Assignment: JSON Data Wrangling Mini Project

Goals: 
    -Practice working with the JSON format using a real life data set
    -Extract and manipulate data in JSON
    -Practice data wrangling skills


Reference: http://pandas.pydata.org/pandas-docs/stable/io.html#io-json-reader

Data source: http://jsonstudio.com/resources/


Approach: 
    1. Import JSON file into a DataFrame
    2. Utilize aggregates to generate a list of the 10 countries with the most projects  (top 10).
        a. Assuming "top 10" is 10 highest scoring
        b. Assuming "top 10" is 10 highest scores with repeatable ranks
    3. Find the top 10 major project themes via mjtheme_namecode.
        a. Read column in as JSON file into DataFrame 
        b. Normalize Data
    4. Get top 10 major themes using aggregates
    5. Investigate "missing" values
        a. Fill in missing values utilizing information derived from project code 
    6. Recalculate top 10 major themes
    7. Investigate skew due to duplicate project codes within project ID's
        a. Remove duplicate project codes within a project ID
        b. Generate 'corrected' dataset
    8. Recalculate the top 10 major themes
    9. Compare results of steps 6/8 and determine differences, if any. 
    
    