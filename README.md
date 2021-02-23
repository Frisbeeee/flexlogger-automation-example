# FlexLogger Python Automation Example
This example automates a FlexLogger test session with the [FlexLogger Automation API](https://github.com/ni/niflexlogger-automation-python) and analyzes the resulting data with the same Python program. The repo includes a PDF showing a completed run of the example's Python Jupyter Notebook. 

This example was written with:
- [FlexLogger 2021 R1](https://www.ni.com/en-us/shop/data-acquisition-and-control/flexlogger.html)
- [Jupyter Notebook](https://jupyter.org/)
- Python 3.6.8
- Key Python packages:
  - [niflexlogger-automation](https://github.com/ni/niflexlogger-automation-python)
  - [npTDMS](https://pypi.org/project/npTDMS/)
  - [matplotlib](https://matplotlib.org/stable/index.html)
  - [NumPy](https://numpy.org/doc/stable/user/index.html)
  
## Example Overview
Using a Python Juptyer Notebook, this example covers basic data acquisition and analysis:
- Connect to FlexLogger and run a test
- Read the resulting TDMS data file
- Review relevant test metadata
- Check the measurements were within a desired range
- Visualize the measurements
