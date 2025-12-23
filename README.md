<h1>Netflix Content Analysis</h1>
<h3>Portfolio Data Analysis Project</h3>

<h2>Overview</h2>
<p>
This project presents a complete data analysis workflow based on raw Netflix content data.
It was created as part of a personal portfolio to demonstrate practical experience in data cleaning,
SQL-based data modeling, and interactive visualization using Power BI.
</p>
<p>
The project follows an end-to-end approach, covering the full process from raw data preparation
to insight-driven dashboards.
</p>

<h2>Dataset</h2>
<p>
The dataset consists of raw CSV files containing information about Netflix movies and TV shows, including:
</p>
<ul>
  <li>Content type (Movie / TV Show)</li>
  <li>Release year</li>
  <li>Age rating</li>
  <li>Genres</li>
  <li>Directors</li>
  <li>Cast members</li>
  <li>Countries where the content is available</li>
</ul>
<p>
The raw data was denormalized and included multiple columns with multi-value fields.
</p>

<h2>Tools &amp; Technologies</h2>
<ul>
  <li><strong>MySQL</strong> – data cleaning, normalization, and querying</li>
  <li><strong>Excel</strong> – initial inspection and preprocessing</li>
  <li><strong>Power BI</strong> – data modeling and dashboard creation</li>
</ul>

<h2>Data Preparation &amp; SQL Modeling</h2>
<p>
The raw dataset was cleaned and prepared to support structured analysis:
</p>
<ul>
  <li>Handling missing (NULL) values</li>
  <li>Converting and standardizing data types, with emphasis on date fields</li>
  <li>Transforming string-based numeric fields into integers</li>
</ul>
<p>
To enable relational analysis, multi-value fields were normalized into separate tables,
including genres, directors, cast members, and countries.
Each table is linked using <code>show_id</code>, allowing accurate joins and improved analytical flexibility.
</p>
<p>
SQL was used to build these normalized tables and to prepare analysis-ready data for Power BI.
</p>

<h2>Power BI Dashboards</h2>

<h3>Dashboard 1 – Content Overview</h3>
<ul>
  <li>Content added over time</li>
  <li>Distribution by age rating</li>
  <li>Top 10 genres</li>
  <li>Geographic distribution of available content</li>
</ul>

<h3>Dashboard 2 – Content-Level Analysis</h3>
<p>
An interactive dashboard focused on individual titles.
After selecting a specific movie or TV show, the dashboard displays:
</p>
<ul>
  <li>Release year</li>
  <li>Age rating</li>
  <li>Short description</li>
  <li>Genre(s)</li>
  <li>Director(s)</li>
  <li>Cast members</li>
  <li>Countries where the content is available</li>
</ul>

<h2>Key Insights</h2>
<ul>
  <li>Most Netflix content was added <strong>after 2016</strong>, indicating rapid platform growth.</li>
  <li>The <strong>United States</strong> has the highest number of available titles.</li>
  <li><strong>International Movies</strong> are the most common genre in the dataset.</li>
</ul>

<h2>Repository Structure</h2>
<ul>
  <li><code>data/</code> – raw and processed data files</li>
  <li><code>sql/</code> – SQL scripts used for data normalization</li>
  <li><code>visuals/</code> – screenshots of Power BI dashboards</li>
  <li><code>powerbi/</code> – Power BI (.pbix) file</li>
</ul>

<h2>Notes</h2>
<p>
This project was created for portfolio and learning purposes and does not represent official Netflix data.
</p>
