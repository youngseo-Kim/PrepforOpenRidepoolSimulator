# Data preparation for OpenRidepoolSimulator

## 1. Directories

### /dataprep

The _/dataprep_ directory contains all the codes for generating data which will be saved in _/dataprep/data_. Note the 'data' folder is exactly in the right format that _OpenRidepoolSimulator/data_ requires. The notebook named _generate data for OpenRidepoolSimulator.ipynb_ creates a graph representing road network for the given area using OpenStreetMap. The resulting graph is saved _nodes.csv, edges.csv, and times.csv_ in _data/map_ directory. Requests are also randomly generated between any two nodes (we will improve the travel demand generation technique later) and the artificial requests are saved as _data/request/requests.csv_. 


## 2. Related resources
Highlevel idea of the simulator can be found below

https://www.overleaf.com/project/61605648ca50a69b92aee363

The matching algorithm is largely related to the OpenRidepoolSimulator that follows the design presented in "On-demand high-capacity ride-sharing via dynamic trip-vehicle assignment" (Alonso-Mora et al, PNAS 2017).

https://github.com/MAS-Research/OpenRidepoolSimulator




## Contributors

**Youngseo Kim**
- Doctoral Student, Cornell University
- email: [yk796@cornell.edu](mailto:yk796@cornell.edu)

**Tomas Rossetti**
- Doctoral Student, Cornell University
- email: [ter58@cornell.edu](mailto:ter58@cornell.edu)
