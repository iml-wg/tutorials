## Machine Learning Tutorials

# Setting up workspace
* In swan select configuration 93

* Open a terminal and clone the repository from github
```
git clone https://github.com/iml-wg/tutorials
```

* Go to the directory data
```
cd tutorials/notebooks/data/
```
and download the required datasets executing
```
sh getdata.sh
```

* Install python dependecies executing
```
pip install scikit-learn dask[array] --user
```

# Parallel execution 

For parallel execution add in the first cell
```
ROOT::EnableImplicitMT(8);
```
to use the 8 threads in swan.

