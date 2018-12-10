# quick_gadget_plot

## Description

A couple of jupyter notebooks with fast plots showing particle distribution of a gadget snapshot using pygadget and vaex

## Preview

- plots all particles of DM, GAS and STARS in the box: [plot_box.ipynb](plot_box.ipynb)
- plots all particles of DM, GAS and STARS in a single subhalo: [plot_single_subhalo.ipynb](plot_single_subhalo.ipynb)

## Installation

1. Clone this repository
  ```bash
    git clone https://github.com/UNAB-AstroNum/quick_gadget_plot
  ```
  
2. Install the vaex library
  - Anaconda users: `conda install -c conda-forge vaex`
  - Regular Python users using pip: `pip install --pre vaex`

3.  Install matplotlib and pandas if necessary

## Running the notebook

1. Initialize the notebook
  ```bash
    jupyter notebook
  ```

2. Open one the example notebook files
  - [plot_box.ipynb](plot_box.ipynb)
  - [plot_single_subhalo.ipynb](plot_single_subhalo.ipynb)
