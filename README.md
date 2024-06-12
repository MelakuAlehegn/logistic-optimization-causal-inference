# Logistic Optimization with Causal Inference

This project focuses on optimizing delivery driver locations using logistic optimization techniques and causal inference. The objective is to analyze historical delivery data and apply causal inference methods to improve delivery efficiency and effectiveness.

## Table of Contents

- [Project Description](#project-description)
- [Dataset](#dataset)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Causal Inference](#causal-inference)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Description

The project involves two main tasks:

1. Exploratory Data Analysis (EDA) to understand the dataset and identify key features.
2. Application of causal inference techniques to optimize the locations of delivery drivers.

## Dataset

The project uses two CSV files:

- `deliveries.csv`: Contains historical delivery data.
- `drivers.csv`: Contains information about delivery drivers.

## Exploratory Data Analysis (EDA)

During the EDA phase, we explore the dataset to identify patterns, correlations, and insights that can help in the optimization process. Key steps in the EDA include:

- Data cleaning and preprocessing.
- Visualizing distributions and relationships between variables.
- Identifying key features for optimization.

## Causal Inference

The causal inference phase aims to determine the causal relationships between different variables and their impact on delivery efficiency. This involves:

- Applying causal inference methods to the dataset.
- Identifying key factors that influence delivery times and efficiency.
- Using these insights to recommend optimal locations for delivery drivers.

## Setup

To set up the project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/MelakuAlehegn/logistic-optimization-causal-inference.git
   cd logistic-optimization-causal-inference
   ```

2. Create a virtual environment and activate it:

```bash
python3 -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

To run the EDA and causal inference analysis, follow these steps:

1. Ensure the CSV files are in the project directory.
2. Run the Jupyter Notebook or Python scripts provided for EDA and causal inference

```bash
jupyter notebook eda_anlysis.ipynb
# or
python causal_inference.py
```

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please create a pull request or open an issue.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
