# OceanSciences2022
Repository containing the tutorial notebook run during the Townhall Sesion titled

## Open Science Analysis of Petabyte Scale Ocean and Ocean-Atmosphere Models with Open Source Cloud Tools







Howto:

The notebooks need to be run within Sciserver to access the model data and correct (conda) environment. Furthermore, within Sciserver, the notebooks 
only run within a container created with the `Oceanography 2.3` Compute image, along with access to either the `Poseidon` (for llc4320) or `Ocean Circulation`
(for ECCO) data volumes.

The folder `img/` contains static images used in the notebooks for model-data comparison. The folder needs to be added within the (local) directory as to where
the tutorial notebooks are stored, so that within the notebooks `img/figure.png` sucessfully loads the static images.


