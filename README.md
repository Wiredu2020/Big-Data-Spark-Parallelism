# Big Data Spark Parallelism

This repository contains a collection of educational notebooks, scripts, and utility
code focused on exploring big data concepts using Apache Spark, as well as
parallelism techniques in Python. It is designed for self-paced learning and
experimentation with real-world data processing workflows.

---

## 📂 Repository Structure

- `NOTEBOOKS/` – Main directory containing Jupyter notebooks and auxiliary
  Python/Java files.
  - `intro-to-parallelism-in-python.ipynb` – CPU-bound examples exploring
    multiprocessing, threading, and asynchronous programming in Python.
  - `intro-to-parallelism-in-python-io.py`, `intro-to-parallelism-in-python-cpu.py` –
    complementary Python scripts demonstrating I/O and CPU parallelism.
  - `hello-spark.ipynb`, `introducing-spark-APIs.ipynb`,
    `spark-structured-APIs.ipynb`, `spark-structured-APIs-updated.ipynb` –
    hands‑on Spark tutorials covering basic concepts, RDDs vs DataFrames, and
    structured APIs.
  - `RDDs-vs-DataFrames.ipynb`, `working-with-spark-dataframes.ipynb` –
    deeper dives into Spark data abstractions.
  - `functional-programming.ipynb` – A primer on functional programming
    techniques useful in big-data pipelines.
  - `intro-to-APIs.ipynb`, `intro-to-web-scraping.ipynb` – Tutorials showing
    how to consume REST APIs and scrape the web, often in parallel.
  - `ML-with-large-datasets.ipynb` – Machine learning workflows at scale using
    Spark and pandas.
  - `mob_data_utils.py` – A Python module with utility functions for processing
    mobile network data; contains both Spark-specific and vanilla Python
    helpers.
  - `WordCount.java` – Simple WordCount example implemented in Java for
    running on a Spark cluster.

> *The list above is not exhaustive; explore the notebooks to discover
> additional examples and exercises.*

---

## ⚙️ Prerequisites

To run the notebooks and scripts you will need:

1. **Python 3.8+** – preferably in a virtual environment (venv, conda, etc.)
2. **Jupyter Notebook / JupyterLab** – to launch and interact with the `.ipynb`
   files.
3. **Apache Spark** – a local installation or a cluster; `pyspark` must be
   available to Python.
4. **Python packages** – install via `pip` or `conda`:

```bash
pip install pandas numpy geopandas shapely plotly aiohttp requests
pip install pyspark
```

> See each notebook’s first cell for any additional dependencies.

---

## 🚀 Getting Started

1. Clone or download the repository to your local machine.
2. Set up and activate your Python environment.
3. Launch Jupyter Notebook/Lab inside the repository root:
   `jupyter notebook` or `jupyter lab`.
4. Open any notebook inside `NOTEBOOKS/` and execute the cells sequentially.
5. For standalone Python scripts, run them with `python path/to/script.py`.

> Example: `python NOTEBOOKS/intro-to-parallelism-in-python-io.py`.

---

## 💡 Tips & Notes

- Many of the notebooks are geared toward demonstration rather than production
  use. Feel free to modify code and datasets to explore new scenarios.
- The `mob_data_utils` module includes both vanilla Python functions (suffix
  `_va`) and Spark-aware versions (suffix `_sp`) for easy switching between
  local and distributed execution.
- `WordCount.java` is a classic Spark example; compile and submit it using
  `spark-submit` if you want to experiment with a JVM-based job.

---

## 📚 References

- [Apache Spark Documentation](https://spark.apache.org/docs/latest/)
- [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/)
- [Geopandas Documentation](https://geopandas.org/)

---

## 📝 License

This repository is provided for educational purposes. Feel free to adapt and
share the material under the terms of the [MIT License](LICENSE) or your own
preferred license.

---

Happy learning and experimenting with big data and parallelism!
