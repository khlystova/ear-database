### Database "Magnetic fields and plasma flows during the emergence of active regions in the solar photosphere (1999-2008)"

#### Description

Active regions on the Sun are formed as a result of the magnetic field emergence from the convective zone into the atmosphere. The created database contains parameters of magnetic fields and plasma flows at the stage of development of active regions. The database includes active regions that appeared on the visible side of the Sun in 1999-2008. The selected active regions are isolated from large concentrations of existing magnetic fields and have fairly complete sets of observational data from the SOHO/MDI solar space telescope.

#### Database structure

The database includes 224 emerging active regions. For each active region, the following are given: NOAA number or EFR designation, date and time, heliographic coordinates, parameters of magnetic flux, plasma flows and sunspots in the solar photosphere at different stages of the active region formation. These data are presented as a table and divided into 5 blocks:
1) Data at the beginning of active region emergence;
2) Data at the end of the first hours of active region evolution;
3) Data between the beginning and end of the first hours of active region evolution;
4) Data at the maximum of active region evolution;
5) Data between the beginning and maximum of active region evolution.

The database is stored in formats: h5, csv, and html.

**"h5"** refers to HDF-format, see details [here](https://en.wikipedia.org/wiki/Hierarchical_Data_Format).
<br>
**"csv"** is a simple text format to store tabular data.

#### Related Publications

Description of the used data, criteria for selecting the emerging active regions and methods for calculating the parameters included in the database can be found in the article by
[Khlystova A.I., The Relationship between Plasma Flow Doppler Velocities and Magnetic Field Parameters During the Emergence of Active Regions at the Solar Photospheric Level, Solar Physics, Volume 284, Issue 2, pp. 329-341 (2013)](https://doi.org/10.1007/s11207-020-01734-9) // [ArXiv](https://arxiv.org/abs/1204.4536)

#### Сitation of Database

Khlystova A.I., The Relationship between Plasma Flow Doppler Velocities and Magnetic Field Parameters During the Emergence of Active Regions at the Solar Photospheric Level, Solar Physics, Volume 284, Issue 2, pp. 329-341 (2013). https://doi.org/10.1007/s11207-020-01734-9

-----

#### Repository description

- Database in different formats with identical content:
  - ear.h5
  - ear.csv
  - ear.html
- Use cases in Python (folder 'examples'):
  - Database description (01-description.ipynb)
  - Plots for simple dependencies (02-examples.ipynb)

Files with content in Russian have names with **"-ru"**
<br>
#### Requirements to run examples

* Python 3 (>3.6)
* Interactive Python
* [Pandas](https://pandas.pydata.org/docs/)
* [Numpy](https://github.com/numpy/numpy)
* [h5py](https://github.com/h5py/h5py)
* [Matplotlib](https://matplotlib.org/stable/users/installing.html)