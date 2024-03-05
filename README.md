
# Project Title: What Drives the Price of a Car?

This repository contains an analysis of what Drives the Price of a Car. The project aims to understand what factors make a car more or less expensive and provide clear recommendations to a used car dealership as to what consumers value in a used car.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction: 

The scenarios revolve around understand what factors make a car more or less expensive (i.e. year, manufacturer,	model,	condition,	cylinders,	etc.)	


### Overview

The objective is to use the standard process in industry for data projects called CRISP-DM to complete the study of the car prices

### Data

In this application, we will explore a dataset from kaggle. The original dataset contained information on 3 million used cars. The provided dataset contains information on 426K cars to ensure speed of processing. The main features are:
'id', 'region', 'price', 'year', 'manufacturer', 'model', 'condition','cylinders', 'fuel', 'odometer', 'title_status', 'transmission', 'VIN','drive', 'size', 'type', 'paint_color', 'state']


### Deliverables
The final report highlights the findings of an in-depth analysis aimed at understanding consumer preferences in the used car market. Through statistical modeling and permutation importance analysis, we have identified key vehicle features that significantly influence consumer choices. These insights will assist in optimizing inventory selection, marketing strategies, and customer satisfaction, ultimately leading to increased sales and profitability for your dealership.

The analysis involves statistical summaries, visualizations, and Python code to explore the dataset. The findings will be shared in a public GitHub repository as a portfolio piece.


### Used Car Dealership Inventory Optimization Report

#### Executive Summary

This report presents the findings of an in-depth analysis aimed at understanding consumer preferences in the used car market. Through statistical modeling and permutation importance analysis, we have identified key vehicle features that significantly influence consumer choices. These insights will assist in optimizing inventory selection, marketing strategies, and customer satisfaction, ultimately leading to increased sales and profitability for your dealership.

#### Introduction

In a competitive used car market, understanding what consumers value in a vehicle is crucial for inventory management and sales strategy. Our analysis utilized a comprehensive dataset and applied machine learning techniques to discern patterns and preferences in consumer behavior.

#### Methodology

We employed Ridge Regression with Polynomial Features to model the relationship between various car features and consumer preferences. A critical aspect of our analysis was the application of permutation importance, which helped identify the features that consumers value most when selecting a used car.

#### Key Findings

Our analysis revealed several key features that significantly impact consumer choices in the used car market:

1. **Model of the Car**: This is the most valued feature, indicating consumers' preference for specific brands or models known for their quality, reliability, or status. Below the most famous models:

   
2. **Year of Manufacture**: Newer models are preferred, likely due to the latest technology, safety features, and style, along with the perceived lower risk of mechanical issues. This key with time serie analysis we did before shows the price trend values increase steadily over time.

3. **Four-Wheel Drive (4WD)**: The presence of 4WD is a significant factor, suggesting that consumers value the performance, safety, and capability it provides, especially in adverse weather conditions or for off-road use. Below is the distribution of the 4WD from our data:


4. **Odometer Reading**: Lower mileage vehicles are preferred, as they are associated with better condition, longer lifespan, and fewer potential mechanical problems.

5. **Drive Type**: The preference varies, indicating the importance of offering a diverse inventory that includes different drive types to meet varied consumer needs. Below is the drive type distribution for the top manufacturers:


#### Recommendations

Based on our findings, we recommend the following strategies to optimize your used car inventory:

- **Prioritize Popular Models**: Focus on acquiring models with high demand and a solid reputation to attract more customers.

- **Highlight Newer Models**: Emphasize vehicles from recent years in your inventory and marketing efforts, appealing to consumers looking for the latest features and lower mileage.

- **Promote Vehicles with 4WD**: Especially in regions with challenging weather, highlighting the availability of 4WD vehicles can be a key selling point.

- **Showcase Low Mileage Vehicles**: Make low mileage a prominent feature in the marketing of relevant vehicles, capitalizing on consumer association of lower mileage with higher value.

- **Maintain a Diverse Inventory**: Offer a variety of drive types to cater to different consumer preferences regarding performance, safety, and fuel efficiency.



### Conclusion
Our analysis provides a data-driven foundation for adjusting your inventory and marketing strategies to align with consumer preferences. By focusing on the key features valued by consumers, your dealership can enhance customer satisfaction, increase sales, and gain a competitive edge in the used car market.




## Features

As follow the list of the main features/functionalities of our study:

- ### Problem Presentation:
  Includes: reading the data, Investigatation the dataset for missing or problematic data, Decidng what to do about your missing data (drop, replace, other etc.),
  study all the features and it's relation to the price
- ### Modeling:
   Includes: using different model to characterize the data (linear, Ridge, polynomial, lasso etc) and find the best model that fit the data and the most inmportant features that affect the price of a car
- ### Conclusion and reporting
provide a key features that affacts the price of car and provide detailed report of our studay  


## Installation

To use Price_of_car_study, follow these steps:

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/ahachani/Price_of_car_study.git
    
    ```

2. **Navigate to the Project Directory:**
    ```bash
    cd Price_of_car_study

## Usage

Once you have installed Price_of_car_study, here's how you can use it:

1. **Import Price_of_car_study:**
    First, import Price_of_car_study into your Python script or Jupyter Notebook:
    ```python
    from Price_of_car_study import Price_of_car_study
    ```

2. **Initialize Price_of_car_study:**
    Create an instance of Price_of_car_study:
    ```python
    Price_of_car_study_instance = Price_of_car_study()
    ```

3. **Perform Operations:**
    Use the methods provided by Price_of_car_study to perform various operations. 

4. **Customize as Needed:**
    Explore additional functionalities and parameters available in Price_of_car_study to suit your specific use case. 

5. **Interpret Results:**
    After performing operations, interpret the results and use them according to your project requirements.

6. **Further Steps:**
    Continue refining your workflow and utilizing Price_of_car_study's features as needed for your data processing and machine learning tasks.


## Contributing

We welcome contributions from the community to improve Price_of_car_study. To contribute, please follow these steps:

1. **Fork the Repository:**
    Fork the Price_of_car_study repository to your GitHub account by clicking on the 'Fork' button at the top right of the repository page.

2. **Clone the Forked Repository:**
    Clone your forked repository to your local machine:
    ```bash
    git clone https://github.com/your-username/Price_of_car_study.git
    ```

3. **Create a Branch:**
    Create a new branch to work on your changes:
    ```bash
    git checkout -b feature-branch
    ```

4. **Make Changes:**
    Make the necessary changes, improvements, or additions to the codebase.

5. **Commit Changes:**
    Commit your changes with descriptive commit messages:
    ```bash
    git add .
    git commit -m "Add feature XYZ"
    ```

6. **Push Changes:**
    Push your changes to your forked repository:
    ```bash
    git push origin feature-branch
    ```

7. **Create a Pull Request:**
    Go to the GitHub repository and create a Pull Request (PR) from your forked repository.
    - Describe the changes made and their purpose clearly in the PR description.
    - Mention any related issues if applicable.

8. **Review and Collaborate:**
    Participate in discussions related to your PR and make necessary changes based on feedback received.

9. **Continuous Integration (CI) Checks:**
    Ensure that your changes pass any automated tests or CI checks set up for the repository.

10. **Merge Pull Request:**
    Once your PR is reviewed and approved, it will be merged into the main repository.

Thank you for contributing to Price_of_car_study!

## License

Price_of_car_study is licensed under the MIT License.

---

MIT License

Copyright (c) [2023] [Adel Hachani]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


