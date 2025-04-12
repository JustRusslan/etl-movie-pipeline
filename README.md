# 🎬 ETL Movie Pipeline

This project demonstrates a simple **ETL (Extract, Transform, Load) pipeline** using `pandas` and `SQLite`, based on a dataset of movie metadata.

We:
- Extract data from `movies.csv`
- Transform the data into normalized tables (`movies`, `genres`, `movie_genres`)
- Load it into a relational SQLite database

## 📁 Project Structure

- `movies.csv` – source dataset  
- `etl_movie_pipeline.ipynb` – Jupyter Notebook with all ETL steps  
- `movies_etl.db` – SQLite database file generated from the notebook

## 🧱 Tables

| Table Name     | Description                     |
|----------------|---------------------------------|
| `movies`       | Contains movie id, title, year  |
| `genres`       | Contains genre id and name      |
| `connection`   | Maps movies to their genres     |

## 🧪 How to Run

1. Open `etl_movie_pipeline.ipynb`
2. Run all cells in order
3. Resulting database will be saved as `movies_etl.db`

## 📦 Dependencies

- pandas
- sqlite3 (built-in)

## 📜 License

MIT
