# metricsdao_univ3_usdc_bounty


### Installation

First make a virtual environment.

```
python -m venv .venv
source .venv/bin/activate
```
    
Then install the package.
```pip install git+https://github.com/Evan-Kim2028/subgraph-query-portal.git```

### Usage
1. Run the `pipeline.ipynb` notebook to query the Univ3 subgraphs and collect the data.
2. Run the `easy_ethereum_univ3_charts.ipynb` notebook to generate all the charts. Charts are saved in the charts folder.
3. Read the results in `easy_ethereum_univ3_report.ipynb` notebook. This serves as a final representation of the data collected and results.


The pipeline was created using `.ipynb` files to build the pipeline creation steps in a more ad-hoc manner. Although initial analysis is restricted to April 21st - April 28th 2023, the pipeline can be modified
with different dates to collect data from different time periods as well as different token pairs.
