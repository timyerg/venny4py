# Venny4Py
Simple Venn diagrams for Python 3, up to 4 sets (for more than 4 sets it is better to use UpSet plot).
It will take as input a dictionary of 2-4 sets and produce a venn diagram and a txt file with element intersections.

**Installation:**

    pip install venny4py

When installed, import:

    from venny4py.venny4py import *


**Parameters:**

- ***sets*** - disctionary of sets (required)

- ***out*** - directory to output files, default current directory

- ***asax*** - if diagram should be plotted as subplot (matplotlib ax), default is 'False' which will plot new figure

- ***ext*** - image extension, default is 'png'.

- ***dpi*** - image resolution, default is 300 dpi.

- ***size*** - image size in inches, default is 3.5. If using custom ax through "asax" parameter, specify approximate size of subplot in inches since fontsize is dependent on this parameter.


Check "Examples.ipynb" to see some examples.



