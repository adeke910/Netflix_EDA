# Netflix_EDA
 Netflix is one of the most popular media and video streaming platforms. They have over 8000 movies or tv shows available on their platform, 
 as of mid-2021, they have over 200M Subscribers globally. This tabular dataset consists of listings of all the movies and tv shows available on Netflix,
 along with details such as - cast, directors, ratings, release year, duration, etc
 
 ## Python libraries used:
- Numpy
- Pandas
- Seaborn
- Matplotlib
### Visualisations
- **Bar Plots:** Classical bar plots that are good for visualisation and comparison of different data statistics, especially comparing statistics of feature variables.
### Pandas Data Science

#### Basic Dataset Information
- **Read in a CSV dataset:** `pd.DataFrame.from_csv("csv_file")` OR `pd.read_csv("csv_file")`
- **Basic dataset feature info:** `fake_job_df.info()`
- **Basic dataset statistics:** `fake_job_df.describe()` 

#### Basic Data Handling
- **Drop missing data:** `df.dropna(axis=0, how='any')` Return object with labels on given axis omitted where alternately any or all of the data are missing
- **Replace missing data:** `df.replace(to_replace=None, value=None)` Replace values given in "to_replace" with "value".
- **Check for NANs:** `pd.isnull(object)` Detect missing values (NaN in numeric arrays, None/NaN in object arrays)
- **Get first "n" rows:** `df.head([n])`
