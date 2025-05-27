

:arrow_left: [[**Back to ML Paths**](https://ua-datalab.github.io/mlpaths_grids/)]

# Self-Directed Learning Module: Python for Data Science 🐍🔬

<img src="https://images.unsplash.com/photo-1640875130844-ba6985dc0502?q=80&w=2069&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" width=840>

(Image Credit: [Trac Vu](https://unsplash.com/@tracminhvu). Unsplash.com)


***

This module focuses on mastering Python for the critical stages of the data science workflow that precede machine learning. You'll delve into data acquisition, cleaning, manipulation, analysis, and visualization using Python's powerful ecosystem. This experiential, self-paced program emphasizes hands-on learning and the integration of AI tools to support your development.

### 1. General Learning Objectives
Upon successful completion of this module, you will be able to:

1. **Remember** core Python syntax, data structures, and control flow relevant to data manipulation tasks. (Bloom's: Remember)
2. **Understand** the principles of data wrangling, cleaning, and the importance of data quality. (Bloom's: Understand)
3. **Understand** how to use NumPy for efficient numerical operations and array manipulations in data preparation. (Bloom's: Understand)
4. **Apply** Pandas library functions to effectively load, inspect, clean, transform, merge, and aggregate diverse datasets. (Bloom's: Apply)
5. **Apply** Matplotlib and Seaborn to create a variety of informative visualizations for exploratory data analysis and communicating findings. (Bloom's: Apply)
6. **Analyze** datasets to identify data quality issues, inconsistencies, and patterns through programmatic inspection and visualization. (Bloom's: Analyze)
7. **Analyze** and select appropriate Python techniques and tools for specific data manipulation and analysis challenges. (Bloom's: Analyze)

Throughout this module, you are encouraged to use open-source Large Language Models (LLMs) as a learning aid to clarify Pythonic practices, debug code, generate example snippets, and explore data handling strategies more deeply.

---

### 2. Topic Overview

Effective data science relies heavily on robust data preparation and exploration, stages where Python excels. This module immerses you in using Python for the entire pre-modeling pipeline: acquiring data from various sources, performing intensive cleaning and transformation, conducting thorough exploratory data analysis (EDA) to uncover insights, and creating compelling visualizations to communicate findings. We will focus on writing efficient, readable, and "Pythonic" code using libraries like Pandas, NumPy, Matplotlib, and Seaborn. Mastering these skills is fundamental for any data scientist, as the quality of data preparation directly impacts the success of any subsequent analytical or modeling efforts. This module specifically excludes machine learning algorithms to allow for a deeper dive into these foundational data handling capabilities.

---

### 3. Open-Source Python Libraries

These libraries are essential for data handling and analysis in Python:

* **Python Standard Library (selected modules):**
    * **Description:** Python's built-in modules provide foundational capabilities. `csv` for reading/writing CSV files, `json` for handling JSON data, `collections` for specialized data structures (e.g., `Counter`, `defaultdict`), and `datetime` for date/time manipulation are particularly relevant.
    * **Practical Applications:** Basic file I/O, parsing simple data formats, efficient counting, and managing temporal data without external dependencies.
* **NumPy (Numerical Python):**
    * **Description:** The cornerstone for numerical computing in Python. It introduces the powerful N-dimensional array (`ndarray`) object, enabling efficient vectorized operations, which are significantly faster than Python's native loops for numerical tasks.
    * **Practical Applications:** Performing complex mathematical calculations, statistical operations, linear algebra, random number generation, and serving as the underlying data structure for many other data science libraries like Pandas.
* **Pandas:**
    * **Description:** A high-performance, easy-to-use library providing versatile data structures (like DataFrame and Series) and a rich set of tools for data manipulation and analysis. It's designed for working with structured (tabular, relational) and time-series data.
    * **Practical Applications:** Data loading (from CSV, Excel, SQL, JSON, etc.), data cleaning (handling missing values, duplicates, outliers), data transformation (merging, joining, reshaping, pivoting, applying functions), filtering, grouping, and aggregation.
* **Matplotlib:**
    * **Description:** A foundational and widely used plotting library in Python that provides extensive control over all aspects of a figure. It can produce a vast array of static, animated, and interactive visualizations.
    * **Practical Applications:** Creating line charts, bar charts, histograms, scatter plots, pie charts, error bars, and more. Essential for detailed data exploration and producing publication-quality figures.
* **Seaborn:**
    * **Description:** Built on top of Matplotlib, Seaborn provides a higher-level interface for creating attractive and informative statistical graphics. It simplifies the creation of common complex visualizations.
    * **Practical Applications:** Generating statistical plots like distribution plots, categorical plots (box plots, violin plots), regression plots, heatmaps, and pair plots with concise syntax, often enhancing EDA.
* **Requests:**
    * **Description:** A simple yet elegant HTTP library for Python, making HTTP requests straightforward.
    * **Practical Applications:** Accessing web APIs to fetch data (e.g., JSON data from a REST API) for your data science projects.

---

### 4. Core Skills to Develop

Engaging with this module will help you develop these specific skills:

1. **Pythonic Data Manipulation:** Writing efficient, idiomatic Python code for complex data transformation and cleaning tasks.
2. **Advanced Data Wrangling:** Mastering techniques for handling missing data, transforming data types, merging datasets, and reshaping data structures using Pandas.
3. **In-depth Exploratory Data Analysis (EDA):** Systematically exploring datasets to uncover patterns, anomalies, and relationships using statistical summaries and diverse visualizations.
4. **Data Input/Output Expertise:** Confidently reading data from and writing data to various common file formats (CSV, JSON, Excel).
5. **AI-Assisted Python Development:** Utilizing LLMs to optimize Python code, understand library functionalities, and troubleshoot data-specific programming challenges.

---

### 5. Subtopics

This module is structured around five key subtopics, focusing on Python for data work before modeling:

1. **Pythonic Foundations for Data Work:** Revisiting essential Python data structures, functions, control flow, and list/dictionary comprehensions with a data-centric approach.
2. **Numerical Data Operations with NumPy:** In-depth array manipulation, broadcasting, vectorized computations, and statistical functions for data preparation.
3. **Comprehensive Data Acquisition & Cleaning with Pandas:** Advanced techniques for reading diverse data formats, identifying and handling missing/erroneous data, and data type conversions.
4. **Transforming and Reshaping Data with Pandas:** Mastering merging, joining, concatenating, pivoting, and applying custom functions to DataFrames.
5. **Exploratory Data Analysis and Visualization:** Deep dive into using Pandas, Matplotlib, and Seaborn for statistical exploration and creating insightful visualizations.

---

### 6. Experiential Use Cases

Remember to consult AI tools (like a locally run LLM or an online one) to help you understand error messages, suggest alternative Pythonic solutions, or explain library functions in more detail. For example: "Explain how Pandas `merge` differs from `concat` with examples," or "Show me a Pythonic way to apply a custom function to each row of a Pandas DataFrame."

#### Subtopic 1: Pythonic Foundations for Data Work

* **Use Case 1.1: Data Aggregation with Dictionaries and Lists**
    * **Problem Definition:** You have a list of sales transaction tuples `(product_id, quantity_sold, price_per_unit)`. You need to calculate the total revenue for each `product_id`.
    * **Learning Goal:** Write Python code using dictionaries to aggregate total revenue per product. Practice iterating through lists and updating dictionary values. (Bloom's: Apply)
    * **Python Tools:** Python lists, dictionaries, `for` loops, `if` statements.
* **Use Case 1.2: Filtering Complex Data with Comprehensions**
    * **Problem Definition:** Given a list of dictionaries, where each dictionary represents a student with keys like 'name', 'grade', and 'activities' (a list of strings), filter this list to get only students who are in 'grade' 10 and participate in 'chess club'.
    * **Learning Goal:** Implement this filtering logic using a list comprehension with nested conditions or chained comprehensions. (Bloom's: Apply, Analyze)
    * **Python Tools:** Python lists, dictionaries, list comprehensions.
* **Use Case 1.3: Writing a Reusable Data Processing Function**
    * **Problem Definition:** You frequently need to clean text data by converting it to lowercase, removing leading/trailing whitespace, and replacing multiple spaces with a single space.
    * **Learning Goal:** Create a Python function that takes a string as input and returns the cleaned string according to the specified rules. Include a docstring for your function. (Bloom's: Apply)
    * **Python Tools:** Python functions (`def`), string methods (`lower()`, `strip()`, `split()`, `join()`).

#### Subtopic 2: Numerical Data Operations with NumPy

* **Use Case 2.1: Creating and Inspecting NumPy Arrays**
    * **Problem Definition:** You need to represent a small table of numerical sensor readings (e.g., 5 readings for 3 different sensors) and perform basic inspections.
    * **Learning Goal:** Create a 2D NumPy array from a Python list of lists. Inspect its `shape`, `dtype`, `ndim`, and `size` attributes. (Bloom's: Apply)
    * **Python Tools:** NumPy (`np.array`, array attributes).
* **Use Case 2.2: Vectorized Arithmetic and Broadcasting**
    * **Problem Definition:** You have a NumPy array representing product prices in USD. You need to convert all prices to EUR using a fixed exchange rate and then add a flat shipping fee to each.
    * **Learning Goal:** Perform these calculations using vectorized operations (multiplication by exchange rate, addition of shipping fee) demonstrating NumPy's broadcasting. (Bloom's: Apply, Understand)
    * **Python Tools:** NumPy arrays, arithmetic operations.
* **Use Case 2.3: Conditional Selection and Modification with NumPy**
    * **Problem Definition:** Given a NumPy array of temperature readings, you need to identify all readings below a certain threshold (e.g., freezing point) and replace them with a specific value (e.g., the threshold itself, or NaN).
    * **Learning Goal:** Use boolean indexing to select elements that meet a condition and then modify these selected elements. (Bloom's: Apply, Analyze)
    * **Python Tools:** NumPy arrays, boolean indexing, `np.nan`.

#### Subtopic 3: Comprehensive Data Acquisition & Cleaning with Pandas

* **Use Case 3.1: Loading and Inspecting Diverse File Formats**
    * **Problem Definition:** You receive data from two sources: a CSV file containing product information and a JSON file containing customer reviews.
    * **Learning Goal:** Load the CSV data into one Pandas DataFrame and the JSON data into another. Perform initial inspection (`.head()`, `.info()`, `.describe()`) on both to understand their structure and data types. (Bloom's: Apply)
    * **Python Tools:** Pandas (`pd.read_csv()`, `pd.read_json()`).
* **Use Case 3.2: Advanced Missing Data Imputation**
    * **Problem Definition:** A dataset of employee information has missing values in 'Salary' (numerical) and 'Department' (categorical) columns.
    * **Learning Goal:** Implement different imputation strategies: fill missing 'Salary' values with the median salary of their respective 'JobLevel'. Fill missing 'Department' values using the mode or by forward/backward fill based on some criteria (e.g., if sorted by employee ID). Justify your choices. (Bloom's: Apply, Analyze)
    * **Python Tools:** Pandas (`.fillna()`, `.groupby()`, `.transform()`, `.median()`, `.mode()`, `ffill`, `bfill`).
* **Use Case 3.3: Identifying and Handling Duplicates and Inconsistent Text**
    * **Problem Definition:** A customer dataset has duplicate entries based on email address and inconsistent entries in a 'Country' column (e.g., "USA", "U.S.A.", "United States").
    * **Learning Goal:** Identify and remove duplicate rows, keeping the first occurrence. Standardize the 'Country' column to a consistent format (e.g., "USA"). (Bloom's: Apply, Analyze)
    * **Python Tools:** Pandas (`.duplicated()`, `.drop_duplicates()`, string methods, `.replace()` or `.map()`).

#### Subtopic 4: Transforming and Reshaping Data with Pandas

* **Use Case 4.1: Combining Datasets with Merging/Joining**
    * **Problem Definition:** You have two DataFrames: one with order details (`order_id`, `customer_id`, `product_id`) and another with customer details (`customer_id`, `customer_name`, `city`). You need to combine them to get customer names and cities for each order.
    * **Learning Goal:** Perform an appropriate merge (e.g., left merge) to combine these DataFrames based on `customer_id`. (Bloom's: Apply)
    * **Python Tools:** Pandas (`pd.merge()`).
* **Use Case 4.2: Reshaping Data with Pivot Tables**
    * **Problem Definition:** You have a "long" format DataFrame of sales data with columns `Date`, `ProductCategory`, `Region`, and `SalesAmount`. You need to transform it into a "wide" format where rows are `ProductCategory`, columns are `Region`, and cell values are total `SalesAmount`.
    * **Learning Goal:** Use Pandas `pivot_table()` to reshape the data, calculating the sum of sales for each category-region combination. (Bloom's: Apply, Understand)
    * **Python Tools:** Pandas (`.pivot_table()`).
* **Use Case 4.3: Applying Custom Functions for Complex Transformations**
    * **Problem Definition:** You have a DataFrame with a 'transaction_date' column (as strings) and a 'price' column. You need to extract the day of the week from the date and create a new column indicating if the price is 'High', 'Medium', or 'Low' based on custom quantile-based thresholds.
    * **Learning Goal:** Convert the 'transaction_date' to datetime objects. Write a custom function to categorize prices and apply it to the 'price' column using `.apply()` to create the new 'price_category' column. Extract the day of the week into a new column. (Bloom's: Apply, Analyze)
    * **Python Tools:** Pandas (`pd.to_datetime()`, `.dt.day_name()`, `.apply()`, custom Python functions, `.quantile()`).

#### Subtopic 5: Exploratory Data Analysis and Visualization

* **Use Case 5.1: Univariate Analysis - Distributions and Outliers**
    * **Problem Definition:** For a given numerical feature in your dataset (e.g., 'age' of customers, 'response_time' of a service), you need to understand its distribution, central tendency, and spread, and identify potential outliers.
    * **Learning Goal:** Calculate descriptive statistics (mean, median, std, min, max, quartiles) for the feature. Create a histogram and a box plot to visualize its distribution and identify outliers. (Bloom's: Apply, Analyze)
    * **Python Tools:** Pandas (`.describe()`), Matplotlib/Seaborn (`histplot`, `boxplot`).
* **Use Case 5.2: Bivariate Analysis - Relationships and Correlations**
    * **Problem Definition:** You want to investigate the relationship between two numerical variables (e.g., 'study_hours' and 'exam_score') and between a numerical and a categorical variable (e.g., 'income' across different 'education_levels').
    * **Learning Goal:** Create a scatter plot for the two numerical variables and calculate their correlation coefficient. Create grouped box plots or violin plots for the numerical vs. categorical variable. Interpret the findings. (Bloom's: Apply, Analyze)
    * **Python Tools:** Pandas (`.corr()`), Matplotlib/Seaborn (`scatterplot`, `boxplot`, `violinplot`).
* **Use Case 5.3: Creating a Multi-plot Dashboard for Insights**
    * **Problem Definition:** You need to present a consolidated view of several key aspects of a dataset to a stakeholder.
    * **Learning Goal:** Create a figure with multiple subplots (e.g., a 2x2 grid) using Matplotlib, where each subplot shows a different insightful visualization (e.g., a distribution, a relationship, a comparison across categories) from your dataset. Ensure plots are well-labeled and titled. (Bloom's: Apply, Analyze)
    * **Python Tools:** Matplotlib (`plt.subplots()`, `ax.set_title()`, etc.), Seaborn (can be used for individual plots within subplots).

---

### 7. Assessment Quiz

This quiz helps you self-assess your understanding. Verify answers by reviewing module content or quick experimentation.

1.  Which Python data structure is mutable and typically used for ordered sequences where elements can be changed?<br>
    a)  Tuple<br>
    b)  Set<br>
    c)  String<br>
    d)  List<br>
    *(Answer: d)*

2.  What is the primary advantage of using NumPy's vectorized operations over standard Python loops for numerical computations?<br>
    a)  They require less memory.<br>
    b)  They are significantly faster due to optimized C implementations.<br>
    c)  They can handle non-numeric data more easily.<br>
    d)  They automatically generate plots.<br>
    *(Answer: b)*

3.  In Pandas, if `df` is a DataFrame, what does `df.dropna(subset=['email'], inplace=True)` do?<br>
    a)  Drops rows where any column has a missing value.<br>
    b)  Drops rows where the 'email' column has a missing value, modifying `df` directly.<br>
    c)  Fills missing 'email' values with the mean.<br>
    d)  Drops the 'email' column itself.<br>
    *(Answer: b)*

4.  Which Pandas method is most suitable for combining two DataFrames based on the values in one or more common columns (similar to SQL joins)?<br>
    a)  `pd.concat()`<br>
    b)  `df.append()`<br>
    c)  `pd.merge()`<br>
    d)  `df.join()` (Note: `join` is often index-based or can use `on` for columns, but `merge` is more general for column-based joining)<br>
    *(Answer: c)*

5.  What does the Pandas `groupby()` method enable you to do?<br>
    a)  Sort the DataFrame by one or more columns.<br>
    b)  Split the DataFrame into groups based on some criteria, apply a function to each group independently, and then combine the results.<br>
    c)  Select a random sample of rows from the DataFrame.<br>
    d)  Reshape the DataFrame from long to wide format.<br>
    *(Answer: b)*

6.  Which Matplotlib/Seaborn plot is best for visualizing the distribution of a single continuous numerical variable and checking for skewness or modality?<br>
    a)  Scatter plot<br>
    b)  Bar chart<br>
    c)  Histogram or Kernel Density Estimate (KDE) plot<br>
    d)  Line chart<br>
    *(Answer: c)*

