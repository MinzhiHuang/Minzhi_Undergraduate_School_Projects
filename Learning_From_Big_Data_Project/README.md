# 🔧 Advanced Missing Data Imputation

**Course**: STAT 440 - Learning from Big Data  
**Achievement**: Ranked #1/28 in class for imputation accuracy  
**Skills**: Statistical Imputation, MICE, Data Engineering, R Programming  
**Tools**: R, Statistical Computing, Cross-validation, Data Visualization

## 🎯 Project Overview

This project focuses on developing sophisticated missing data imputation strategies for Canadian internet speed test data. The challenge involved handling complex missing patterns across multiple variables while maintaining data integrity and achieving high imputation accuracy.

## 🏆 Key Achievement

**Class Ranking**: Achieved #1 position out of 20 groups for highest imputation accuracy, demonstrating mastery of statistical imputation techniques.

## 📊 Dataset Description

The dataset contains internet speed test results from locations across Canada:

- **V01**: Average download speed (kbps)
- **V02**: Average upload speed (kbps)  
- **V03**: Average latency (ms)
- **V04**: Number of tests performed at same location
- **V05**: Device type (mobile, pc, laptop)
- **V06**: Year of test
- **V07-V09**: Geographic identifiers (Province, Census Division, Dissemination Area)
- **V10**: Rural/urban classification indicator
- **V11-V14**: Population and geographic classification variables

## 🛠️ Technical Implementation

### Imputation Strategy by Variable Type

#### Continuous Variables (V1-V5, V11)

- **Method**: MICE (Multiple Imputation by Chained Equations)
- **Rationale**: Preserves relationships between variables and uncertainty quantification
- **Implementation**: Used R's `mice` package with appropriate imputation models

#### Categorical Variables (V6, V7, V10)

- **Method**: Rule-based imputation using geographic hierarchy
- **Logic**: Check if previous/next values are identical, otherwise refer to geographic hierarchy
- **Validation**: Cross-referenced with V8/V9 for consistency

#### Geographic Variables (V8, V9, V12-V14)

- **Method**: Nearest filled value replacement
- **Rationale**: Geographic variables often have spatial autocorrelation
- **Implementation**: Custom function to find nearest non-missing values

### Validation Framework

- **Cross-validation**: Used validation set to measure imputation accuracy
- **Accuracy Metrics**: Calculated per-variable accuracy rates
- **Quality Assurance**: Ensured imputed values maintain data distribution properties

## 📈 Results & Performance

- **Overall Accuracy**: Achieved highest accuracy in class competition
- **Variable-specific Performance**: Optimized imputation for each variable type
- **Statistical Validity**: Maintained original data distributions and relationships
- **Computational Efficiency**: Efficient implementation handling large datasets

## 📁 Project Files

- `Final_R_Code.Rmd` - Main R Markdown file with complete imputation pipeline
- `Minzhi_R.Rmd` - Development and testing code
- `V16.R`, `V18.R` - Version iterations of the imputation approach
- Various imputation method folders containing different approaches tested

## 🔍 Key Insights

1. **Geographic Hierarchy**: Leveraging Canada's administrative hierarchy improved categorical imputation
2. **Variable-specific Approaches**: Different missing patterns required tailored imputation methods
3. **MICE Effectiveness**: Multiple imputation proved superior for continuous variables
4. **Rule-based Logic**: Custom rules outperformed generic imputation for geographic variables

## 📊 Methodology Highlights

- **Domain Knowledge Integration**: Used Canadian geographic structure for intelligent imputation
- **Statistical Rigor**: Applied proper validation techniques to ensure imputation quality
- **Iterative Refinement**: Multiple versions tested and refined for optimal performance
- **Comprehensive Documentation**: Detailed methodology documentation for reproducibility

## 🎯 Business Impact

- **Data Quality**: Enabled analysis of previously unusable incomplete datasets
- **Statistical Validity**: Maintained data integrity for downstream analysis
- **Scalability**: Methodology applicable to similar geographic datasets
- **Research Value**: Contributed to understanding of missing data patterns in geographic data

---
