# The Lack of Interaction between Extrinsic Grouping Factors in Motion-Induced Blindness
Data and the analysis code for the  manuscript "The Lack of Interaction between Extrinsic Grouping Factors in Motion-Induced Blindness" manuscript, submitted to Plos One

## Data
### Experiment 1. "_Grouping via the Kanizsa figure and the common mask_"
The raw data files are located in the [__Kanitza - Raw Data__](Kanitza - Raw Data) folder. The files for the main experiment and for the preliminary fingers-press asynchrony measurement are, correspondingly, in [__Main Experiment__](Kanitza - Raw Data/Main Experiment) and [__Real Disappearances__](Kanitza - Raw Data/Real Disappearances) subfolders. Please use scripts `MatlabToCSV_MainExperiment.m` and `MatlabToCSV_RealDisappearances.m` to convert from Matlab scripts to the CSV tables.

### Experiment 2. "__Grouping via the connecting line and the common mask__"
The raw data files are located in the [__Connecting lines - Raw Data__](Connecting lines - Raw Data) folder. Files that correspond to the preliminary fingers-press asynchrony measurement are marked with `_real_dis` suffix. Please use notebooks [Connecting lines - Import responses](Connecting lines - Import responses.ipynb) and [Connecting lines - Import real disappearances](Connecting lines - Import real disappearances.ipynb) to convert raw data to CSV tables.

### Experiment 3. "__Visibility of the illusory Kaniza triangle__"
The raw data files are located in the [__Kanitza - Raw Data/Static Control__](Kanitza - Raw Data/Static Control) folder. Please use `MatlabToCSV_KanitzaStaticControl.m` script to convert from Matlab scripts to the CSV table.

## Statistical analysis and figures
### Experiment 1. "_Grouping via the Kanizsa figure and the common mask_"
* Disappearance time analysis, Fig. 2A-D: [Experiment 1. Kanitza - Disappearance time](Experiment 1. Kanitza - Disappearance time.ipynb)
* Key press simultaneity analysis, Fig. 2E-H: [Experiment 1. Kanitza - Response simultaneity](Experiment 1. Kanitza - Response simultaneity.ipynb)

### Experiment 2. "__Grouping via the connecting line and the common mask__"
* Disappearance time analysis, Fig. 3A-D: [Experiment 2. Connecting lines - Disappearance time](Experiment 2. Connecting lines - Disappearance time.ipynb)
* Key press simultaneity analysis, Fig. 3E-H: [Experiment 2. Connecting lines - Response simultaneity](Experiment 2. Connecting lines - Response simultaneity.ipynb)

### Experiment 3. "__Visibility of the illusory Kaniza triangle__"
* Disappearance time analysis, Fig. 4AB: [Experiment 3. Kanitza control - Disappearance time](Experiment 3. Kanitza control - Disappearance time.ipynb)
* Kanitza visibility analysis, Fig. 4CD: [Experiment 3. Kanitza control - Kanitza visibility](Experiment 3. Kanitza control - Kanitza visibility.ipynb)

## License
All data (and associated content) is licensed under the [CC-By Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/). All code is licensed
under the [MIT License](http://www.opensource.org/licenses/mit-license.php).
