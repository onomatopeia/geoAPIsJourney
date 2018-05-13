# geoAPIsJourney
A journey over APIs for geographical data

The repository contains a Jupyter notebook that will allow you to find an ice cream shop that is the closest to your location and to determine the shortest route to get there. 

# Installation (Python 3)
1. [Optional] Create a virtual environment 
If you have Anaconda:
```
conda create -n geo
activate geo
```

2. Install required packages
```
pip install -r requirements.txt
```

3. If you are on Linux / Mac, aditionally install Shapely
```
pip install shapely
```
If you are on Windows, download Shapely whl file adequate for your Python version (cp27 for Python 2.7, cp34 for Python 3.4, and so on) and your system architecture (32 or amd64). Then install it using pip
```
pip install <path to Shapely.whl>
```

4. Run Jupyter Notebook engine
```
jupyter notebook
```

5. Jupyter Notebook will start in your browser. Open Routing.ipynb and voila! 

Have fun finding the nearest ice cream shop and enjoy your ice cream!
