# Machine Learning on Clothing Dataset

For this project, we will be applying machine learning models (both regression and classification) to a dataset containing information about various individuals, their clothing, and its properties along with other atmospheric elements such as temperature, pressure, humidity, etc. The users also provided feedback on if they feel cold or not. The feedback (through AMV and PMV) is based on the following mapping:

| Sensation | PMV | AMV |
|-----------|-----|-----|
| Warm      | +3  | 3   |
| Slightly warm | +2 | 2 |
| Neutral | 0 | 1 |
| Slightly cold | -2 | -1 |
| Cold | -3 | 0 |

The dataset is given in an Excel file named `CollectedData.xlsx`, see sheet 2 of the Excel file. The dimension names (column headers) are not mentioned in the given file. The table below describes the columns which will be of your interest.

| Column number | Feature Name | Feature Description |
|:-------------:|:------------:|:-------------------:|
| 3             | Age          | Age                 |
| 22            | Clo          | Clothing insulation |
| 19            | Met          | Met Rate            |
| 26            | Dewpt        | Dewpt               |
| 27            | PlaneRadTemp | Plane radiant temperature |
| 37            | Ta           | Average air temperature |
| 38            | Tmrt         | Average mean radiant temperature |
| 40            | Vel          | Air Velocity        |
| 42            | AirTurb      | Air Turbulance      |
| 43            | Pa           | Vapor Pressure      |
| 44            | Rh           | Humidity            |
| 74            | TaOutdoor    | Outdoor Air Temperature |
| 77            | RhOutdoor    | Outdoor Humidity    |
| 8             | AMV          | Classification response variable |
| 49            | PMV          | Regression response variable |

## Part A. Preprocessing
1. In this step, you are required to apply the preprocessing steps that you’ve covered in the course. Specifically, for each of the input dimension, fill in the following (add rows and complete the table for all input dimensions).

| Dim Name | Data Type | Total Instances | Number of Nulls | Number of Outliers | Min. Value | Max Value | Mode | Mean | Median | Variance | ST D |
|:--------:|:---------:|:---------------:|:--------------:|:-----------------:|:----------:|:---------:|:----:|:----:|:------:|:--------:|:----:|
| Age      |           |                 |                |                   |            |           |      |      |        |          |      |
| ...      |           |                 |                |                   |            |           |      |      |        |          |      |
| PMV      |           |                 |                |                   |            |           |      |      |        |          |      |

2. For each of the input dimension, plot histogram and comment on the type of distribution the dimension exhibits. Further, visualize each dimension using a Box Plot. Specifically, for each of the input dimension, you’re required to fill the following table (duplicate it for each of the 15 dimensions).

| Dim Name | Histogram | Box Plot | Comments |
|:--------:|:---------:|:-------:|:--------:|
| Age      |           |         |          |
| ...      |           |         |          |
| PMV      |           |         |          |

3. Find
