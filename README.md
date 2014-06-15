visualization_project
=====================

This is a visualization project. For detailed info, visit www.luhangxin.info


TOOLS I USED FOR THIS PROJECT:

Ipython: command shell for interactive computing (http://ipython.org/)

Networkx: a Python language software package for the creation, manipulation, and study of the structure, dynamics, and functions of complex networks. (http://networkx.github.io/)

other libraries for scientific computing: SciPy, NumPy etc.

d3.js : Javascript library for manipulating documents based on data  (http://d3js.org/)

VISUALIZATIONS 
 1. Random graph visualization
 2. Brain Visualization
    - force-directed layout with fisheye distortion
    - with position information
    - integrated interface showing centrality information
 3. Social network visualization
 
HOW TO USE IT?
 1. go to different files
 2. run the ipynb to generate json file or use the existing json file
 3. run the html file to see the visualization using the followin command: 
python -m SimpleHTTPServer 8888 &
 4. go to http://localhost:8888/
note: you can also change 8888 to any number from 0 to 8888. e.g. 7900
