# San Francisco Rental Market Analysis

![Photo of the Painted Ladies with downtown San Francisco in the Background](https://ei.marketwatch.com/Multimedia/2019/03/07/Photos/ZH/MW-HF311_sanfra_20190307211532_ZH.jpg?uuid=0d287a22-4148-11e9-b892-ac162d7bc1f7)

---
This program analyzes rental market data for the San Francisco area over a six year period, from 2010-2016. It tracks the average year to year rental income and the sales price per square foot to determine if there are neighborhoods that a company should invest in that are interested in a potential one-click, buy-and-rent strategy.


---
## Technologies:

This program runs on [Python 3.7](https://www.python.org/). It utilizes [PyViz](https://pyviz.org/) and [Jupyter Lab](https://jupyter.org/install)


---
## Installation Guide:
If you do not have the `PyViz` Ecosystem installed which includes `hvplot` and `geoviews`; before openning the program copy and run the following in your terminal:

```python
conda install -c pyviz hvplot geoviews
```

Once you have installed the `PyViz` ecosystem open `san_francisco_housing.ipynb` with Jupyter Lab.

Import the following libraries for the program to run:

```python
import pandas as pd
import hvplot.pandas
from pathlib import Path
```

---
## Usage:

Moving through the program you will start seeing the housing data being visualized through different plots, such as:

![Screen shot of a line plot showing the sales price and average gross rent by neighborhood](https://user-images.githubusercontent.com/89755088/140631825-0be33058-34ab-4f1b-9bec-70a7d5674e07.png)

![Screen shot of a map of San Francisco with neighborhoods plotted on it](https://user-images.githubusercontent.com/89755088/140631748-2d765fc0-9f59-414b-b0f9-4180e70ee5bb.png)

---
## Contributors:

Code was written by Thomas Leahy, thomasleahy6@gmail.com
In conjunction with © 2020 - 2021 Trilogy Education Services, a 2U, Inc. brand.

---
## Licence:

MIT

2021 Thomas Leahy