# House Price Analysis

This project analyzes house price data for St. Albans, focusing on trends over time and other insights using combined data from the Land Registry, Energy Performance Certificates and Ordinance Survey. The repository includes two Jupyter notebooks, the first containing data loading and processing to create the combined data set including multiple features for each sold property. The second notebook includes analysis and visualization steps, including visualising different regions of St Albans, depending on both their location and their *added-value*, that is, whether they are above or below the price expected for their total floor area in the St Albans area. These added-value regions have then been used in Random Forest Regression models, and significantly improved predictions

This project has created some nice interactive folium maps - none of which are displayed in GitHub. Therefore, I've included static images (and a PDF version). 


## Project Structure
- **St_Albans_house_prices_dataframe.ipynb**: Notebook to create a combined dataset
- **St_Albans_house_prices_analysis.ipynb**: Main Notebook to analyse the dataset

## Setup Instructions
1. Clone the repository: `git clone https://github.com/JamesSuter/House_price_analysis.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Open the notebook and run cells in order.

## Requirements
- Python 3.x
- Libraries: pandas, matplotlib, seaborn, geopandas, folium, sklearn, xgboost
  
## Data Sources
Due to licensing restrictions, the dataset used in this analysis is not included in the repository. However, you can access the data directly from the following links after agreeing to their usage terms.

Sold house prices: https://landregistry.data.gov.uk/
Energy Performance Certificates: https://epc.opendatacommunities.org/files/
Ordinance Survey: https://osdatahub.os.uk/downloads/open/OpenUPRN


## License
[MIT License](LICENSE)
