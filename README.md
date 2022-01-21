# Data preparation for OpenRidepoolSimulator

This repository is for generating data to be used in OpenRidepoolSimulator 
https://github.com/MAS-Research/OpenRidepoolSimulator


Generated data will be saved in _/data_. Note the 'data' folder is exactly in the right format that _OpenRidepoolSimulator/data_ requires. The notebook named _generate data for OpenRidepoolSimulator.ipynb_ creates a graph representing road network for the given area using OpenStreetMap. The resulting graph is saved _nodes.csv, edges.csv, and times.csv_ in _data/map_ directory. Requests are also randomly generated between any two nodes (we will improve the travel demand generation technique later) and the artificial requests are saved as _data/request/requests.csv_. Vehicles are also artificailly generated. 

## Contributors

- Youngeso Kim (yk796@cornell.edu)
- Michael P Wilbur (michael.p.wilbur@vanderbilt.edu)
- Matthew Zalesak (mdz32@cornell.edu)
