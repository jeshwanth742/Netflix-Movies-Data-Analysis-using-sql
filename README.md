
## Netflix Movies Data Analysis using sql
🚀 Netflix Movies Data Analysis: Unveiling Insights with SQL! 🎬

📊 Objective
We analyzed Netflix's movie dataset to uncover content trends, genre patterns, audience focus, and more using SQL queries.

📁 Data Exploration Highlights:
Movies based on Rating: Family, Kids, Adult
Peak Content Year: 2021 saw the highest releases.
Show with the longest duration in minutes: The Great British Baking Show(3600min)
Average Duration: Shows that have the longest runtime.

💡 SQL in Action
From data cleaning to advanced queries, we leveraged SQL to:
Identify content trends by year.
Classify titles based on ratings.
Create cumulative growth views and rank titles within countries.

🔍 Sample Query:
Top countries with maximum titles:
SELECT country, COUNT(*) AS title_count 
FROM netflix_titles 
GROUP BY country 
ORDER BY title_count DESC; 

💼 Future Scope
Our next steps include integrating user ratings for deeper insights and comparing content strategies across platforms.

📌 Takeaway
This analysis highlights SQL's power in turning raw data into meaningful insights. Stay tuned for more!
![image](https://github.com/user-attachments/assets/50753b42-8c00-48d1-bddd-eef2b64881fa)
https://drive.google.com/file/d/1UmVXwVvQr8EIFCpUXL4rzxKF8jfw4pIh/view?usp=classroom_web&authuser=0

