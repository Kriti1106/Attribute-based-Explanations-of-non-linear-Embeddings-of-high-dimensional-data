# NoLiES: The non-linear embeddings surveyor
This repository contains a Jupyter Notebook implementation of the method presented in "Attribute-based Explanation of Non-Linear Embeddings of High-Dimensional Data" by Jan-Tobias Sohns, Michaela Schmitt, Fabian Jirasek, Hans Hasse, and Heike Leitte, submitted to IEEE VIS 2021.

## Requirements
- pandas
- bokeh
- pyviz::panel
- scikit-learn
- conda-forge::umap-learn
- shapely


## Datasets used
- Iris (150x5)
- Wine (178x14)
- OECD Better Life (41x11)
- Penguins (344x7)
- Covertype (3500x11)

## Working with your own data

Download the repository and create an environment with the dependencies:
```
git clone https://github.com/Kriti1106/Attribute-based-Explanations-of-non-linear-Embeddings-of-high-dimensional-data.git
conda env create -f nolies.yml
conda activate nolies
```

Make a copy of the temple jupyter notebook:
```
cp template.ipynb my_data.ipynb
```

Update the notebook to load your data. Open the notebook with jupyter lab or jupyter notebook and edit the section **Load data**. Important parameters are grouped in the section **Parameters** and **Preprocessing**:
```
jupyter lab
```


## Acknowledgements
This is a clone code for the research paper-  Attribute-based Explanation of Non-Linear Embeddings of High-Dimensional Data by Jan-Tobias Sohns, Michaela Schmitt, Fabian Jirasek, Hans Hasse, and Heike Leitte.