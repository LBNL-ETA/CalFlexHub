# California Load Flexibility Research and Development Hub

The California Load Flexibility Research and Development Hub (CalFlexHub) is the innovation hub
supporting the scaled adoption of affordable, equitable, and reliable load flexible technologies. 
CalFlexHub seeks to advance the capability of smart building technologies to provide flexible 
energy load for the State of California and beyond. More information can be found 
[here](https://calflexhub.lbl.gov/).

## How to use this repository

CalFlexHub has made a set of fictitious, prototype research price profiles available
through the CEC's Market Informed Demand Automation Server [(MIDAS)](https://www.energy.ca.gov/proceedings/energy-commission-proceedings/load-management-rulemaking/market-informed-demand).
To support affiliates, a jupyter notebook showing how to receive prices (_ReceivingPrices-midas.ipynb_) has been provided.
The steps to receive prices from MIDAS are as follows:

1. To clone this repository and use the code:
  ``` git clone https://github.com/LBNL-ETA/CalFlexHub.git ```
2. This repository contains code written in Python3
  and Jupyter notebooks. While [Python3](https://www.python.org/downloads/)
  and [Jupyter notebook](https://jupyter.org/install) interactive environment
  can be installed separately, we recommend setting them up
  using the [anaconda](https://www.anaconda.com/download) platform. 
3. Once they have been install, install dependencies using the provided
  ``requirements.txt`` file and ``pip``:
  
      ``pip install -r requirements.txt``
  
4. Users must set up credentials to use MIDAS. This can be accomplished using the file _registration-midas.ipynb_ 
    - Code in this file is based on the Registration script in the [MIDAS python repository](https://github.com/morganmshep/MIDAS-Python-Repository/tree/main)
5. This process should create a file named _midas_config.yaml_
6. The file _ReceivingPrices-midas.ipynb_ will use these credentials to pull prices from MIDAS. 
    - Partner's can copy and integrate this code into their own existing solutions to create a 'price client'

## Copyright
California Load Flexibility Research and Development Hub (CalFlexhub)
Copyright (c) 2022, The Regents of the University of California,
through Lawrence Berkeley National Laboratory (subject to receipt of
any required approvals from the U.S. Dept. of Energy). All rights reserved.

If you have questions about your rights to use or distribute this software,
please contact Berkeley Lab's Intellectual Property Office at IPO@lbl.gov.

NOTICE.  This Software was developed under funding from the U.S. Department
of Energy and the U.S. Government consequently retains certain rights.  As
such, the U.S. Government has been granted for itself and others acting on
its behalf a paid-up, nonexclusive, irrevocable, worldwide license in the
Software to reproduce, distribute copies to the public, prepare derivative 
works, and perform publicly and display publicly, and to permit others to do so.

## License
CalFlexHub is available under the following [license](https://github.com/LBNL-ETA/CalFlexHub/blob/main/License.txt).

## Contributing

If you are interested in contributing to this project, you are welcome to
report any issues in [Issues](https://github.com/LBNL-ETA/CalFlexHub/issues) 
or reach out to [Anand Prakash](mailto:akprakash@lbl.gov) or 
[Lazlo Paul](mailto:LPaul@lbl.gov).
