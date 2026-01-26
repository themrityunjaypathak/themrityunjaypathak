<strong>

<div align="center">

<a href="https://github.com/themrityunjaypathak" title="Mrityunjay's GitHub"><img src="https://github.com/user-attachments/assets/5e63170b-439e-452e-bf2c-efd78bb4455c"></a>

</div>

<div align="right">

<a href='mailto:themrityunjaypathak@gmail.com' title='Email'>
<img src='https://github.com/user-attachments/assets/ba588b5a-ed89-4c08-8f4d-da39538cf464' height="33px" align="center"></a>
&nbsp;
<a href='https://drive.google.com/file/d/1YT8LPk5UlwdnV5xH1st-Pl2OEf-mfE6m/view?usp=sharing' title='Resume'>
<img src='https://github.com/user-attachments/assets/f7f11e22-5a3c-4eca-a7db-b4886d276164' height="33px" align="center"></a>

</div>

## About

Hello! My name is Mrityunjay Pathak.

I'm a data scientist who enjoys building real-world, end-to-end systems.

I love creating projects that don't just stay in notebooks, but are deployed online where people can actually use them.

Projects I've worked on :

- AutoIQ : Used Car Pricing System
  - Built an end-to-end car price prediction system with FastAPI and Docker, trained on 2,800+ records scraped from Cars24.
  - Deployed an interactive HTML/CSS/JS application on GitHub Pages that fetches real-time predictions via the API.
  - Tech Stack : Python, Pandas, BeautifulSoup, Selenium, Scikit-learn, FastAPI, Docker, Git
- Dashly : Live Sales Dashboard
  - Designed a live Power BI dashboard connected to a Neon PostgreSQL database, containing 50,000+ sales records.
  - Automated an ETL pipeline with GitHub Actions to keep the dashboard updated with real-time insights.
  - Tech Stack : Python, Pandas, SQLAlchemy, PostgreSQL, Power BI, GitHub Actions, Git
- Pickify : Movie Recommender System
  - Developed a content-based movie recommender system using metadata from 5,000+ movies.
  - Integrated the TMDB API to fetch and display movie posters dynamically, for a personalized user experience.
  - Tech Stack : Python, Pandas, Scikit-learn, NLTK, Streamlit, TMDB API, Git 

Tools I've worked with :

- Programming Language : Python, SQL
- Libraries : NumPy, Pandas, Matplotlib, Seaborn, Plotly
- Machine Learning : Scikit-learn
- Database : MySQL, PostgreSQL
- BI Tool : Power BI, Excel
- Web Framework : FastAPI
- Containerization : Docker
- Version Control : Git
- Automation : GitHub Actions
- Shell Scripting : Bash

I'm currently seeking opportunities as a Junior Data Scientist or Junior Machine Learning Engineer.

If you're looking for someone who's eager to learn, collaborate, and build real-world solutions, I'd love to connect.

## Get in Touch

