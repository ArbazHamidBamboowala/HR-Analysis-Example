This project aims to analyze HR Data.
During this project I have performed various Operations using Power BI.
Including Extracting data from a source,
Performed Cleaning of Data,
Then I have performed transforming the data,
I analyzed it and performed a visualization.
Then I predicted the analysis using various charts in Power BI.
I have used DAX for various operations on data.

Here is the Detailed Explanation:

Step 1:
REQUIREMENT ANALYSIS
I started initially by understanding vendor or clients requirement.
I moved forward by understanding the given data I looked for Insights of data, Working preference of people, People working from home or working from office, Reason for working from home frequently
I also looked at the attendance keys given and understood what each key meant.
Then I looked over and realised the presence of people, If people are working from home what days they must be working that is Monday to Friday.
The people who were working from home had been given a laptop and they were permitted to work for two days which saved infrastructure cost.
I looked in for people who are taking sick leaves and the reason for those leaves.
Reasons for leaves also included Seasonal sick leaves such that client mentioned during a football match.

STEP 2:
Data Extraction:
I Extracted the data from sources such as Excel and it contained multiple sheets which was in xlsx format.

STEP 3:
Data Cleaning and Transformation:
I converted the source of data in csv format which was a requirement by client. Now I added the sheets into Power BI.
Now I started with cleaning data by performing transformation but I took one sheet first so that the rest can be automated using function.
I removed the unwanted rows, created a header column.
There was a need to convert the columns of attendance dates into rows as data looked unclean and was difficult to work on.
So I Transposed attendance dates from columns to rows in a way it shows all attendance dates for everyday of a particular employee.
As soon as transposition was done I removed all the necessary error values so there is no problems with the data.
I as well removed a few duplicate and null values to remove any gaps.

STEP 4: 
Data Analysis:
I rechecked and ensure that data is correct.
After ETL was performed I worked on how to create an analysis of data.
I used DAX function for creating percentage values.
DAX Function included operations such as:
Count of Total Working Days - Non Working Days to get Absent People
Work From Home Present Days
Sick Leave Percentage 

Then I added all the functions togeather onto the dashboard.

Conclusion:
My analysis revealed some noteworthy statistics for the months of April, May, and June 2022. In April, we observed an impressive 94% attendance rate, with 9.1% of employees working from home. May witnessed 89.7% attendance, along with 11.2% of individuals opting for remote work. June showcased a remarkable 91.5% attendance, with 9.5% of the workforce working from home.
My involvement in this project began with a thorough analysis of the client's requirements, ensuring a deep understanding of the provided data. To facilitate this, I engaged with stakeholders, posing relevant questions to gain valuable insights.
When it came to data management, I chose Power BI over Excel for its efficiency. Employing Power Query, I seamlessly imported and transformed the data, meticulously removing any errors. To further enhance data processing, I created a specialized function tailored to the original dataset. The dashboard itself was brought to life through the application of DAX functions, offering a comprehensive and visually appealing snapshot of the data.
Analyzing data has always been a passion of mine.

The ability to derive meaningful insights and translate them into actionable strategies is a valuable asset in today's data-driven landscape.
