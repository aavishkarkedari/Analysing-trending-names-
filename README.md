# Name Trend Analysis

Welcome to the Name Trend Analysis project! This repository contains code and instructions for analyzing trends in baby names using popular baby name data provided by the Social Security Administration (SSA) of the United States.

## Problem Statement

The objective of this project is to analyze trends in baby names from a dataset in zipped format. Specifically, we aim to:

1. Extract the dataset programmatically.
2. Visualize the number of male and female babies born in a particular year.
3. Identify and analyze popular baby names.

This project not only focuses on implementing data manipulation and data visualization using the pandas library but also tests your ability to solve real-world problem statements.

## Dataset

The dataset used for this analysis is the "Popular baby names" data provided by the SSA of the United States. You can download the dataset from the SSA website using the following steps:

1. Visit the SSA Baby Names Data page: [SSA Baby Names Data](https://www.ssa.gov/oact/babynames/limits.html).

2. Click on 'National data'.

3. Download the zipped file containing the dataset.

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/name-trend-analysis.git
   ```

2. Extract the dataset from the zipped file you downloaded from the SSA website. Place the extracted CSV files in the project's `data/` directory.

3. Install the required Python packages if you haven't already. You can use `pip` to install them:

   ```bash
   pip install -r requirements.txt
   ```

## Analysis Process

Here's a high-level overview of the analysis process, along with helpful hints:

1. **Data Extraction**:
   - Use Python libraries such as pandas, zipfile, and BytesIO to programmatically extract the data.
   - Find a way to extract only files that consist of useful data.
   - You can use the following code as a hint to read the CSV files:

   ```python
   pd.read_csv(BytesIO(z.read(file_name)), encoding='utf-8', engine='python', header=None)
   ```

2. **Visualize Births by Gender and Year**:
   - Utilize pandas to create visualizations of the number of male and female babies born in a particular year.
   - You can use the `DataFrame.plot` method to create plots.

3. **Identify Popular Baby Names**:
   - Analyze baby names by sorting out all birth counts.
   - Analyze baby names by sorting out the top 100 birth counts.
   - Group the names to find out the most popular baby names.

## Project Structure

The project directory structure is as follows:

- `data/`: Directory to store the dataset files (CSVs).
- `name_trend_analysis.ipynb`: Jupyter Notebook containing the analysis code.
- `requirements.txt`: A list of required Python packages for the project.
- `README.md`: This README file with project information and instructions.

## Contributing

If you'd like to contribute to this project, please follow these guidelines:

1. Fork this repository.

2. Create a new branch for your feature or bug fix:

   ```bash
   git checkout -b feature/your-feature
   ```

3. Make your changes and commit them with clear commit messages.

4. Push your changes to your fork:

   ```bash
   git push origin feature/your-feature
   ```

5. Create a pull request to merge your changes into the main repository.


Feel free to explore, analyze, and contribute to this exciting project! Happy name trend analysis!
