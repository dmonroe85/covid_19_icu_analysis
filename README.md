# March 2020 COVID-19 Analysis

The goal of this analysis is to estimate when individual countries will exceed
their ICU capacity due to the incoming COVID-19 cases.

### Getting Started

Requires git, python3.7 and virtualenv.  Developed on Ubuntu.

    git clone https://github.com/CSSEGISandData/COVID-19
    virtualenv -p python3.7 v
    source v/bin/activate
    pip install -r requirements.txt
    jupyter notebook

Open the `HospitalCapacity.ipynb` notebook and run all cells.  The interactive
analysis cell is at the end.