7.  If you have a Pandas DataFrame `sales_data` and want to find the average sales amount for each `product_category`, which code snippet is most appropriate?<br>
    a)  `sales_data.pivot_table(columns='product_category', values='sales_amount', aggfunc='mean')`<br>
    b)  `sales_data.groupby('product_category')['sales_amount'].mean()`<br>
    c)  `sales_data.describe()['sales_amount']`<br>
    d)  `sales_data['sales_amount'].apply(lambda x: x.mean() if x.name == 'product_category' else x)`<br>
    *(Answer: b)*

8.  You've written a Python script to process a large CSV. It's running much slower than expected. How could an LLM potentially help you optimize it (without directly accessing your system)?<br>
    a)  By remotely debugging your script on your machine.<br>
    b.  By explaining common Python performance bottlenecks, suggesting more efficient Pandas/NumPy functions for tasks you describe (e.g., replacing row-wise iteration with vectorized operations), or helping refactor a specific slow code snippet you provide.<br>
    c.  By rewriting the entire script in C++ for you.<br>
    d.  By telling you to buy a faster computer.<br>
    *(Answer: b)*

9.  What is the purpose of `df.info()` for a Pandas DataFrame `df`?<br>
    a)  To display the first 5 rows.<br>
    b)  To provide a summary of descriptive statistics.<br>
    c.  To show a concise summary including the index dtype and columns, non-null values, and memory usage.<br>
    d)  To check for duplicate rows.<br>
    *(Answer: c)*

