# Fjord5G: A Comprehensive 5G Dataset for Coastal Maritime Connectivity

Welcome to the Fjord5G GitHub repository! 

The Fjord5G is a 5G dataset for coastal maritime connectivity research. We conduct an extensive measurement campaign aboard research and public ferries in the Kiel Fjord, Germany, collecting GPS-located cellular data along maritime routes. These measurements cover the network conditions encountered in coastal and near-shore regions and provide insights into metrics such as signal strength, modulation, and bandwidth. The resulting dataset includes cellular measurements at a sampling rate of 1 Hz from two mobile network operators, four 5G routers, and two ferries for up to 12 months per router.

The paper is accepted at the 2025 IEEE 101st Vehicular Technology Conference: [VTC2025-Spring](https://events.vtsociety.org/vtc2025-spring).
The dataset is available at [Zenodo](https://doi.org/10.5281/zenodo.14627352). 

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14627352.svg)](https://doi.org/10.5281/zenodo.14627352)

This project is licensed under the terms of the Creative Commons Attribution 4.0 International License.

## Usage:

1. Clone this Git repository to your local machine using the following command:

```
git clone https://github.com/ds-kiel/Fjord5G.git
```

2. Create a virtual Python environment (e.g. using pyenv)

```
curl https://pyenv.run | bash
pyenv install 3.13
pyenv virtualenv 3.13 Fjord5G
```

3. Install the necessary Python packages by running:

```
cd Fjord5G
pip install -r requirements.txt -U
```

4. Download the dataset from Zenodo into the data folder


5. Analyze the data with the supplied Jupyter Notebooks

## Citation
B. Denizer et al., "Fjord5G: A Comprehensive 5G Dataset for Coastal Maritime Connectivity", 2025 IEEE 101st Vehicular Technology Conference (VTC2025-Spring), Oslo, Norway, 2025, pp. 1-5
```
@INPROCEEDINGS{Fjord5G,
  author={Denizer, Birkan and Landsiedel, Olaf},
  booktitle={2025 IEEE 101st Vehicular Technology Conference (VTC2025-Spring)}, 
  title={Fjord5G: A Comprehensive 5G Dataset for Coastal Maritime Connectivity}, 
  year={2025},
  volume={},
  number={},
  pages={1-5},
  keywords={Dataset;coastal;maritime;LTE;5G;machine learning;QoS prediction;remote control;autonomous ferry},
  }
```