# Data

All data files belong in the `data/` folder. It can be helpful in larger projects to preserve your datasets at different points in the cleaning and transformation process, to enable easier re-use. One suggested folder structure is:

### 0_raw

The source datasets, preserved exactly as you got them. Whether you downloaded a file or used an API to extract the data, save your unmodified source datasets here.

### 1_cleaned

The cleaned and slightly modified version of your source datasets. These should be 1:1 with your sources, and the data in these files are clean, trimmed to only the data you need to use, columns renamed, etc.

### 2_transformed

These datasets contain data from multiple sources, and have been aggregated or otherwise significantly transformed. Statistical analysis, machine learning, or prepping for visualization happens here.

### 3_final

The final presentation-ready datasets. These contain the data you want to share (for example, with results from your analyses) and may be included in any dashboards or visualizations you produce.

## Alternative option: use a database

While you should still preserve your source data in its original format, you may not want to output the cleaned/transformed data to files of their own. Instead, you can preserve them as tables in a database file. The database file can have schemas that mimic the folder structure (raw, cleaned, transformed, final), and what would have been your file names become your table names. If you choose this option, I would suggest using [DuckDB](https://duckdb.org).