10. Which Python library would you primarily use to fetch data from a public REST API that returns JSON?<br>
    a)  NumPy<br>
    b)  Pandas<br>
    c)  Requests (often combined with the `json` standard library module)<br>
    d)  Matplotlib<br>
    *(Answer: c)*

---

### 8. Bonus Challenge Problems

These challenges are designed to push your analytical and Python data handling skills further.

1. **Comprehensive Sales Data Analysis Pipeline** (Bloom's: Analyze, Evaluate)
    * **Problem:** Find a multi-file sales dataset (or generate a plausible one with an LLM, e.g., one file for transactions, one for product details, one for store locations). Your task is to create a full data pipeline in a Jupyter Notebook that:
        1.  Loads data from multiple sources.
        2.  Cleans each dataset thoroughly (handle missing values, correct data types, standardize text, remove duplicates).
        3.  Merges these datasets into a single analytical DataFrame.
        4.  Performs EDA: Generate at least five distinct and insightful visualizations (e.g., sales trends over time, top-selling products, sales by region, correlation between product price and quantity sold). For each visualization, write a brief interpretation.
        5.  Derive at least two new features that might be useful (e.g., profit margin if cost data is available/creatable, sales per square foot if store size is available/creatable, day of the week of sale).
        6.  Summarize your key findings and any data quality issues or limitations you encountered.
    * **Guidance:** Justify your cleaning and transformation choices. Use LLMs to brainstorm potential new features or to get ideas for impactful visualizations given the (actual or mock) data. Focus on clear, well-commented code and insightful interpretations.

2. **Time-Series Data Anomaly Detection and Smoothing** (Bloom's: Analyze, Evaluate)
    * **Problem:** Obtain a simple time-series dataset (e.g., daily stock prices for a single stock over a year, monthly temperature readings for a city). Your task is to:
        1.  Load and preprocess the time-series data (ensure dates are proper datetime objects, handle missing values using time-series appropriate methods like interpolation).
        2.  Visualize the raw time series.
        3.  Implement a simple method to detect potential anomalies or outliers (e.g., values exceeding a certain rolling standard deviation, or using interquartile range on differences). Clearly mark these on your plot.
        4.  Apply a smoothing technique (e.g., a simple moving average) to the time series and plot the smoothed series alongside the original.
        5.  Discuss the effect of the smoothing technique and the rationale for your anomaly detection method. What are the pros and cons of the methods you chose?
    * **Guidance:** Pandas has excellent time-series capabilities (e.g., `resample()`, `rolling()`). Use an LLM to understand different smoothing techniques or simple anomaly detection approaches suitable for time series data if you're unfamiliar. Focus on interpretation and justifying your choices.

---

### 9. References & Further Reading

(Focus on open-access or widely available resources)

1. **McKinney, W. (2022). *Python for Data Analysis* (3rd ed.). O'Reilly Media.**
    * Authored by the creator of Pandas, this is the definitive guide for data manipulation with Pandas, also covering NumPy and practical data analysis techniques.
2. **VanderPlas, J. (2016). *Python Data Science Handbook*. O'Reilly Media.**
    * Open-access online version: [https://jakevdp.github.io/PythonDataScienceHandbook/](https://jakevdp.github.io/PythonDataScienceHandbook/)
    * Excellent coverage of IPython, NumPy, Pandas, Matplotlib. Great for practical, hands-on learning.
3. **Pandas Official Documentation: User Guide & Tutorials.**
    * Open-access: [https://pandas.pydata.org/pandas-docs/stable/user_guide/index.html](https://pandas.pydata.org/pandas-docs/stable/user_guide/index.html)
    * The most authoritative and comprehensive resource for all Pandas functionalities.
4. **NumPy Official Documentation: User Guide.**
    * Open-access: [https://numpy.org/doc/stable/user/index.html](https://numpy.org/doc/stable/user/index.html)
    * Essential for understanding NumPy arrays and their operations in depth.
5. **Python Standard Library Documentation: `csv`, `json`, `collections`, `datetime`.**
    * Open-access: [https://docs.python.org/3/library/](https://docs.python.org/3/library/) (Navigate to specific modules)
    * Direct from the source, for understanding Python's built-in capabilities for data handling.

***

Created: 05/25/2025 (C. Lizárraga); Updated: 05/25/2025 (C. Lizárraga)


<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a3/Cc.logo.circle.svg/64px-Cc.logo.circle.svg.png" width=20> 2025. [University of Arizona DataLab](https://datascience.arizona.edu/education/uarizona-data-lab), [Data Science Institute](https://datascience.arizona.edu/)

