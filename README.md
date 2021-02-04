# Example notebook for S6 - Generation of spectral indexes 

Practical activity during the [Geology & Planetary Mapping Winter School Program](https://www.planetarymapping.eu/375/program.html)
- **Name** : S6 - Generation of spectral indexes
- **Lead**: Francesca Altieri (INAF); Francesca Zambon (INAF)
- **Description** :  Exploiting spectral data to generate compositional indexes.
- **Instructors** : Cristian Carli (INAF); Sabrina Ferrari (UNIPD); Mario D'Amore (DLR); Jacopo Nava (UNIPD)
- **Data preparation** : Francesca Altieri (INAF); Francesca Zambon (INAF)
- **Data Source** : Data from NASA MESSENGER/MDIS camera from Mercury. Data available here below.
    * [MESSENGER > Explore > Quick Map-Orbital-Data](https://messenger.jhuapl.edu/Explore/Quick-Map-Orbital-Data.html)
    * [MESSENGER Imaging Node Mission Page](https://pds-imaging.jpl.nasa.gov/portal/messenger_mission.html)
    * [PDS Geosciences Node Data and Services: MESSENGER Mission](https://pds-geosciences.wustl.edu/missions/messenger/index.htm)
- **Code** : Mario D'Amore (DLR, mario.damore@dlr.de)

This project has received funding from the European Union's Horizon 2020 research and innovation programme under grant agreement No 776276 & No. 871149.


![european flag wikicommon](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b7/Flag_of_Europe.svg/320px-Flag_of_Europe.svg.png)

Exploiting spectral data to generate compositional indexes. See attacched presentations.

## Setup working enviroment

You can install python modules in any way you want to run this notebook, if you have the following packages available :

```
pip install jupyterlab numpy pandas matplotlib ipython rasterio skimage
```

**The easy way** is to install anaconda for your OS > [Installation — Anaconda documentation](https://docs.anaconda.com/anaconda/install/) then :

```
## create an enviroment with the desired packages
conda create -n spectral-indexes-workshop -c conda-forge jupyterlab numpy pandas matplotlib ipython rasterio skimage

## activate it
conda acrivate spectral-indexes-workshop

## run jupyter lab
jupyter lab

## then open this ipynb : ipython notebook
```
