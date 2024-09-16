# Zomato Data Analysis

This repository contains a project aimed at analyzing Zomato restaurant data to derive insights on restaurant types, ratings, votes, and more. The analysis is performed using **Python** with the help of libraries like **Pandas**, **Seaborn**, and **Matplotlib** for data manipulation and visualization.

## Project Overview

The project focuses on analyzing various aspects of the dataset, such as:

- **Restaurant types**
- **Distribution of votes**
- **Ratings distribution**
- **Cost for two people**
- **Influence of online orders on ratings**
  
## Dataset

The dataset used for this project includes information such as restaurant names, votes, ratings, cost for two people, whether the restaurant accepts online orders, and more.

### Key Features:
- `name`: Name of the restaurant
- `online_order`: Whether the restaurant accepts online orders (Yes/No)
- `book_table`: Whether the restaurant accepts table bookings (Yes/No)
- `rate`: Restaurant rating
- `votes`: Number of votes received
- `listed_in(type)`: Type of restaurant (e.g., delivery, dine-out, cafes)

## Analysis Performed

### 1. Rating Handling
- The `rate` column was processed to extract numeric ratings by splitting the values and converting them into floats.

### 2. Restaurant Type Distribution
- A count plot is generated to visualize the distribution of restaurant types using Seaborn’s `countplot()`.

### 3. Votes by Restaurant Type
- Grouped data by restaurant type and summed up votes to create a line plot of total votes for each type of restaurant.

### 4. Ratings Distribution
- A histogram is plotted to understand how ratings are distributed across restaurants.

### 5. Approximate Cost for Two People
- The distribution of restaurant costs is visualized using a count plot for better understanding.

### 6. Online Order and Ratings
- A box plot visualizes the relationship between online ordering availability and restaurant ratings.

### 7. Heatmap of Online Orders and Restaurant Types
- A pivot table is created, and a heatmap visualizes how many restaurants of each type accept online orders.

## Visualizations

The project makes use of several visualizations to explore and better understand the data:

- **Count Plot**: For the distribution of restaurant types.
- **Line Plot**: For total votes by restaurant type.
- **Histogram**: For ratings distribution.
- **Box Plot**: For online order vs rating analysis.
- **Heatmap**: For visualizing the relationship between restaurant types and online orders.

## Installation

To run the project, you'll need to install the required libraries:

```bash
pip install pandas seaborn matplotlib numpy
```

## How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/zomato-data-analysis.git
   ```

2. Navigate to the project directory:

   ```bash
   cd zomato-data-analysis
   ```

3. Open and run the Jupyter notebook or Python script that contains the analysis code.

## Conclusion

Through this project, we are able to draw insights regarding the types of restaurants on Zomato, how online orders influence ratings, and the cost distribution for two people. This project demonstrates how data analysis techniques can be applied to real-world data for making business decisions.
