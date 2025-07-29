# 📦 CassandraProject

This project demonstrates how to model data using **Apache Cassandra**, a distributed NoSQL database, for analyzing user activity on a fictional music app called **Sparkify**.

---

## 🎯 Project Goal

Sparkify wants to analyze user listening behavior on their app. However, the raw data exists in CSV logs and is not structured for easy querying. The goal of this project is to:
- Build a denormalized data model using Apache Cassandra
- Design tables to answer specific queries
- Implement a basic ETL pipeline in Python to insert the data into Cassandra
- Run SELECT queries to retrieve insights

---

## 🧱 Technologies Used
- Apache Cassandra
- Python 3
- Pandas
- Jupyter Notebooks

---

## 📁 Project Structure

CassandraProject/
├── event_data/ # Raw CSV event logs
├── event_datafile_new.csv # Flattened, cleaned CSV file
├── etl.ipynb # Main notebook with ETL + queries
├── README.md # This file

---

## 🧪 How to Run the Project

1. **Start Cassandra**  
   Make sure your Cassandra server is running (e.g. via Docker or local install).

2. **Open the notebook**  
   Use Jupyter Notebook to open `etl.ipynb`.

3. **Run cells**  
   - The first section processes raw CSVs.
   - The second section creates tables and inserts data.
   - The final section runs SELECT queries to verify the model.

---

## ❓ Example Query Goalss

These are the business questions this project aims to answer:
1. What is the song, artist, and length for a particular session and item?
2. What songs were listened to by a specific user?
3. What users listened to a particular song?

---

## ✍️ Author

**Rahaf Mohammed**  
[GitHub Profile](https://github.com/RahafMohoammed)

---

## 📜 License

This project is open source and free to use under the MIT License.
