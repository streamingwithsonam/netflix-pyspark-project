
# Netflix Data Exploration with PySpark

This project is a beginner-friendly PySpark data analysis of a sample Netflix dataset. It focuses on exploring content type, genres, ratings, and movie durations using PySpark on Databricks.

## 📁 Dataset

- `netflix_titles_sample.csv`: A subset of the Netflix dataset containing titles, types (Movie/TV Show), genres, ratings, countries, and durations.

## 💻 Technologies Used

- Apache Spark (PySpark)
- Databricks Community Edition
- Python
- Spark SQL
- CSV file handling
- Basic regular expressions and data transformations

## 📊 Analysis Performed

1. **TV Shows vs Movies**  
   Counted the number of TV Shows and Movies using groupBy.

2. **Genre Breakdown**  
   Split multi-value genre column (`listed_in`), exploded them into separate rows, and counted the frequency of each genre.

3. **Ratings Distribution**  
   Grouped and counted content based on Netflix ratings like `TV-MA`, `PG-13`, etc.

4. **Movie Duration Analysis**  
   - Filtered out only Movie records.
   - Extracted numeric minutes from strings like "148 min".
   - Calculated the average duration of movies in minutes.

## 📂 Folder Structure

```
netflix-pyspark-project/
├── README.md
├── Netflix_Data_Exploration.ipynb
└── netflix_titles_sample.csv
```

## 🚀 How to Run

1. Create a free Databricks Community Edition account.
2. Upload the dataset to DBFS (under `/FileStore/tables/`).
3. Open the notebook in Databricks.
4. Attach a cluster and run cells sequentially.
5. Modify or expand the project as needed!

## 🙌 Credits

- Dataset: [Netflix Titles on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows) *(sampled)*
- Built with 💻 by [Your Name]

## 📌 Note

This project was done as a PySpark mini-project for learning and portfolio building. Ideal for beginners looking to practice Spark and data exploration.

