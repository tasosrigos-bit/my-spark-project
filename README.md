# my-spark-project

An Apache Spark assignment on a Q-Commerce retail dataset (1,000,000 transactions), for the Business Intelligence & Data Engineering course of my MSc in Business Analytics.

The notebook has two parts:

- **Spark SQL:** exploring the data and answering a set of business questions (descriptive statistics, filtering customers by payment method, age group and product, aggregations and window functions), with the dataframe cached in memory to speed up the repeated queries.
- **Spark ML:** building a pipeline (indexing and encoding the categorical features, assembling a feature vector) and running KMeans to cluster the customers.

Built with PySpark.

## Files

- `spark-assignment/f2822511-Rigos-Anastasios.ipynb` — the full notebook. All the outputs are saved, so you can read it without running Spark.
- `pyproject.toml` / `uv.lock` — the Python environment (managed with uv).
