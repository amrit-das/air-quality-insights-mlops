# Air Quality Insights MLOps

This project aims to provide insights into air quality using machine learning operations (MLOps). The dataset used for this analysis is located in the `dataset/` directory, and the documentation can be found in the `docs/` directory.

## Project Structure

- `dataset/`: Contains the air quality dataset used for analysis.
- `docs/`: Contains documentation related to the project.
- `src/`: Contains the source code for data processing, model training, and evaluation.
- `notebooks/`: Contains Jupyter notebooks for exploratory data analysis and model experimentation.
- `models/`: Contains saved models and related artifacts.
- `scripts/`: Contains utility scripts for data preprocessing and other tasks.

## Getting Started

### Prerequisites

- Python 3.8 or higher
- Required Python packages (listed in `requirements.txt`)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/amrit-das/air-quality-insights-mlops.git
    cd air-quality-insights-mlops
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

### Usage

1. Preprocess the data:
    ```sh
    python scripts/preprocess_data.py
    ```

2. Train the model:
    ```sh
    python src/train_model.py
    ```

3. Evaluate the model:
    ```sh
    python src/evaluate_model.py
    ```

### Documentation

For detailed documentation, please refer to the `docs/` directory.

## Acknowledgements

- Data source: [UCI air-quality dataset](https://archive.ics.uci.edu/dataset/360/air%20quality)
- Contributors: [amrit-das]
