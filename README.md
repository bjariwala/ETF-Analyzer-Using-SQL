# Module_7_Challenge
This application helps Passive investors build a financial database and web application by using SQL, Python, and the Voilà library to analyze the performance of a hypothetical fintech ETF.

---
## Technologies

- [Anaconda](https://www.anaconda.com/products/individual) - Pandas is included in Anaconda distribution and Conda package manager to manage Python environments.
- [Jupyter Lab](https://jupyter.org/) - web-based user interface designed for data analysis. It lets you write, run, and review the results in Python programs (all in a single integrated development environment (IDE).
[Voila Documentation](https://voila.readthedocs.io/en/stable/index.html) - Voilà allows you to convert a Jupyter Notebook into an interactive dashboard that allows you to share your work with others.
S[QLALCHEMY](https://www.sqlalchemy.org) - SQLAlchemy is the Python SQL toolkit and Object Relational Mapper that gives application developers the full power and flexibility of SQL.
[hvPlot](https://hvplot.holoviz.org) - A high-level plotting API for the PyData ecosystem built on HoloViews. hvPlot provides an alternative for the static plotting API provided by Pandas and other libraries, with an interactive Bokeh-based plotting API that supports panning, zooming, hovering, and clickable/selectable legends

---
## Installation Guide

Install SQLAlchemy
SQLAlchemy is an open-source SQL library for Python. It’s designed to ease the communication between Python-based programs and databases. The SQLAlchemy library should have installed on your computer as part of the Anaconda download.

To confirm that SQLAlchemy installed in your Conda dev environment, open a terminal window, and then complete the following steps:
Activate your Conda dev environment.
Run the following command:
```
conda list sqlalchemy
```
If SQLAlchemy is already installed, sqlalchemy and its version number will display in your terminal, as the following image shows. In this case, you don’t need to do anything further for SQLAlchemy. Move to the next section to install Voilà.

A screenshot depicts the name sqlalchemy and its version number in the terminal.
If sqlalchemy doesn’t display in your terminal, you need to install it. To do so, follow these steps:
With your Conda dev environment still active, run the following command:
```
pip install SQLAlchemy
```
When the installation completes, confirm it by running the following command:
```
conda list sqlalchemy
```
Note that your terminal should now display sqlalchemy and its version number, as the previous image shows.

Install Voilà
With Voilà, a Python library, you can convert a Jupyter notebook into a live webpage. You’ll need this library later in the module when you create web applications that use databases.

Activate your Conda dev environment.
Run the following command:

conda install -c conda-forge voila
Confirm that the installation succeeded by running the following command:
```
conda list voila
```
If Voilà successfully installed, voila and its version number will display in your terminal window, as the following image shows:

A screenshot depicts the name voila and its version number in the terminal.


## Contributors

Created by Bina Jariwala

---

## License

None

---



