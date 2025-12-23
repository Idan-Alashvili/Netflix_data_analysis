Netflix Content Analysis
Portfolio Data Analysis Project
Overview

This project presents a complete data analysis workflow based on raw Netflix content data.
It was created as part of a personal portfolio to demonstrate practical experience in data cleaning, SQL-based data modeling, and interactive visualization using Power BI.

The project follows an end-to-end approach, covering the full process from raw data preparation to insight-driven dashboards.

Dataset

The dataset consists of raw CSV files containing information about Netflix movies and TV shows, including:

Content type (Movie / TV Show)

Release year

Age rating

Genres

Directors

Cast members

Countries where the content is available

The raw data was denormalized and included multiple columns with multi-value fields.

Tools & Technologies

MySQL – data cleaning, normalization, and querying

Excel – initial inspection and preprocessing

Power BI – data modeling and dashboard creation

Data Preparation & SQL Modeling

The raw dataset was cleaned and prepared to support structured analysis:

Handling missing (NULL) values

Converting and standardizing data types, with emphasis on date fields

Transforming string-based numeric fields into integers

To enable relational analysis, multi-value fields were normalized into separate tables, including genres, directors, cast members, and countries.
Each table is linked using show_id, allowing accurate joins and improved analytical flexibility.

SQL was used to build these normalized tables and to prepare analysis-ready data for Power BI.

Power BI Dashboards
Dashboard 1 – Content Overview

Provides a high-level overview of the Netflix content library:

Content added over time

Distribution by age rating

Top 10 genres

Geographic distribution of available content

Dashboard 2 – Content-Level Analysis

An interactive dashboard focused on individual titles.
After selecting a specific movie or TV show, the dashboard displays:

Release year

Age rating

Short description

Genre(s)

Director(s)

Cast members

Countries where the content is available

Key Insights

Most Netflix content was added after 2016, indicating rapid platform growth.

The United States has the highest number of available titles.

International Movies are the most common genre in the dataset, highlighting Netflix’s global focus.

Repository Structure

data/ – raw and processed data files

sql/ – SQL scripts used for data normalization

visuals/ – screenshots of Power BI dashboards

powerbi/ – Power BI (.pbix) file

Notes

This project was created for portfolio and learning purposes and does not represent official Netflix data.