[Kaggle](https://www.kaggle.com/themrityunjaypathak)&nbsp;&nbsp;✦&nbsp;&nbsp;[LinkedIn](https://www.linkedin.com/in/themrityunjaypathak)&nbsp;&nbsp;✦&nbsp;&nbsp;[GitHub](https://github.com/themrityunjaypathak)&nbsp;&nbsp;✦&nbsp;&nbsp;[Medium](https://medium.com/@themrityunjaypathak)&nbsp;&nbsp;✦&nbsp;&nbsp;[Portfolio](https://themrityunjaypathak.github.io/)

## Projects

### AutoIQ : Used Car Pricing System 
<a href="https://github.com/themrityunjaypathak/AutoIQ"><img src="https://github.com/user-attachments/assets/92d6ca72-44fa-4874-8495-f07811dddd60" title="GitHub" width="80px"></a>&nbsp;&nbsp;<a href="https://themrityunjaypathak.github.io/AutoIQ/"><img src="https://github.com/user-attachments/assets/5876b6a4-9ab2-48aa-90d3-70117399aff3" title="Application" width="80px"></a>&nbsp;&nbsp;<a href="https://autoiq.onrender.com/docs"><img src="https://github.com/user-attachments/assets/453026e0-6b16-4b24-af29-415de2bc6bf8" title="Swagger UI" width="80px"></a>

➔ Problem
- In the used car market, buyers and sellers often struggle to determine a fair price for their vehicles.
- This project aims to provide an accurate and transparent pricing for used cars by analyzing real-world data.

➔ Solution
- Built and deployed an end-to-end machine learning pipeline to predict used car prices from real-world data.
- Collected and cleaned 2,800+ used car records from Cars24 using Selenium and BeautifulSoup.
- Optimized dataset memory usage by 90% through downcasting data types and converting to Parquet format.
- Trained models with Scikit-learn Pipelines & ColumnTransformer to avoid data leakage.
- Deployed the machine learning model as an API using FastAPI on Render.
- Built an HTML/CSS/JS application hosted on GitHub Pages to interact with the API and display predictions in real-time.
- Containerized the entire application using Docker and pushed to Docker Hub for reproducibility.

➔ Impact
- Achieved a 30% lower MAE and a 12% higher R2 score compared to the baseline regression model.
- Reduced prediction error variance by 70%, ensuring more stable and reliable predictions.

➔ Result
- Helps car owners quickly find the right selling price for their vehicles based on real-world data.
- Makes it easier for buyers to know if a car is fairly priced before making a purchase.

<hr>

### Dashly : Live Sales Dashboard
<a href="https://github.com/themrityunjaypathak/Dashly"><img src="https://github.com/user-attachments/assets/92d6ca72-44fa-4874-8495-f07811dddd60" title="GitHub" width="80px"></a>&nbsp;&nbsp;<a href="https://app.powerbi.com/view?r=eyJrIjoiZTgxODBhYmMtYjc1Zi00YjVkLWIyZDItZDYxY2RjZmIwNGY5IiwidCI6ImZhYjAyYzVkLTYxYjYtNGIxMi05ZTY2LTdhMDhkOWY0ZmNjMSJ9&pageName=5b9aaf645951a59cacdc"><img src="https://github.com/user-attachments/assets/97f1694b-8595-40cd-a234-308f143613d4" title="Dashboard" width="80px"></a>

➔ Problem
- Quick Buy is a leading superstore operating across the United States.
- It manages thousands of product transactions daily across multiple regions.
- The store's operations relied on manual spreadsheets and SQL queries to track business performance.
- As a result, decision-making was slowed down and made it harder to identify growth opportunities.

➔ Solution
- Designed a fully automated ETL pipeline using Python, SQLAlchemy and GitHub Actions for seamless daily data updates.
- Built custom Python ETL scripts to extract, transform and load over 50,000+ sales records into a Neon PostgreSQL database.
- Automated daily data generation (~100 new transactions daily) to simulate real-time sales activity.
- Integrated Power BI directly with the database, enabling real-time auto-refreshing dashboard without manual updates.

➔ Key Insights
- Standard Class accounts for ~60% of sales (~₹5.1M) and profit (~₹897K), making it the most profitable shipping mode.
- Consumer Segment generates ~50% of revenue (~₹4.26M) and profit (~₹757K), highlighting it as the primary customer base.
- Q4 (Oct–Dec) contributes ~27% of annual revenue, indicating strong seasonal demand, ideal for marketing and promotions.
- Paper, Binders and Phones are the top-performing sub-categories, together making up ~45% of total revenue.
- West and East regions dominate the market with ~58% of total sales, while South region with ~19% shows growth potential.
- Top 5 States (CA, NY, TX, PA, OH) contribute ~54% of sales, with CA alone driving ~21%, showing strong regional concentration.

➔ Impact
- Improved daily data update time from hours to under a minute (average ~45 sec) using GitHub Actions.
- Reduced reporting time by 80% through automation, delivering updated insights in under a minute.
- Delivered a reliable, low-latency, fully automated data pipeline with zero manual intervention.
- Achieved 100% workflow reliability, with zero pipeline failures since deployment (as recorded in GitHub Actions).

<hr>

### Pickify : Movie Recommender System
<a href="https://github.com/themrityunjaypathak/Pickify"><img src="https://github.com/user-attachments/assets/92d6ca72-44fa-4874-8495-f07811dddd60" title="GitHub" width="80px"></a>&nbsp;&nbsp;<a href="https://pickify.streamlit.app/"><img src="https://github.com/user-attachments/assets/5876b6a4-9ab2-48aa-90d3-70117399aff3" title="Application" width="80px"></a>

➔ Problem
- With the rise of streaming services, viewers now have access to thousands of movies across platforms.
- As a result, many viewers spend more time browsing than actually watching.
- This problem can lead to frustration, lower satisfaction and reduced watch time on the platform.
- Ultimately, this impacts both user experience and business performance.

➔ Solution
- Built a content-based movie recommender system trained on 5,000+ movie metadata records.
- Generated the top 5 similar titles for any selected movie in under 3 seconds.
- Integrated the TMDB API to dynamically fetch and display movie posters, enhancing user experience.
- Deployed the system as a Streamlit web app, used by 100+ users to discover personalized movie suggestions.

➔ Impact
- Reduces the time users spend choosing what to watch.
- Increases user engagement, watch time and satisfaction.
- Helps retain users by offering more personalized recommendations.

<hr>

### Netflix Data Analysis
<a href="https://github.com/themrityunjaypathak/Netflix-Data-Analysis"><img src="https://github.com/user-attachments/assets/92d6ca72-44fa-4874-8495-f07811dddd60" title="GitHub" width="80px"></a>&nbsp;&nbsp;<a href="https://www.kaggle.com/code/themrityunjaypathak/netflix-data-analysis"><img src="https://github.com/user-attachments/assets/7b33292b-2a68-4af3-ae25-281105385f8d" title="Notebook" width="80px"></a>

➔ Problem
- To analyze Netflix content data, uncovering valuable insights into how the platform evolves over time.

➔ Key Findings
- Cleaned and analyzed a dataset of 8,000+ Netflix Movies and TV Shows.
- More than 60% of the content on Netflix is rated for mature audiences.
  - Suggests that Netflix targets adult viewers to boost engagement and retention.
- More than 25% of the Movies and TV Shows were released on the 1st day of the month.
  - Shows a consistent release schedule, likely aligned with subscription renewal cycles.
- More than 40% of the content on Netflix is exclusive to the United States.
  - Shows a strong focus on U.S. market and content availability by location.
- More than 20% of the content on Netflix falls under the "Drama" genre.
  - Confirms that "Drama" is a key part of Netflix's content library.
- More than 23% of the content on Netflix was released in 2019 alone.
  - Indicates a major content push that year, possibly tied to growth or user acquisition efforts.

<hr>

### Supermarket Sales Analysis
<a href="https://github.com/themrityunjaypathak/Supermarket-Sales-Analysis"><img src="https://github.com/user-attachments/assets/92d6ca72-44fa-4874-8495-f07811dddd60" title="GitHub" width="80px"></a>&nbsp;&nbsp;<a href="https://www.kaggle.com/code/themrityunjaypathak/supermarket-sales-analysis"><img src="https://github.com/user-attachments/assets/7b33292b-2a68-4af3-ae25-281105385f8d" title="Notebook" width="80px"></a>

➔ Problem
- To analyze Supermarket Sales data, identifying key factors for improving profitability and operational efficiency.

➔ Key Findings
- Analyzed purchasing patterns of 9,000+ customers of a Supermarket.
- More than 15% of the products sold were Snacks.
  - Shows that Snacks are a convenient choice and a major source of revenue.
- More than 32% of total sales came from the West region of the supermarket.
  - Suggests that West region is a strong-performing area as compared to others.
- Health and Soft drinks were the most profitable sub-categories in beverages.
  - Shows that both type of drink options perform well among customers.
- November was the most profitable month contributing about 15% of the total annual profits.
  - Makes it an ideal time for running promotions and special offers.

## Certificates

<div>

<a href="https://www.hackerrank.com/certificates/e41a7578cc82" title="HackerRank Python (Basic)"><img src="https://github.com/user-attachments/assets/a06b46c9-6ff8-41d7-a035-c4f02d624422" width="175px" align="center"/></a> &nbsp;&nbsp; <a href="https://www.hackerrank.com/certificates/09ec62ca442f" title="HackerRank SQL (Basic)"><img src="https://github.com/user-attachments/assets/b49b401f-bcc4-4574-9fe9-e79052e324dc" width="175px" align="center"/></a>

</div>

## Blogs

<a href="https://medium.com/@themrityunjaypathak/simple-linear-regression-an-overview-8bfe6614ede8" title="Simple Linear Regression"><img src="https://github.com/user-attachments/assets/b1f48a17-20bd-463c-85cd-3974dcde19e0" width="175px" align="center"/></a> &nbsp;&nbsp; <a href="https://medium.com/@themrityunjaypathak/multiple-linear-regression-an-overview-5d0283d31f3f" title="Multiple Linear Regression"><img src="https://github.com/user-attachments/assets/ba744e94-ee35-4074-a7d7-3e50a81fa31f" width="175px" align="center"/></a>

<div align="right">
 
<a href="#" title="Scroll To Top"><img src="https://github.com/user-attachments/assets/d659b889-7e76-4fb3-a55a-3a14abb4df5a" width="35px"></a>

</div>

<a href='#'><img src='https://github.com/user-attachments/assets/e841a7d6-c1cb-49da-8922-5436987cc4d1'></a>

</strong>
