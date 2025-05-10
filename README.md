Here are the simple and clear answers to your questions. I've grouped them for better readability:

---

### 🐼 **Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn**

1. **What is Pandas library in Python?**
   Pandas is a Python library used for data manipulation and analysis. It provides tools to handle structured data using DataFrames and Series.

2. **Key features of Pandas:**

   * Easy handling of missing data
   * Data alignment and integrated handling of time-series
   * Powerful grouping and aggregation
   * Reading/writing to CSV, Excel, etc.
   * Label-based slicing, indexing, and subsetting

3. **What is NumPy library in Python?**
   NumPy stands for Numerical Python. It provides support for large, multi-dimensional arrays and matrices and mathematical operations on them.

4. **What is matplotlib library?**
   Matplotlib is a Python library used to create static, animated, and interactive visualizations like line plots, bar charts, etc.

5. **Difference between seaborn and matplotlib:**
   Seaborn is built on top of Matplotlib. Seaborn provides prettier and more informative statistical graphics with less code.

6. **Is Sklearn and Scikit-learn the same?**
   Yes, `sklearn` is the import name for the `Scikit-learn` library. It's used for machine learning tasks like classification, regression, and clustering.

7. **Functions in Pandas and NumPy:**

   * Pandas: `read_csv()`, `head()`, `tail()`, `describe()`, `dropna()`, `fillna()`
   * NumPy: `array()`, `mean()`, `std()`, `reshape()`, `arange()`, `linspace()`

8. **What is DataFrame in Python?**
   A DataFrame is a 2D labeled data structure in Pandas, similar to a table in Excel or SQL.

9. **How to find duplicates in Python?**

   ```python
   df.duplicated()
   ```

10. **Use of `describe()` command:**
    It gives summary statistics like count, mean, std, min, max, and percentiles for numerical columns.

---

### 🤖 **Machine Learning & Evaluation Metrics**

11. **Naive Bayes classification algorithms in Python:**

    * GaussianNB
    * MultinomialNB
    * BernoulliNB (all in scikit-learn)

12. **Significance of Confusion Matrix:**
    It shows the performance of a classification model using TP, TN, FP, FN values.

13. **TP, TN, FP, FN in confusion matrix:**

    * TP: True Positive
    * TN: True Negative
    * FP: False Positive
    * FN: False Negative

14. **What is Recall?**
    Recall = TP / (TP + FN) — It tells how many actual positives were correctly identified.

15. **What is Precision?**
    Precision = TP / (TP + FP) — It tells how many predicted positives were actually correct.

16. **What is F1 Score?**
    F1 Score is the harmonic mean of precision and recall. It balances both.

---

### 📊 **Data Visualization**

17. **Need of Data Visualization in Data Science:**
    It helps to understand data easily, find patterns, and make decisions quickly using graphs and charts.

18. **What is Outlier?**
    An outlier is a data point that is very different from other points in the dataset.

19. **When to use histogram and pie chart:**

    * Histogram: For showing distribution of numerical data
    * Pie Chart: For showing proportions/percentages of categories

20. **Challenges in Big Data Visualization:**

    * Handling large volumes of data
    * Real-time data updates
    * Performance and clarity of graphs

21. **What is jointplot and distplot?**

    * `jointplot()`: Shows relationship between 2 variables with scatter and histogram
    * `distplot()`: Shows distribution of a single variable (now replaced by `displot()`)

22. **Tools used for data visualization:**

    * Matplotlib
    * Seaborn
    * Tableau
    * Power BI
    * Plotly

---

### 🧹 **Data Preprocessing**

23. **What is Data Wrangling?**
    Cleaning, structuring, and enriching raw data into a usable format.

24. **What is Data Transformation?**
    Converting data into another format or structure for analysis (e.g., normalization, scaling).

25. **Use of `StandardScaler()` in Python:**
    It standardizes data by removing the mean and scaling to unit variance.

---

### 🐘 **Big Data & Hadoop**

26. **What is Hadoop?**
    An open-source framework to store and process big data using a distributed computing system.

27. **What is HDFS and MapReduce?**

    * HDFS: Hadoop Distributed File System, used to store big data in blocks
    * MapReduce: Programming model for processing large datasets in parallel

28. **Components of Hadoop Ecosystem:**
    HDFS, MapReduce, YARN, Hive, Pig, HBase, Sqoop, Flume, Oozie, Spark, etc.

---

### ⚙️ **Scala & Big Data Tools**

29. **What is Scala?**
    Scala is a high-level programming language that combines object-oriented and functional programming. Used in Apache Spark.

30. **Features of Scala:**

    * Combines OOP and functional programming
    * Interoperable with Java
    * Concise syntax
    * Immutable collections

31. **How is Scala different from Java?**
    Scala is more concise, supports functional programming, and needs fewer lines of code than Java.

32. **Applications of Scala:**

    * Big Data (Apache Spark)
    * Web development
    * Data processing tools

---

### 📈 **Data Science & Statistics**

33. **What is Data Science?**
    A field that uses tools, algorithms, and machine learning to extract knowledge from data.

34. **What is Big Data?**
    Extremely large datasets that cannot be processed using traditional tools.

35. **Characteristics of Big Data:**

    * Volume
    * Velocity
    * Variety
    * Veracity
    * Value

36. **Phases of Data Science Life Cycle:**

    * Data Collection
    * Data Cleaning
    * Data Exploration
    * Model Building
    * Model Evaluation
    * Deployment

37. **What is Central Tendency?**
    It indicates the center of a data set (mean, median, mode).

38. **What is Dispersion?**
    It tells how spread out the data is (range, variance, standard deviation).

39. **Mean, Mode, Midrange, Median of:** `10,22,13,10,21,43,77,21,10`

    * Mean = (10+22+13+10+21+43+77+21+10)/9 = 25.22
    * Mode = 10 (appears 3 times)
    * Midrange = (min + max)/2 = (10 + 77)/2 = 43.5
    * Median = 21 (sorted middle value)

40. **What is Variance?**
    It measures how much data points vary from the mean.

41. **What is Standard Deviation?**
    Square root of variance. Shows the average distance from the mean.

---

### 🤖 **Naive Bayes & NLP**

42. **Posterior Probability (Naive Bayes):**
    The updated probability of a hypothesis after observing evidence.

43. **Likelihood Probability (Naive Bayes):**
    The probability of evidence given a hypothesis.

44. **How to deal with missing values?**

    * Drop missing values: `df.dropna()`
    * Fill missing values: `df.fillna(value)`

---

### 📚 **NLP (Natural Language Processing)**

45. **What is NLTK?**
    Natural Language Toolkit — a Python library for working with human language data (text).

46. **What is Tokenization?**
    Splitting text into words or sentences.

47. **What is Stemming?**
    Reducing words to their root form (e.g., “playing” → “play”).

48. **What is Lemmatization?**
    Similar to stemming but returns proper root words using vocabulary.

49. **What is Corpus in NLP?**
    A large collection of text data used for training NLP models.

---

### ⚡ **Apache Spark**

50. **What is Spark Framework?**
    Apache Spark is a fast, in-memory big data processing framework that supports batch and real-time analytics.

---

Would you like these in a downloadable PDF or organized into flashcards?
