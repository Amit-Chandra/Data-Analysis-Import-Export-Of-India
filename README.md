# India Trade Data Analysis

This project involves analyzing trade data for India using Python. The analysis includes visualizations of export and import data, trade balance, and total trade over financial years. Interactive plots are created using Plotly for a better understanding of the data.

## Project Overview

- **Data Source**: The data is fetched from a MySQL database containing trade data.(Taken from Kaggle)
- **Visualization**: Interactive plots are generated using Plotly, allowing users to filter data by specific financial years.
- **Key Visualizations**:
  - Export vs. Import
  - Trade Balance per Country
  - Total Trade over Financial Years
  - Export and Import over Financial Years
  - Trade Balance over Financial Years


![Import Export Over Financial Year](https://github.com/Amit-Chandra/Data-Analysis-Import-Export-Of-India/blob/main/import_export_over_financial_year.png)


## Setup Instructions

### Prerequisites

- Python 3.x
- MySQL Server

### Install Required Packages

To install the required packages, you can use pip. Create a virtual environment (optional but recommended) and then run:

```bash
pip install pandas sqlalchemy mysql-connector-python plotly
```

### Database Setup

Ensure that you have a MySQL database named `indiatradedata` with a table named `tradedata` containing the relevant columns. Modify the connection string in the script to match your database credentials.

### Running the Scripts

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Amit-Chandra/Data-Analysis-Import-Export-Of-India.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Data-Analysis-Import-Export-Of-India
   ```

3. Run the Python scripts to generate the visualizations:

   ```bash
   python import_export_data_of_india.ipynb
   ```


## Example Output

Here is an example of what the interactive visualizations will look like:

- **Export vs. Import**: Scatter plot comparing export and import values.
- **Trade Balance per Country**: Bar chart showing trade balance for each country.
- **Total Trade over Financial Years**: Line chart showing total trade over financial years.
- **Export and Import over Financial Years**: Line chart comparing export and import over financial years.
- **Trade Balance over Financial Years**: Line chart showing trade balance over financial years.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request. Ensure that your contributions adhere to the project's coding standards and include tests where applicable.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Data source: [https://www.kaggle.com/]
- Visualization library: [Plotly](https://plotly.com)

For any questions or issues, please open an issue on the GitHub repository or contact me directly.

---

Happy analyzing!

