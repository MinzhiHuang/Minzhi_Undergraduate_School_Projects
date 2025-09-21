# 🎯 Dimension Reduction & Outlier Detection

**Course**: STAT 341/641 - Dimension Reduction  
**Skills**: Unsupervised Learning, Statistical Computing, Isolation Forest Algorithm  
**Tools**: R, Statistical Computing, Algorithm Implementation

## 🎯 Project Overview

This project implements the isolation forest algorithm for dimension reduction and outlier detection in high-dimensional data. The focus is on understanding how isolation forest principles can be adapted for dimension reduction while maintaining outlier detection capabilities.

## 🧠 Algorithm Foundation

The isolation forest algorithm separates points through recursive partitioning:

1. **Random Variable Selection**: Choose one of the variables in the dataset
2. **Random Split Point**: Select a random value within the variable's range
3. **Binary Partitioning**: Divide data based on the split condition
4. **Recursive Process**: Repeat until isolation is achieved

## 🛠️ Technical Implementation

### Data Generation

- **Multi-dimensional Data**: Created 6-dimensional synthetic dataset with known cluster structure
- **Cluster Design**:
  - Cluster 1: 25 observations from normal distribution (mean = 1 in all dimensions)
  - Cluster 2: 35 observations with structured covariance matrix
  - Cluster 3: 18 observations with different mean vector
  - Cluster 4: 10 uniform random points
  - Cluster 5: 5 Cauchy-distributed outliers

### Isolation Forest Implementation

- **Dimension Reduction**: Adapted isolation forest for reducing dimensionality
- **Outlier Detection**: Maintained ability to identify anomalous points
- **Statistical Validation**: Compared results against ground truth cluster labels

### Key Code Components

- **Data Simulation**: Generated synthetic data with known structure
- **Algorithm Implementation**: Built isolation forest from scratch
- **Performance Evaluation**: Validated against known cluster assignments
- **Statistical Analysis**: Applied proper statistical tests for validation

## 📊 Results & Analysis

- **Outlier Identification**: Successfully identified Cauchy-distributed outliers
- **Cluster Separation**: Demonstrated effectiveness in separating normal from anomalous observations
- **Dimension Reduction**: Showed how isolation principles apply to dimensionality reduction
- **Statistical Validation**: Confirmed algorithm performance against ground truth

## 📁 Project Files

- `Final_student_version_not_filled.Rmd` - Original assignment template
- `Final_student_version_filled.Rmd` - Completed implementation
- `cluster_outlier_set.csv` - Dataset with cluster and outlier labels

## 🔍 Key Learning Outcomes

1. **Algorithm Understanding**: Deep comprehension of isolation forest mechanics
2. **Statistical Computing**: Proficiency in R for statistical algorithm implementation
3. **Dimension Reduction**: Understanding of unsupervised learning principles
4. **Outlier Detection**: Mastery of anomaly detection techniques

## 📈 Technical Highlights

- **Custom Implementation**: Built isolation forest algorithm from first principles
- **Statistical Rigor**: Applied proper validation methods for unsupervised learning
- **Code Quality**: Clean, well-documented R implementation
- **Educational Value**: Clear demonstration of algorithm mechanics

## 🎯 Applications

- **Anomaly Detection**: Identifying unusual patterns in high-dimensional data
- **Data Preprocessing**: Removing outliers before downstream analysis
- **Quality Control**: Detecting anomalies in manufacturing or process data
- **Security**: Identifying suspicious activities in network or transaction data
