## DOSSL

This repository contains the author's implementation Pytorch in  paper "Open-world Structured Sequence Learning Via Dense Target Encoding".


## Dependencies

- Python (>=3.6)
- torch:  (>= 1.7.0)
- numpy (>=1.17.4)
- sklearn



## Implementation

Here we provide the implementation of DOSSL along with the default dataset (DBLP5). The repository is organised as follows:

 - `data/` contains the necessary dataset files and config files;
 - `code/` contains the implementation of the DOSSL and the basic utils;

 Finally, `main.py` puts all of the above together and can be used to execute a full training run on the datasets.

## Process
 - Place the datasets in `data/`
 - Training/Testing:
 ```bash
 python main.py
 ```
 
