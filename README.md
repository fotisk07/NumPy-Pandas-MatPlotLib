# NumPy-Pandas-MatPlotLib
Projects from the Udacity Nanodegree AI Programming with Python in the form of Jupyter Notebooks . 
The [first notebook](https://github.com/fotisk07/NumPy-Pandas-MatPlotLib/blob/master/Mean%20Normalization%20and%20Data%20Separation%20.ipynb) uses NumPy to perform mean normalization.
The [Second notebook](https://github.com/fotisk07/NumPy-Pandas-MatPlotLib/blob/master/Statistics%20from%20Stock%20Data.ipynb) uses Pandas to extract useful information concerning Apple, Amazon, and Google stocks.
The remaining notebooks demonstrate basic features of the MatPlotLib library.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

The Code inside the nptebooks is written in Python 3.6.5 . If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. 

To install pip run in the command Line
```
python -m ensurepip -- default-pip
``` 
to upgrade it 
```
python -m pip install -- upgrade pip setuptools wheel
```
to upgrade Python
```
pip install python -- upgrade
```

You will also need to download the Numpy, Pandas and MatplotLib packages. Again in the command Line type
```
pip install numpy 
pip install pandas
pip install matplotlib
```
to download them using pip or

```
conda install numpy pandas matplotlib 

```
and type Yes when asked to to download them using Anaconda.


### Viewing the Jupyter Notebook

In order to better view and work on the jupyter Notebook I encourage you to use [nbviewer](https://nbviewer.jupyter.org/) . You can simply copy and paste the link to this website and you will be able to edit it without any problem. Alternatively you can clone the repository using 
```
git clone https://github.com/fotisk07/NumPy-Pandas-MatPlotLib/
```
then in the command Line type, after you have downloaded jupyter notebook type
```
jyputer notebook
```
locate the notebook and run it.

### Data

The [NumPy Project](https://github.com/fotisk07/NumPy-Pandas-MatPlotLib/Mean-Normalization-and-Data-Separation.ipynb) does not require any external dataset . However the [Pandas](https://github.com/fotisk07/NumPy-Pandas-MatPlotLib/blob/master/Statistics%20from%20Stock%20Data.ipynb) one does require Stock data from 3 companies in order to work. Stock data are already provided in the Folder data in the form of 3 .csv files(APPL, AMZN, GOOG), but feel free to use any other data you wish by doing the appropraite modifications. Also the [Bar_Chart_Practice](https://github.com/fotisk07/NumPy-Pandas-MatPlotLib/blob/master/Bar_Chart_Practice.ipynb) , the [Histogram_Practice](https://github.com/fotisk07/NumPy-Pandas-MatPlotLib/blob/master/Histogram_Practice.ipynb) and the [Scales_and_Transformations_Practice](https://github.com/fotisk07/NumPy-Pandas-MatPlotLib/blob/master/Scales_and_Transformations_Practice.ipynb) notebooks require external data in order to create the relative plots. Two datasets are provided, Pokemon and fuel data, but you can use any data to plot the relative diagrams if you perform the necessery modifications. 


## Contributing

Please read [CONTRIBUTING.md](https://github.com/fotisk07/NumPy-Pandas-MatPlotLib/blob/master/CONTRIBUTING) for the process for submitting pull requests. 

## Authors

* **Fotios Kapotos** - *Initial work* 

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/fotisk07/NumPy-Pandas-MatPlotLib/blob/master/LICENSE) file for details

