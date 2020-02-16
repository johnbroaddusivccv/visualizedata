# Visualize Data with Bokeh
Manipulating data with [Bokeh](https://docs.bokeh.org/en/latest/index.html) and [Pandas](https://pandas.pydata.org/)
## Installation && usage
```bash
git init
```

```bash
git clone https://github.com/johnbroaddusivccv/visualizedata.git
```

```bash
cd visualizedata/
```

Make sure Python is installed 
```bash
python ––version
```
When using python it's important to create a virtual enviroment. A virtual enviroment is a tool that helps keep dependencies required by different projects separate by isolation.
- - -
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install [Bokeh](https://docs.bokeh.org/en/latest/index.html).
- - -
To create a virtual enviroment bash the following:
* on windows 10
```bash
py -m venv venv
```
to activate the virtual enviroment bash the following:
```bash
source venv/scripts/activate
```
- - - 
* on mac
```bash
pip install virtualenv
```
```bash
virtualenv venv
```
- - - -
To deactivate the virtual enviroment bash the following:
```bash
deactivate
```
Using [pip](https://pip.pypa.io/en/stable/) we are going to install [Bokeh](https://docs.bokeh.org/en/latest/index.html).
* On windows 10
```bash
py -m pip install bokeh
```
* On Mac
```bash
pip install bokeh
```
- - - - 
bash the following to see what Bokeh does:
```bash
python main.py
```
It creates a graph using the data in the CSV file [cars.csv](https://github.com/johnbroaddusivccv/visualizedata/blob/master/cars.csv)
