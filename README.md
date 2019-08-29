# Visualizing Flux Maps of Death
Visualizing Flux Maps of Death to Determine Antibiotics' Mechanism of Action 

# Installation
Download and install miniconda then install the dependencies with: 

    git clone https://github.com/KosarL/visualizing_flux_maps.git
    cd visualizing_flux_maps
    conda env create -f environment.yml
    
To start the notebook type:

    conda activate FLUX
    jupyter notebook Vizualizing_flux_maps.ipynb
    
# About the Program 
This program maps the biochemical pathways in a bacterial cell. 
By running this program based on example_data, the program maps the given nodes. 
To be able to run the program, the x and y coordinates of the nodes are needed as well as the flux ratios at each time point. 

The example_data gives the reactions in glycolysis and TCA cycle. 

  
