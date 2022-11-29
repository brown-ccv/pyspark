# PySpark

## It Started with Apache Spark 

Apache Spark is an open-source, distributed processing system used for big data workloads. It utilizes in-memory caching, and optimized query execution for fast analytic queries against data of any size. It provides development APIs in Java, Scala, Python and R, and supports code reuse across multiple workloads—batch processing, interactive queries, real-time analytics, machine learning, and graph processing. 

![spark](assets/template_0.png)

## What is PySpark?

Apache Spark is written in Scala programming language. PySpark has been released in order to support the collaboration of Apache Spark and Python, it actually is a Python API for Spark. In addition, PySpark, helps you interface with Resilient Distributed Datasets (RDDs) in Apache Spark and Python programming language

![python + spark](assets/template_1.png)

### PySparkSQL
A PySpark library to apply SQL-like analysis on a huge amount of structured or semi-structured data. We can also use SQL queries with PySparkSQL.

### MLlib
MLlib is a wrapper over the PySpark and it is Spark’s machine learning (ML) library. This library uses the data parallelism technique to store and work with data. The machine-learning API provided by the MLlib library is quite easy to use. MLlib supports many machine-learning algorithms for classification, regression, clustering, collaborative filtering, dimensionality reduction, and underlying optimization primitives.

### GraphFrames
The GraphFrames is a purpose graph processing library that provides a set of APIs for performing graph analysis efficiently, using the PySpark core and PySparkSQL. It is optimized for fast distributed computing. 

Advantages of using PySpark: 
• Python is very easy to learn and implement. 
• It provides simple and comprehensive API. 
• With Python, the readability of code, maintenance, and familiarity is far better. 
• It features various options for data visualization, which is difficult using Scala or Java.  

## How to get started 

1. Download Anaconda. In case you are not aware Anaconda is the most used distribution platform for python & R programming languages in the data science & machine learning community as it simplifies the installation of packages like PySpark, pandas, NumPy, SciPy, and many more.

You can install anaconda following this [link](https://www.anaconda.com/products/distribution). 

OR 

Uing Brew

```
brew install --cask anaconda
```
2. Python 3.4+ is required for the latest version of PySpark, so make sure you have it installed before continuing. (Earlier Python versions will not work.)

```
python3 --version
```

```
sudo apt install python3-pip
```

3. Install Jupyter Notebook if you do not already have one. 

```
pip install notebook
```

4. Clone this directory and navigate to the base of this directory. 

5. Create an anaconda environment using environment.yaml file. 

```
conda env create -f environment.yml
conda activate pyspark-tutorial

```
6. Addinng pyspark-tutorial environment to jupyter notebook. 

```
python -m ipvkernel install --user --name=pvspark-tutorial

```

