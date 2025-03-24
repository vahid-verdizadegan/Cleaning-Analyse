# Chart Drawing Script

## Introduction

This project provides a Python script that processes data and generates various charts. It is ideal for data analysis and visualization.

## Features

- Reads data from CSV or Excel files
- Cleans and processes the data
- Generates line, bar, pie, and scatter plots
- Saves charts as image files (PNG or JPG)

## Requirements

To run this script, you need:

- Python 3.x
- The following libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn

Install the libraries using the following command:

```bash
pip install pandas numpy matplotlib seaborn
```

## Usage

1. Prepare your data in a CSV or Excel file.
2. Run the script:

```bash
python plot_script.py data.csv
```

3. Charts will be saved in the `output/` folder.

## Example

Suppose you have a file named `data.csv` with the following columns:

```
Date, Sales, Profit
2025-03-01, 5000, 1200
2025-03-02, 6000, 1500
```

After running the script, a line chart displaying Sales and Profit will be generated.

![Example Chart](example_chart.png)

## Contribution

If you have suggestions for improvements or want to report bugs, please submit a Pull Request or create a new Issue.

## License

This project is licensed under the MIT License. For more details, see the `LICENSE` file.

