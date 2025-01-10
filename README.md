# Fjord5G: A Comprehensive 5G Dataset for Coastal Maritime Connectivity

Welcome to the Fjord5G GitHub repository! 

The Fjord5G is a 5G dataset for coastal maritime connectivity research. We conduct an extensive measurement campaign aboard research and public ferries in the Kiel Fjord, Germany, collecting GPS-located cellular data along maritime routes. These measurements cover the network conditions encountered in coastal and near-shore regions and provide insights into metrics such as signal strength, modulation, and bandwidth. The resulting dataset includes cellular measurements at a sampling rate of 1 Hz from two mobile network operators, four 5G routers, and two ferries for up to 12 months per router.

The dataset is available at [Zenodo](https://doi.org/10.5281/zenodo.14627352). Currently, the corresponding paper is under review. It will be added in the future.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14627352.svg)](https://doi.org/10.5281/zenodo.14627352)

This project is licensed under the terms of the Creative Commons Attribution 4.0 International License.

## Usage:

1. Download the dataset from Zenodo into the data folder

2. Clone this Git repository to your local machine using the following command:

```
git clone https://github.com/ds-kiel/Fjord5G.git
cd Fjord5G
```

3. Create a virtual Python environment (e.g. using pyenv)

```
curl https://pyenv.run | bash
pyenv install 3.13.1
pyenv virtualenv 3.13.1 Fjord5G
```

4. Install the necessary Python packages by running:

```
pip install -r requirements.txt -U
```

5. Analyze the data with the supplied Jupyter Notebooks

## Citation
B. Denizer and O. Landsiedel, ‘Fjord5G: A Comprehensive 5G Dataset for Coastal Maritime Connectivity’. Zenodo, Jan. 10, 2025. doi: 10.5281/zenodo.14627352.
```
@dataset{denizer_2025_14627352,
  author       = {Denizer, Birkan and
                  Landsiedel, Olaf},
  title        = {Fjord5G: A Comprehensive 5G Dataset for Coastal
                   Maritime Connectivity
                  },
  month        = jan,
  year         = 2025,
  publisher    = {Zenodo},
  version      = {1.0.0},
  doi          = {10.5281/zenodo.14627352},
  url          = {https://doi.org/10.5281/zenodo.14627352},
}
```