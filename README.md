
# DBpedia Association Analysis

## Description

This notebook performs association analysis on DBpedia data by extracting entities of type `dbo:Person` using SPARQL queries. The associated properties of these entities are analyzed using the FPGrowth algorithm from SPMF to identify significant association rules. The generated rules are then validated against Wikidata and visualized using interactive graphs.

## Technologies Used

- **Python**: Primary programming language.
- **SPARQLWrapper**: For executing SPARQL queries on DBpedia and Wikidata.
- **SPMF**: Data mining tool used to extract association rules.
- **Pandas**: Data manipulation and analysis.
- **Altair**: Creating interactive visualizations of association rules.
- **NetworkX & Matplotlib**: Generating and visualizing graphs.
- **TQDM**: Progress bars to track task execution.
- **Requests**: Handling HTTP requests.
- **PySpark**: Distributed data processing.

## Usage

Open the notebook `analysis_notebook.ipynb` and follow the steps outlined to execute the complete analysis.

## Results

The identified association rules are visualized below. This graph showcases the main associations between the properties of `dbo:Person` entities in DBpedia.

![Association Rules Graph](https://i.imgur.com/34XCf6M.png)

