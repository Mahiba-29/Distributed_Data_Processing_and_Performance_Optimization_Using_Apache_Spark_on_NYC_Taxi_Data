# Distributed_Data_Processing_and_Performance_Optimization_Using_Apache_Spark_on_NYC_Taxi_Data
This project demonstrates distributed data processing using Apache Spark on a large-scale real-world dataset. I used the NYC Taxi public dataset and executed analytical queries using Spark’s distributed execution model. Performance was improved using partitioning, caching, and columnar storage formats.


**Dataset Overview :**

- Dataset Name: NYC Yellow Taxi Trip Data
- Source: New York City Taxi & Limousine Commission (TLC) – Public Open Data
- Data Format: Parquet (columnar storage format)
- Nature of Data: Real-world, large-scale transportation data
- Type: Structured dataset

<img width="491" height="161" alt="image" src="https://github.com/user-attachments/assets/4cc6d923-39e9-40bd-9d4b-198d8322d362" />

This dataset contains detailed trip-level information for taxi rides taken in New York City, including pickup/drop-off times, trip distance, fare amount, payment type, and vendor details. The dataset is widely used in Big Data analytics and distributed computing experiments because of its large size and real-world relevance.

**Architecture :**

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/68469e15-0ddb-470c-ae4e-201c5630291a" />


**Performance Optimization Techniques :**

1. Columnar Storage (Parquet)
    - Reduces I/O operations
    - Enables predicate pushdown

2. Repartitioning
    - Distributes data evenly across executors
    - Improves parallelism

3. Caching
    - Stores frequently accessed data in memory
    - Reduces recomputation

4. Shuffle Optimization
    - Reduces unnecessary data movement between nodes
    - These optimizations significantly reduce execution time.
  

**VISUALIZATION**

**Visualization 1: Trips Per Vendor (Bar Chart) :**
This visualization shows vendor-wise trip distribution computed using Spark’s distributed groupBy operation.

**Visualization 2: Average Fare by Passenger Count :** 
How fare changes with number of passengers.

**Visualization 3: Peak Hour Traffic :**
This helps identify peak traffic hours in New York City.

**Visualization 4: Fare Distribution (Histogram) :**
Sampling is used to efficiently visualize large datasets without memory overload.

**Visualization 5: Trip Distance vs Fare (Scatter Plot) :**
shows Relationship between distance and fare.

