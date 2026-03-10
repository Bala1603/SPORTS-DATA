# SPORTS-DATA
I worked on a Sports Analytics dataset using Python and Pandas to perform data cleaning, transformation, and basic analysis.

First, I started with data cleaning.
I corrected inconsistent values such as gender spelling mistakes like ‘Mal’, ‘Mle’, ‘Femal’ and standardized them to Male and Female. I also removed extra spaces from columns like Coach_Name and Player_Name using string functions.

Then I handled missing values using different statistical techniques.
For example:

I filled Age with the mean value.

I replaced missing categorical values using mode.

Some missing player names were replaced with “Anonymous”.

Next, I removed invalid or unrealistic records to improve data quality. For example:

Removed rows where Match_Fee ≤ 0

Removed Feedback_Score outside 1–5

Replaced unrealistic Sponsorship_Amount (<0 or >1,000,000) with the median value.

After cleaning the data, I performed feature engineering by creating new columns such as:

Total_Earning = Match_Fee + Bonus + Sponsorship_Amount

Performance_Score = Score + Assists×2 + Goals×3 + Wickets×4

Age_Group categories like <20, 20–30, 31–45

I also performed data queries and analysis such as:

Finding top players by total earnings

Fetching players from India with more than 10 matches

Identifying players with low average ratings

Detecting the player with the highest single match score

Additionally, I standardized date formats and converted the Match_Date column to datetime for chronological analysis.

Finally, I ensured data integrity by checking duplicates and creating unique Player_ID values starting from 1001.

Through this project, I improved my skills in data cleaning, data transformation, feature engineering, and exploratory analysis using Pandas.
