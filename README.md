# Venny4Py
Simple Venn diagrams for Python 3, up to 4 sets (for more than 4 sets it is better to use UpSet plot).
It will take as input a dictionary of 2-4 sets and produce a venn diagram and a txt file with element intersections.

**Dependencies:**

- itertools
- matplotlib


**Installation:**

    pip install venny4py

When installed, import:

    from venny4py.venny4py import *
    
    #dict of sets
    sets = {
        'Set1': set(list("Harry Potter")),
        'Set2': set(list("Hermione Granger")),
        'Set3': set(list("Ron Weasley")),
        'Set4': set(list("Severus Snape"))
    }
        
    venny4py(sets=sets)


**Parameters:**

- ***sets*** - disctionary of sets (required)
- ***out*** - directory to output files, default current directory
- ***asax*** - if diagram should be plotted as subplot, then provide matplotlib ax here. Default is 'False' which will plot new figure
- ***ext*** - image extension, default is 'png'.
- ***dpi*** - image resolution, default is 300 dpi.
- ***size*** - image size in inches, default is 3.5. If using custom ax through "asax" parameter, specify approximate size of subplot in inches since fontsize is dependent on this parameter.
- ***colors*** - set of colors for each set, default is "bgrc".
- ***line_width*** - control line width.
- ***font_size*** - control font size.
- ***legend_cols*** - number of legend columns, default is 2.
- ***column_spacing*** - column spacing in legend, default is 4.
- ***edge_color*** - edge colors, default is 'black'.


Check "Examples.ipynb" https://github.com/timyerg/venny4py/blob/main/Examples.ipynb to see some examples.



