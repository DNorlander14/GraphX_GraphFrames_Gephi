# GraphX_GraphFrames_Gephi
## Amazon product co-purchase network analysis and visualization 
Our project uses PySpark, Spark GraphFrame and Gephi for Amazon product co-purchase network analysis and visualization. The data is provided by Standford University. (https://snap.stanford.edu/data/com-Amazon.html)   

Computing Environment:   
Experimental VM (installation instructions: https://github.com/paulovn/ml-vm-notebook)   
Pyspark 3 (comes with Experimental VM)   
Gephi 0.9.2 (https://gephi.org/users/download/)   
GraphFrames (comes with Experimental VM with command: vagrant provision --provision-with graphframes)   
JAVA 7/8 (for Gephi)   

We created a small network using our teammates' name in the 'Trends market example code.ipynb'. We demonstrate some most commonly used functions in GraphFrames using this small network. The 'Data Transformation using graphframes.ipynb' is our analysis of Amazon co-purchasing data. The csv file is pur output from the jupyter notebook. Then we used Gephi to visualize the dataset in the csv file.

