# as1466_week9

This project explores cloud-hosted notebook. The project connects to the dataset in the repository, performs data manipulation in Google Colab Notebook and copies this notebook to github. 
You can access the colab notebook via the link [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nastiiasaenko/as1466_week9/blob/main/as1466_week9.ipynb)

### Setup and configuration steps
1. Open Google Colab
2. Start a new Google Colab Notebook
3. From here you can start coding in Python

#### Connecting dataset to Colab
1. Read CSV file from this repository via the raw github link

```
import pandas as pd
path = r"https://raw.githubusercontent.com/nogibjj/as1466_week9/main/life%20expectancy%202.csv"
df = pd.read_csv(path)
```
2. Perform data analysis and visualization. The code in the [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nastiiasaenko/as1466_week9/blob/main/as1466_week9.ipynb) provides codes for
   * correlation matrix:
 ![jj](https://github.com/Nastiiasaenko/as1466_week9/blob/84a81425c87d4c28ee5eb113cd7ed54ccd745518/corr%20(2).png)
   * scatter plot segmented by region
   * boxplot segmeneted by region/year
  
All data manipulation provided can be found in the colab notebook, and its [local github repository copy](https://github.com/Nastiiasaenko/as1466_week9/blob/main/as1466_week9.ipynb). 

#### Copy Notebook to Github repo
After finishing the colab notebook: 
1. Navigate to file > "Save a copy to Github"
2. Authorize Github Connection
3. Choose the repository and branch
4. Save to Github by clicking "OK" 
  
   
