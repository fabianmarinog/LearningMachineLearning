# LearningMachineLearning
Baby steps into Machine Learning

Following Google Developer Machine Learning Video series

1. Recipe for supervised learning (a technique to create a classifier from examples): https://www.youtube.com/watch?v=cKxRvEZd3Mw

  1.1 Installed Anaconda for Python 2.7: https://www.continuum.io/downloads
  
  1.2 In repo type: `python hello-world.py`
  
  1.3 result: [1]
  
  Done. My first `hello world` in Machine Learning!

2. Visualizing a Decision Tree. Build one on a real dataset, add code to visualize it, and practice reading it. https://www.youtube.com/watch?v=tNa99PG8hR8

 2.1 create viz.py

 2.2 In repo type: `python viz.py`

 2.3 Pdf generation failed with this error: `GraphViz\'s executables not found'` Seems like a path problem with pydot

 2.4 Predictions work like a charm. 

3. What Makes a Good Feature - concepts by using a histogram to visualize a feature from a toy dataset. 

 3.1 create dogs.py

 3.2 In repo type: `python dogs.py`

 3.3. A graphic should appear. I didn't first time. I had to fix the error: `ImportError: No module named matplotlib`

 3.4 `curl -O https://bootstrap.pypa.io/get-pip.py`

 3.5 `python get-pip.py`

 3.6 `pip install matplotlib`

 3.7 Create a file `~/.matplotlib/matplotlibrc` there and add the following code: backend: `TkAgg` http://stackoverflow.com/questions/21784641/installation-issue-with-matplotlib-python

 3.8 Done. it shows the graphic.
